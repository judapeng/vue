<template>
    <banner :img="massage"></banner>

</template>
<script>
import Vue from "vue";
Vue.component('banner',{
    props:["img"],
    data(){
        return {
            img : massage
            }

    },
    template: '<div>{{ img }}</div>'

})


export default {
    data(){
        return{
            name:banner,
            massage:"woshi"


        }
    },


}



</script>