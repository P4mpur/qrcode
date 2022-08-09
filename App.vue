<template>
  <div id="main_div">
    <div class="window">
      <img src="qr-code-component-main\images\image-qr-code.png" class="qr_section">
      <h1 style="position: fixed; top: 540px; left: 520px;">
        Improve your front end<br> skills by bulding projects
      </h1>
      <p style="position: fixed; top:630px; left: 560px; font: sans-serif; font-size: 18px;">
        Scan the QR code to visit Frontend <br>
        Monitor and take your coding skills to<br>
        the next level
      </p>
    </div>
  </div>

</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#main_div {
  position: relative;
  height: 968px;
  width: 1440px;
  background-color: hsl(229, 61%, 85%);
}

.window {
  position: fixed;
  background-color: rgb(255, 255, 255);
  height: 60vmin;
  width: 42vmin;
  top: 190px;
  left: 480px;
  border-radius: 45px;
}

.qr_section {
  position: inherit;
  height: 330px;
  width: 350px;
  top: 220px;
  left: 508px;
  border-radius: 25px;

}
</style>
