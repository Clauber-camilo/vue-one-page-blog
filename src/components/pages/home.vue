<template>
    <div class="page-wrapper main-content">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
    export default {
        name: 'hello',
        data() {
            return {
                msg: 'Blog Project with Vuejs'
            };
        }
    };

</script>

<style lang="scss" scoped>
    .main-content {
        min-height: calc(100vh - 60px);
    }
</style>
