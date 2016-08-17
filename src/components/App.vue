<template>
    <div id="main">
        Hello, Vue DevFlow
    </div>

    <!-- main view -->
    <router-view
            class="view"
            keep-alive
            transition
            transition-mode="out-in">
    </router-view>
</template>


<style>
    #main {
        margin: 15px 0 auto;
        text-align: center;
        font-size: 19px;
    }

</style>
