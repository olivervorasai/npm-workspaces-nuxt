<template>
    <h1>
        <slot></slot>
    </h1>
</template>

<script>
export default {
    name: 'HeaderComponent',
};
</script>

<style scoped>
h1 {
    color: red;
    font-size: 2rem;
}
</style>
