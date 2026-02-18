<template>
	<div style="padding: 1rem; border: 1px solid #ddd; border-radius: 12px">
		<strong>Vue component 1957:</strong>
		<div>Count: {{ count }}</div>
		<button @click="count++" style="margin-top: 0.5rem">Increment</button>
	</div>
</template>

<script setup>
	import { ref } from 'vue'
	const count = ref(0)
</script>
