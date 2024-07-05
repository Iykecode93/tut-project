<template>
    <div>
        <h1>Todo List</h1>
        <AddTodo @add-todo="addTodo" `/>
    </div>
</template>

<script>
import AddTodo from "./AddTodo.vue";
import TodoItem from "./TodoItem.vue";

    export default {
        components: { AddTodo, TodoItem },
        data() {
            return {
                todos: []
            };
        },

        methods: {
            addTodo(todo) {
                this.todos
            }
        }
    }
</script>

<style scoped>

</style>