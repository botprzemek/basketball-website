<script setup lang="ts">
import heightUtil from '~/utils/data/height.util'

const props = defineProps<{
	player: {
		first_name: string
		last_name: string
		teamName?: string
		number: number
		position: string
		height: number
		age: string
		starter: boolean
	}
}>()

toRefs(props)
</script>

<template>
	<section class="grid grid-flow-col">
<!--		<img-->
<!--			:alt="`${player.first_name} ${player.last_name}`"-->
<!--			src="https://a.espncdn.com/combiner/i?img=/i/headshots/nba/players/full/3449.png&w=70&h=50"-->
<!--		/>-->
		<h5>{{ player.first_name }}</h5>
		<p>{{ player.last_name }}</p>
		<p v-if="player.teamName">{{ player.teamName }}</p>
		<p>{{ player.number }}</p>
		<p>{{ player.position }}</p>
		<p>
			{{ heightUtil(player.height).feet }}'{{ heightUtil(player.height).inch }}" ({{
				player.height
			}}
			cm)
		</p>
		<p>{{ player.age }}</p>
		<p>{{ player.starter ? 'Yes' : 'No' }}</p>
	</section>
</template>
