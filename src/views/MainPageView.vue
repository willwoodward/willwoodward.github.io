<template>
    <!-- <iframe id="if" src="https://my.spline.design/dodecahedroncopy-f6c664c96856f2c6d7f014c637ca7417/" frameborder="0" width="100%" height="1200px"></iframe> -->
    <!-- <Landing />
    <iframe id="if" src="https://my.spline.design/dodecahedron-87904bfc4121e2327f5353967829383a/" frameborder="0" width="100%" height="700px"></iframe>
    <Image3D />
    <Services /> -->
    <EmptySpace />
</template>

<style>
    #if {
        position: relative;
        top: -200px;
    }
</style>

<script>
import Landing from "../components/Landing.vue";
import Image3D from "../components/Image3D.vue";
import EmptySpace from "../components/EmptySpace.vue";
import Services from "../components/Services.vue";

    export default {
    name: "MainPageView",
    components: { Landing, EmptySpace, Services }
}
</script>