<template>
    <div class="layout-main">
        <header-main/>
        <nuxt/>
    </div>
</template>

<script>
import headerMain from "@/components/header-main.vue";

export default {
    components: {
        headerMain
    }
};
</script>

<style scoped>
.layout-main {
    padding-top: 70px;
}
</style>
