<template>
    <a v-on:click="handleClick">Click Me!</a>
</template>

<script>
export default {
    methods: {
        handleClick: function() {
            alert('Hello World')
        }
    }
}
</script>
