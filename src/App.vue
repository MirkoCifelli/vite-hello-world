<script>
// importo il componente
import AppHeader from './components/AppHeader.vue';
//  2 dichiaro il componente all interno dell oggetto
//  3 utilizzo del componente
export default {
    data() {
        return { 
            count: 0 
        }
    },
    // 2
    components:{
        AppHeader
    }
   
}
</script>

<template>

    <div>
        <!-- 3 -->
        <AppHeader/>
        <h1>
            Ciao
        </h1>
        <p>
            {{ count }}
        </p>
        <button @click="count++">
            Incrementa il count
        </button>
    </div>
</template>

<style scoped>

</style>
