<template>
<h4>hello</h4>
<canvas>
</canvas>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { BasicScene } from "@/BabylonExamples/BasicScene";
export default defineComponent({
name: "BabylonExamples",
mounted() {
const canvas = document.querySelector("canvas")!;
new BasicScene(canvas);
},
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body{
width: 100%;
height: 100%;
margin: 0;
}
canvas {
width: 100%;
height: 100%;
}
</style>
