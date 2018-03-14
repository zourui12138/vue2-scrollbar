<template>
    <div id="app">
        <vue-scrollbar classes="my-scrollbar" ref="Scrollbar">
            <div class="scroll-me">
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
                <div class="kolom"></div>
            </div>
        </vue-scrollbar>
    </div>
</template>

<script>
    import VueScrollbar from 'vue2-scrollbar';
    import 'vue2-scrollbar/dist/style/vue2-scrollbar.css'
    export default {
        name: 'App',
        components: { VueScrollbar }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        height: 500px;
    }
    /*The Wrapper*/
    .my-scrollbar{
        width: 50%;
        height: calc(100%);
        overflow: hidden;
    }
    .kolom{
        height: 100px;
        background-color: #ff0;
    }
    .kolom:nth-child(odd){
        background-color: #e4393c;
    }
</style>
