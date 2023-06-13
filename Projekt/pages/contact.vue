<template>
  <div class="contact">
    <h1 class="title">Skontaktuj się z nami</h1>
    <div class="form">
      <slot></slot>
      <Button @click="handleButtonClick">Wyślij</Button>
    </div>
  </div>
</template>

<script>
import Button from '~/components/Button.vue';

export default {
  components: {
    Button,
  },
  methods: {
    handleButtonClick() {
      console.log('Kliknięto przycisk');
    },
  },
};
</script>

<style scoped>
.contact {
  max-width: 600px;
  margin: 0 auto;
  padding: 40px;
  background-color: #f8f8f8;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.title {
  font-size: 36px;
  color: #333;
  text-align: center;
  margin-bottom: 20px;
}

.form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

Button {
  background-color: #3aa70f;
  color: #05f8a7;
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
}
</style>



