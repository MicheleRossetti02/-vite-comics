<script>

import ComicsItem from '../assets/data/dc-comics.js'

export default {
    name: 'Comics'
}



</script>

<template>

    <div class="col">
        <img :src="thumb" alt="">
        <p>{{ price }}</p>
        <p>{{ series }}</p>
        <p>{{ type }}</p>
    </div>

</template>