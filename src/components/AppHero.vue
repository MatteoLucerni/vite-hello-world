<script>
export default {
    data() {
        return {
            picName: 'Sekiro'
        }
    },
    methods: {
        getPath(picName) {
            return new URL(`../assets/${picName}.webp`, import.meta.url).href
        }
    }
}
</script>

<template>
    <main>
        <img :src="getPath(picName)" :alt="picName">
    </main>
</template>