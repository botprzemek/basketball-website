<script setup lang="ts">
const { t } = useI18n({ useScope: 'global' })

useHeadSafe({
	title: t(`path.${useRouter().currentRoute.value.name.split('___')[0]}`)
})
</script>

<template>
	<h1>{{ $t(`path.${$route.name.split('___')[0]}`) }}</h1>
	Do pobrania Logo Wersje png pdf jpg ai ksiega znakow
	<a href="/server/api/files/logo/ai">Download</a>
  <section class="w-80">
    <ul class="grid grid-flow-col gap-3">
      <li>
        <svg id="Warstwa_1" data-name="Warstwa 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2048 2048">
          <path d="M0,0v2048h2048V0H0ZM1289.6,682.02h-95.82c-75.61,0-90.29,36.07-90.29,88.76v116.3h180.7l-23.38,182.59h-157.32v466.33h-188.45v-466.68h-156.64v-182.58h156.3v-134c0-155.84,95.47-240.73,234.53-240.73,46.89-.18,93.75,2.23,140.37,7.23v162.78Z"/>
        </svg>
      </li>
      <li>
        <svg id="Warstwa_1" data-name="Warstwa 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2048 2048">
          <path d="M987.23,780.96c-133.66,0-241.94,108.28-241.94,241.94s108.28,241.94,241.94,241.94,241.94-108.32,241.94-241.94-108.32-241.94-241.94-241.94ZM987.23,1180.06c-86.79,0-157.16-70.36-157.16-157.16s70.37-157.16,157.16-157.16,157.16,70.36,157.16,157.16-70.36,157.16-157.16,157.16Z"/>
          <path d="M1295.17,772.01c0,15.59-6.31,29.7-16.51,39.91-10.2,10.2-24.29,16.51-39.86,16.51-31.13.03-56.38-25.18-56.41-56.31v-.11c0-31.14,25.24-56.39,56.39-56.39s56.39,25.25,56.39,56.39Z"/>
          <path d="M0,0v2048h2048V0H0ZM1455.88,1218.89c-.78,39.2-8.16,77.82-21.92,114.46-24.54,63.24-74.55,113.25-137.8,137.79-36.61,13.74-75.3,21.16-114.4,21.93-49.98,2.93-66.36,2.93-194.16,2.93s-143.76-.68-194.16-2.93c-39.18-1.29-77.85-9.25-114.35-23.55-63.27-24.49-113.31-74.49-137.85-137.74-13.76-36.69-21.14-75.31-21.92-114.46-2.94-50.03-2.94-66.36-2.94-194.16s.69-143.76,2.94-194.16c.73-39.08,8.15-77.76,21.92-114.35,24.5-63.27,74.52-113.29,137.8-137.79,36.6-13.74,75.26-21.17,114.35-21.98,49.98-2.88,66.36-2.88,194.16-2.88s143.76.63,194.1,2.88c39.11.8,77.79,8.23,114.41,21.98,63.26,24.51,113.28,74.53,137.79,137.79,13.98,37.1,21.4,76.34,21.93,115.98,2.93,50.08,2.93,66.3,3.03,194.1,0,127.85-.68,143.82-2.93,194.16Z"/>
        </svg>
      </li>
      <li>
        <svg id="Warstwa_1" data-name="Warstwa 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2048 2048">
          <path d="M0,0v2048h2048V0H0ZM1422.5,931.45c-87.58.29-173.04-26.94-244.3-77.85v358.51c-.22,86.76-35.15,169.84-97.01,230.68-127.85,125.75-333.43,124.05-459.18-3.8-57.04-58.42-89.94-136.21-92.12-217.83-4.78-178.98,136.43-327.95,315.41-332.73,17.12-.4,34.23.46,51.22,2.56v179.25c-14.6-4.5-29.8-6.74-45.07-6.66-32.55-.11-64.24,10.51-90.14,30.22-65.06,49.5-77.67,142.37-28.17,207.42,28,37.24,71.89,59.12,118.48,59.07,81.75-.1,147.94-66.44,147.84-148.18v-700.11h176.69v22.53c10.38,106.74,88.34,194.64,193.08,217.67h2.05c16.85,3.47,34.01,5.19,51.22,5.12v174.13Z"/>
        </svg>
      </li>
      <li>
        <svg id="Warstwa_1" data-name="Warstwa 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2048 2048">
          <path d="M0,0v2048h2048V0H0ZM653,1451.09l.71-854.18,741.29,427.8-742,426.38Z"/>
        </svg>
      </li>
    </ul>
  </section>
</template>
