<script>
export default {
    name: "Card",
    props: {
        image: String,
        title: String,
    }
}
</script>

<template>
    <div class="col my-4">
        <div class="card ">
            <div class="card_image">
                <img :src="image" alt="">
            </div>
            <div class="card_text text-white">{{ title }}</div>
        </div>
    </div>
</template>

<style scoped>
img {
    width: 100%;

}
</style>