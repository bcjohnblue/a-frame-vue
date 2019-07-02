<template>
  <a-scene>
    <a-assets>
      <img src="../assets/images/floor.jpg" id="floor" />
      <img src="../assets/images/floor1.jpg" id="floor1" />
    </a-assets>
    <a-plane
      material="src: #floor; repeat: 5 5; normal-map: #floor1; normal-texture-repeat: 5 5"
      position="-1 1 -5"
      scale="10 10 1"
      rotation="-90 0 0"
    ></a-plane>
  </a-scene>
</template>
