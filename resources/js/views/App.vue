<template>
    <!-- scrivo un template vue  -->
    <div>
        <HeaderComp/>
        <!-- qui avviene l'importazione di tutti i componenti 'route -->
        <router-view></router-view>
    </div>
</template>

<script>
import HeaderComp from '../components/HeaderComp.vue'

export default {

    components: {
        //qui metterai i componenti
        HeaderComp,

    },
    data() {
        return {

        }
    },
    mounted() {



    },
    methods: {


    }

}
</script>

