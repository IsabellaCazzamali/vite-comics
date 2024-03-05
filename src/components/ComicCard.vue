<script>
export default {
    name: 'ComicCard',
    props: {
        src: String,
        text: String,
    }
}
</script>

<template>
    <div class="card">
        <img :src="src" alt="">
        <h5>{{text}}</h5>
    </div>
</template>

<style scoped>

</style>