<template>
	<section style="margin-top: 1.5rem; padding: 1rem; border: 1px solid #ddd; border-radius: 12px">
		<h2 style="margin: 0 0 0.5rem 0">Vue island</h2>
		<p style="margin: 0 0 0.75rem 0; opacity: 0.8">This component is hydrated on the client.</p>

		<button @click="count++">Clicks: {{ count }}</button>
	</section>
</template>

<script setup>
	import { ref } from 'vue'
	const count = ref(0)
</script>
