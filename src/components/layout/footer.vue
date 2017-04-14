<template>
    <div class="footer">
        <p> &copy {{msg}}</p>
    </div>
</template>
<script>
    export default {
        name: 'Main-footer',
        data() {
            return {
                msg: 'A simple blog template'
            };
        }
    };
</script>

<style lang="scss" scoped>

    @import '~_sass/config/vars';
    @import '~_sass/config/mixins';

    .footer {
        height: 60px;
        width: 100%;
        padding: 0 30px;

        border-top: 3px solid $color-blue--medium;

        background-color: $color-blue--dark;

        display: flex;
        justify-content: center;
        align-items: center;

        @include rem("font-size", 12);
        color: $color-white--base;
    }
</style>
