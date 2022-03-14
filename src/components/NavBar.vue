<template>
    <div>  
        <h1>ZAWARUDO</h1>
        <button @click="sayHello">PRESIONAME</button> 
    </div>
</template>

<script>
export default {
    name:"NavBar",

    methods:{
        sayHello(){
            console.log("IT WAS ME DIO")
        }
    }
}

</script>

<style>

</style>