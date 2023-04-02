<!-- TodoHeader.vue, TodoInput.vue, TodoList.vue, TodoFooter.vue -->

<template>
    <div>
    <button type="button" v-on:click="clearTodo">전체삭제</button>
</div>
</template>

<script>
export default {
    methods: {
        clearTodo(){
            localStorage.clear();
        }
    }
}
</script>

<style>

</style>