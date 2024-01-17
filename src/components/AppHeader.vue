<script>
export default {
    data() {
        return { 
            title: 'ciao ragazzi'
        }
    },
   
}
</script>

<template>
    <header>
        <h1>
            {{ title }}
        </h1>
    </header>
</template>

<style scoped>
header{
    padding: 20px;
    background-color: aquamarine;
}
h1{
    color: lightcoral;
    text-align: center;
}
</style>
