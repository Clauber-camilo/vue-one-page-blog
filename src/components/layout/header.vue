<template>
    <div class="header">
        <div class="header__logo">

        </div>
        <ul class="header__items">
            <li><a href="#">Home</a></li>
            <li><a href="#">All posts</a></li>
            <li><a href="#">Search</a></li>
        </ul>
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

    @import '~_assets/sass/config/vars';

    .header {
        height: 60px;
        width: 100%;
        padding: 0 30px;

        border-bottom: 3px solid $color-rosewood;

        background-color: $color-red--sub;

        display: flex;
        justify-content: space-between;
        align-items: center;

        &__logo {
            width: 50px;
            height: 50px;

            background-image: url("~_assets/images/logo_blog2.png");
            background-size: cover;
            background-position: center center;
        }

        &__items {
            display: flex;
            align-content: center;

            li {
                color: $color-white--base;
                text-transform: uppercase;

                border-right: 1px solid $color-white--base;
                padding: 0 10px;

                a {
                    color: $color-white--base;
                }

            }

            li:last-of-type {
                border: none;
                padding-right: none;
            }
        }
    }
</style>
