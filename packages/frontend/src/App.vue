<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <div id="app">
    <div class="welcome">VOROMADE VUE x VITE x ELECTRON BOILERPLATE</div>
  </div>
</template>

<style>
@font-face {
  font-family: "Bahnschrift";
  src: url("./assets/fonts/BAHNSCHRIFT.TTF");
}

:root {
  --pearson-dark: #19182d;
  --pearson-purpp: #6753fd;
  --pearson-orange: #ff5c5c;
  --pearson-blue: #2a87fd;
  --pearson-black: #17172c;
  --pearson-gray: #434354;
  --pearson-dark2: #1b1b35;
  --matte-black: #181926;
  --pearson-light-gray: #222336;
  --solana-purple: #9945ff;
  --solana-green: #14f195;
  --matte-black-alt: #131420;
}

html,
body {
  height: 100%;
  overflow: hidden;
  scroll-behavior: smooth;
}

body {
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 8px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Bahnschrift";
  text-overflow: ellipsis;
  white-space: nowrap;
  scroll-behavior: smooth;
}

#app {
  color: #fff;
  background: var(--matte-black);
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.welcome {
  display: flex;
  align-items: center;
  color: #fff;
  margin-top: 3%;
  font-weight: 600;
  font-size: 1.7rem;
}
</style>
