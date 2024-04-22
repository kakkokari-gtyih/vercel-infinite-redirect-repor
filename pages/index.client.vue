<template>
    <div>
        <p>try <code>?text=foo+bar</code></p>
        <pre><code>{{ query }}</code></pre>
    </div>
</template>

<script setup lang="ts">
const { query } = useRoute();
</script>

<style scoped>

</style>