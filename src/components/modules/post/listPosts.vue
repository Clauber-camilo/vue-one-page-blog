<template>
    <div>
        List Posts
        <post v-for="n in 4"></post>
    </div>
</template>

<script>
    import Post from '_modules/post/post';

    export default {
        data() {
            return {};
        },
        components: {
            Post
        }
    };
</script>
<style lang="scss" scoped>

</style>
