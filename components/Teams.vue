<script async setup lang="ts">
import Players from '~/components/Players.vue'

const { t } = useI18n({ useScope: 'global' })
const props = defineProps<{
	city: {
		id: bigint
	}
}>()
const { data: teams } = await useFetch(`/api/basketball/teams?city_id=${props.city.id}`)
</script>

<template>
	<section v-for="team in teams" :key="team.name">
		<h1>
			{{ team.name }}
    </h1>

		<p>
			Record
			{{ team.won }} - {{ team.lost }}
		</p>
		<Players :team="team" />
	</section>
</template>
