<script >
import ComicsCard from './Card.vue'
import comics from '../assets/data/dc-comics'

export default {
    name: 'FirstBlock',
    components: {
        ComicsCard
    },
    data() {
        return {
            comics: comics,
        }
    },

}


</script>

<template>
    <div id="first-block">
        <div class="header_block">

        </div>
        <div class="main_block">
            <div class=" content">
                <div class="container ">
                    <div class="row row-cols-3 row-cols-sm-4 row-cols-md-6 ">

                        <ComicsCard v-for="comic in comics" :image="comic.thumb" :title="comic.series">
                        </ComicsCard>
                        <!-- <Comics></Comics> -->
                        <!-- <div class="row" v-for="comic in comics">
    
                        </div> -->
                    </div>
                    <div class="button_load py-3">
                        <button class="px-5 py-2 text-white">
                            LOAD MORE
                        </button>

                    </div>

                </div>

            </div>
        </div>
    </div>

</template>

<style scoped>

</style>