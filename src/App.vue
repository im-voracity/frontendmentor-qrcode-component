<template>
  <QrCodeCard></QrCodeCard>
</template>

<script>
import QrCodeCard from "@/components/QrCodeCard";

export default {
  name: 'App',
  components: {QrCodeCard}
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
}

html {
  background-color: hsla(211, 45%, 89%, 1);
}

#app {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
