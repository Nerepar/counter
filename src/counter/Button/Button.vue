<template src="./template.html"></template>

<script>
    export default {
        name: "CounterButton",
        methods: {
            changeCounter() {
                this.$emit('changeCounter');
            }
        }
    }
</script>

<style scoped lang="scss" src="./style.scss"></style>