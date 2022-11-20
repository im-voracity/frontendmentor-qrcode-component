<template>
  <div class="card">
    <img class="qr-code" :src="require('../assets/image-qr-code.png')" alt="QR Code for Frontend Mentor" />
    <h1 class="heading">Improve your front-end skills by building projects</h1>
    <p class="description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</template>

<script>
export default {
  name: "QrCodeCard"
};
</script>

<style scoped>
  .card {
    background-color: white;
    width: 320px;
    height: 497px;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    border-radius: 20px;
    box-shadow: 0 25px 25px rgba(0, 0, 0, 0.0476518);
    padding: 16px 16px 40px 16px;
  }

  .qr-code {
    max-width: 288px;
    max-height: 288px;
    border-radius: 10px;
    margin-bottom: 24px;
  }

  .heading {
    font-family: 'Outfit', sans-serif;
    font-size: 22px;
    font-weight: 700;
    line-height: 28px;
    text-align: center;
    margin-bottom: 16px;
    color: hsla(217, 44%, 22%, 1);
    max-width: 288px;
  }

  .description {
    font-family: 'Outfit', sans-serif;
    font-size: 15px;
    font-weight: 500;
    line-height: 19px;
    text-align: center;
    letter-spacing: 0.1875px;
    color: hsla(219, 15%, 55%, 1);
    max-width: 256px;
  }
</style>