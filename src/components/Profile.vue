<script setup lang="ts"></script>

<template>
  <div class="profile">
    <img src="../assets/dog-image.jpg" />

    <div class="description">
      <h1>Seu nome</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed iaculis placerat elit ut
        scelerisque. Vivamus semper porta felis vitae tempus. Pellentesque habitant morbi tristique
        senectus et netus et malesuada fames ac turpis egestas. Nulla ante arcu, varius vel
        hendrerit consectetur, dictum vel justo. Nunc commodo consectetur mollis.
      </p>
    </div>
  </div>
</template>

<style scoped>
.profile {
  display: flex;
  flex-direction: row;
  justify-content: center;

  padding: 16px;
}

.description {
  margin-left: 16px;
  width: 40%;
  color: white;
}

@media only screen and (max-width: 992px) {
  .description {
    width: 60%;
  }
}

img {
  height: 100px;
  width: auto;
  border-radius: 50%;
}
</style>
