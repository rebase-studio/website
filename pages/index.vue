<template>
  <section class="container">
    <div class="center-container">
      <img src="~/assets/logo.svg" alt="" class="logo">
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.center-container {
  text-align: center;
  height: 100vh;
  min-height: 300px;
  position: relative;
  width: 100%;
}

.logo {
  position: absolute;
  left: 50%;
  margin-left: -415px;
  top: 50%;
  height: 230px;
  margin-top: -150px;
  max-width: 100%;
  padding: 0 20px;
}

@media screen and (max-width: 830px) {
  .logo {
    margin-left: -50%;
  }
}
</style>
