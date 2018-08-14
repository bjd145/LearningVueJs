<template>
    <ul>
        <li v-for="todo in todos">{{ todo.title }}</li>
    </ul>
</template>

<script>
export default {
    data() {
        return {
            todos: [
                { id: 1, title:"Clean room"},
                { id: 2, title:"Put dishes away"},
                { id: 3, title:"Wash Car"}
            ]
        }
    }
}
</script>
