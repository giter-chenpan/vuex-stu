
<template>
<div>
    <h2>{{msg}}</h2>
    <h3>{{$store.state.count}}</h3>
    <button @click="$store.commit('add')">+</button>
    <button @click="$store.commit('reduce')">-</button>
 </div>  
</template>

<script>
import store from '@/vuex/store'
export default {
    data(){
        return{
           msg:'Hello Vuex'
        }
    },
    store
}
</script>

<style>

</style>
