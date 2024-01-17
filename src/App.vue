<script>
// importo il componente
import AppTitle from './components/AppTitle.vue';
//  2 dichiaro il componente all interno dell oggetto
//  3 utilizzo del componente
export default {
    data() {
        return { 
            
        }
    },
    // 2
    components:{
        AppTitle
    }
   
}
</script>

<template>

    <div>
        <!-- 3 -->
        <AppTitle/>
        
    </div>
</template>

<style scoped>

</style>
