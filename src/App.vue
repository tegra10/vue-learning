<template>
    <p>Hello world</p>
    <p>{{ nom }}</p>
    <button @click="inc">{{ count }}</button>
</template>
<script>
export default {
    data() {
        return {
            nom: "tegra",
            count: 0
        };
    },
    methods: {
        inc() {
            this.count++;
            console.log(this.count)
        }
    }
};
</script>
