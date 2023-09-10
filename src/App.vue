<template>
	<div>
		<card>
			<template v-slot:title>
				<a href="https://www.figma.com/file/sKxXhIHlAtNeA4d94VpjzX/Kumara?type=design&node-id=0%3A1&mode=design&t=O2uRr6A0bsZIoabH-1" target="_blank">
					<img src="./assets/kurama-logo.svg" class="logo kurama" alt="kurama logo" />
				</a>
			</template>
			<template v-slot:body>
				hello world
			</template>
		</card>
	</div>
</template>

<script setup>
import card from '@/components/utility/card.vue';
</script>

<style scoped>
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}
.logo.kurama:hover {
  	filter: drop-shadow(0 0 2em #b84242aa);
}
</style>
