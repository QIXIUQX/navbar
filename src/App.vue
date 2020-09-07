<template>
    <div id="app">
        <!--    template -->
        <div class="home-nav">
            <NavBar>
                <div slot="center">首页</div>
            </NavBar>
        </div>
    </div>
</template>
<script>
    import NavBar from "./components/navbar/NavBar";

    export default {
        name: '',
        components: {
            NavBar
        }
    }
</script>
<style>
    @import "./assets/css/common/common.css";

    .home-nav {
        background-color: pink;
        color: white;
    }
</style>
