<template>
    <div class="post">
        <div class="post__title">
            Lorem ipsum dolor sit amet.
        </div>
    </div>
</template>
<script>
    export default {
        data() {
            return {};
        }
    };
</script>
<style lang="scss" scoped>
    @import '~_sass/config/vars';
    @import '~_sass/config/mixins';

    .post {
        background-color: $color-white--base;
        box-shadow: 0 1px 3px rgba($color-black--base,0.12), 0 1px 2px rgba($color-black--base,0.24);
        // transition: box-shadow 0.3s cubic-bezier(.25,.8,.25,1);

        margin: 10px 0 ;
        padding: 10px;

        // &:hover {
        //     box-shadow: 0 4px 8px rgba($color-black--base,0.25), 0 8px 8px rgba($color-black--base, 0.22);
        // }
        &__title {
            font-size: rem(20px);
        }
    }
</style>
