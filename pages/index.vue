<template>
    <div class="container mx-auto w-1/2 py-8">
        <CatFact v-for="fact in catFacts" :fact="fact" />
    </div>
</template>

<script setup>
    const { data:catFacts } = await useFetch('http://localhost:8000/api/catFacts/10')
</script>