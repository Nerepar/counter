<template src="./template.html"></template>

<script>
    export default {
        name: "CounterButton",
        methods: {
            changeCounter(value) {
                this.$emit('changeCounter', value);
            },
        }
    }
</script>

<style scoped lang="scss" src="./style.scss"></style>