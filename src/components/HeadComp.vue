
<template>
    <header class="head">
        Olá {{ userName }}
       
    </header>
</template>

<script>


export default{
    data() {
        return {
            userName: 'Cristian'
        };
    }
    
}
</script>

<style>
    .head{
        color: #D6EAFF;
        text-align: left;
        font-family: Helvetica;
        font-size: 19px;
        background-color: #001B2E;
        padding: 10px;
        border: 1px solid #D6EAFF;
    }
</style>