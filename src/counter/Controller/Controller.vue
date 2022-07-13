<template src="./template.html"></template>

<script>
    import Button from "@/counter/Button/Button";
    import Display from "@/counter/Display/Display";

    export default {
        name: "CounterController",
        components: {
            Button, Display
        },
        data() {
            return {
                counter: 0,
            }
        },
        methods: {
            changeCounter() {
                this.counter++;
            }
        }
    }
</script>

<style lang="scss" scoped src="./style.scss"></style>