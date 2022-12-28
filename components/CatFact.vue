<template>
    <div class="mt-2">
        {{ props.fact.fact }}
    </div>
</template>

<script setup>
const props = defineProps({
    fact: Object,
})
</script>