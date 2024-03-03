<template>
    <div class="addbtn" @:click="addTask">
        Add
    </div>
</template>

<script>
    export default{
        methods:{
            addTask(){
                console.log('add')
            }
        }
    }
</script>

<style>
.addbtn{
    width: 60px;    
    margin: 10%;
    padding: 2px;
    background-color: #001B2E;
    color: #D6EAFF;
    border: 1px solid #D6EAFF;
    display: flex;
    justify-content: center;
    
   
}
</style>