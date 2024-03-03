<template>
    <div class="inputcontainer">
        <input @keyup.enter="addTask" class='taskdescript' type="text" v-model="task">
        <div class="addDiv">
            <AddBtn></AddBtn>
        </div>
    </div>
    
</template>

<script>
import AddBtn from './AddBtn.vue';
    export default{
    AddBtn,
    task: '',
    data() {
        return {
            task: ''
        };
    },
    components: { AddBtn }
}
</script>

<style>
    .inputcontainer{
        border: 1.5px solid white;
        display: flex;
        justify-content: center;
    }
    .taskdescript{
        width: 50%;
        padding: 5px;
        margin: 5px;
    }
    
</style>