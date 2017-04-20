<template>
    <div class="page-wrapper main-content">
        <h1>{{ msg }}</h1>

        <div class="main-content__list-post">
            <list-posts></list-posts>
        </div>
    </div>
</template>

<script>
    import ListPosts from '_modules/post/listPosts';

    export default {
        name: 'hello',
        data() {
            return {
                msg: 'Blog Project with Vuejs'
            };
        },
        components: {
            ListPosts
        }
    };

</script>

<style lang="scss" scoped>
    @import '~_sass/config/vars';

    .main-content {
        padding-left: 2.5%;
        padding-right: 2.5%;
        margin: 0 auto;

        min-height: calc(100vh - 60px);
        max-width: $screen-lg;

        @media screen and (max-width: $screen-md) {
            padding-left: 15px;
            padding-right: 15px;
        }

        h1 {
            text-align: center;
        }
    }
</style>
