<template>
  <a-scene>
    <a-assets>
      <img id="brick" src="../assets/images/brick.jpg" />
      <img src="../assets/images/white_brick.jpg" id="brick_white" />
    </a-assets>
    <a-box
      src="#brick"
      color="#ffffff"
      position="-1 2 -6"
      scale="-1 1 1"
      rotation="0 0 0"
      repeat="1 1"
      roughness="1"
      normal-map="#brick_white"
      normal-texture-repeat="1 1"
      width="4"
      depth="4"
      height="4"
    ></a-box>
    <a-box
      src="#brick_white"
      position="1 2 -3"
      scale="2 1 2"
      rotation="0 0 0"
      repeat="1 1"
    ></a-box>
  </a-scene>
</template>
