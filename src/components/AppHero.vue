<script>
export default {
    data() {
        return {
            img: 'banner.png'
        }
    },
    methods: {
        buildImgUrl(img) {
            const url = new URL(`../assets/${img}`, import.meta.url);
            console.log(url.href)
            return url.href;

        }
    }
}

</script>

<template>
    <img :src="buildImgUrl(this.img)">
</template>

<style scoped>
img {
    object-fit: cover;
    width: 100%;
    height: 75%;
    margin: 0;
}
</style>