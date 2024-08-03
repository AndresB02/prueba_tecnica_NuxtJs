<template>
  <div class="video-container">
    <video controls>
      <source
        src="https://www.youtube.com/watch?v=IaJjk0vvnB8&t=1s"
        type="video/mp4"
      />
      Your browser does not support the video tag.
    </video>
  </div>
</template>

<script setup></script>

<style scoped>
.video-container {
  padding-top: 50px;
  width: 100%;
}

video {
  width: 100%;
  height: auto;
}
</style>
