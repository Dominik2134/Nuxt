<template>
  <div class="welcome-page" :style="{ backgroundColor: backgroundColor }">
    <div class="welcome-header">
      <h1>Witaj w naszej firmie żywnościowej</h1>
      <p class="description" :style="{ color: textColor }">Smakowite i zdrowe jedzenie dla wszystkich</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
_backgroundColor: '#006400', 
get backgroundColor() {
return this._backgroundColor;
},
set backgroundColor(value) {
this._backgroundColor = value;
},
      textColor: '#ff0000' 
    };
  }
};
</script>

<style scoped>
.welcome-page {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.welcome-header {
  text-align: center;
  margin-bottom: 2rem;
}

.welcome-header h1 {
  font-size: 2.5rem;
  font-weight: bold;
}

.description {
  font-size: 1.5rem;
}
</style>
