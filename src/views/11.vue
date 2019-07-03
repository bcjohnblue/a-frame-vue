<template>
  <a-scene>
    <a-assets>
      <img src="../assets/images/floor.jpg" id="floor" />
      <img src="../assets/images/floor1.jpg" id="floor1" />
      <img src="../assets/images/panorama.jpg" id="panorama" />
      <img src="../assets/images/room.jpg" id="room" />
      <img src="../assets/images/kitchen.jpg" id="kitchen" />
      <img id="sky" src="../assets/images/clear-sunny-sky.jpg" />
      <a-asset-item
        id="village"
        src="../assets/castle_village_scene/scene.gltf"
        crossorigin="anonymous"
      />
      <!-- <a-asset-item
        id="village"
        src="../assets/castle_village_scene/scene.gltf"
      ></a-asset-item>-->
    </a-assets>
    <a-sky src="#sky" rotation="-60 0 0"></a-sky>
    <!-- <a-gltf-model
      src="../assets/castle_village_scene/scene.gltf"
    ></a-gltf-model>-->
    <a-entity
      gltf-model-next="../assets/castle_village_scene/scene.gltf"
    ></a-entity>
    <!-- <a-plane
      material="src: #floor; repeat: 500 500;"
      scale="1000 1000 1"
      rotation="-90 0 0"
    ></a-plane>-->
  </a-scene>
</template>

<script>
export default {
  data() {
    return {
      // src: require("../assets/scene.gltf")
    };
  }
};
</script>
