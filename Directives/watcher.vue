<template>
    <div>
        <button @click="handleClick()">Change my name</button>
        <p>My Name is: {{name}}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: "Brian"
        }
    },
    methods: {
        handleClick: function() {
            this.name = "Denicola"
        }
    },
    watch: {
        name: function() {
            console.log(this.name)
        }
    }
}
</script>
