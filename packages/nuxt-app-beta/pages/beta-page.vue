<template>
    <div>
        <HeaderComponent> This is page from beta </HeaderComponent>
    </div>
</template>

<script>
import HeaderComponent from 'nuxt-app-alpha/components/header-component.vue';

export default {
    name: 'BetaPage',

    components: {
        HeaderComponent,
    },
};
</script>
