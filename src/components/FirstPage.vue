<template>
  <div class="page">
    <div class="fullscreen">
      <video autoplay loop muted src="../assets/video.mp4"></video>
      <div class="overlay">
        <el-button class="center-button" type="primary" round>
          Trip Now!
        </el-button>
      </div>
    </div>
  </div>
</template>

<style>
.full-screen {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}

.video-background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.center-button {
  font-size: 2rem;
  padding: 1rem 2rem;
  border-radius: 1rem;
}
/* Center the button in the overlay */
.overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

</style>
