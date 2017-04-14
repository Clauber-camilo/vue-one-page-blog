<template>
    <div id="app">
        <main-header></main-header>
        <router-view></router-view>
        <main-footer></main-footer>
    </div>
</template>

<script>
    import MainHeader from './components/layout/header';
    import MainFooter from './components/layout/footer';

    export default {
        name: 'app',
        data() {
            return {};
        },
        components: {
            MainHeader,
            MainFooter
        }
    };

</script>

<style lang="scss">

    // @import './assets/sass/reset';
    // @import './assets/sass/config/vars';

    @import '~_sass/main';

    #app {
        font-family: $font-default;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        // color: #2c3e50;
    }
</style>
