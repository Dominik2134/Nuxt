<template>
    <div class="about">
      <h1 class="title">O nas</h1>
      <p class="description">{{ aboutText }}</p>
      <Button @click="handleButtonClick">Kliknij mnie</Button>
    </div>
  </template>
  
  <script>
  import Button from '~/components/Button.vue';
  
  export default {
    components: {
      Button,
    },
    data() {
      return {
        aboutText: 'Jesteśmy firmą zajmującą się...',
      };
    },
    methods: {
      handleButtonClick() {
        console.log('Kliknięto przycisk');
      },
    },
  };
  </script>
  
  <style scoped>
  .about {
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
  
  .description {
    font-size: 18px;
    color: #555;
    line-height: 1.5;
    margin-bottom: 20px;
  }
  
  </style>
  <template>
    <div class="about">
      <h1 class="title">O nas</h1>
      <p class="description">{{ aboutText }}</p>
      <Button @click="handleButtonClick">Kliknij mnie</Button>
    </div>
  </template>
  
  <script>
  import Button from '~/components/Button.vue';
  
  export default {
    components: {
      Button,
    },
    data() {
      return {
        aboutText: 'Jesteśmy firmą zajmującą się...',
      };
    },
    methods: {
      handleButtonClick() {
        console.log('Kliknięto przycisk');
      },
    },
  };
  </script>
  
  <style scoped>
  .about {
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
  
  .description {
    font-size: 18px;
    color: #555;
    line-height: 1.5;
    margin-bottom: 20px;
  }
  
  Button {
    background-color: #ff9800;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
  }
  </style>
  <template>
    <div class="about">
      <h1 class="title">O nas</h1>
      <p class="description">{{ aboutText }}</p>
      <Button @click="handleButtonClick">Kliknij mnie</Button>
    </div>
  </template>
  
  <script>
  import Button from '~/components/Button.vue';
  
  export default {
    components: {
      Button,
    },
    data() {
      return {
        aboutText: 'Jesteśmy firmą zajmującą się dostarczaniem świeżej i zdrowej żywności. Nasze produkty są starannie wyselekcjonowane z najlepszych lokalnych farm, aby zapewnić naszym klientom najwyższą jakość. Dbamy o to, aby nasza żywność była bogata w składniki odżywcze i dostępna w atrakcyjnych cenach. Nasza pasja do zdrowego odżywiania motywuje nas do tworzenia smacznych i wartościowych dań, które zaspokoją Twoje podniebienie i zapewnią Ci pełnowartościowy posiłek. Zapraszamy do skorzystania z naszej oferty i dołączenia do naszej społeczności miłośników zdrowej żywności!',
      };
    },
    methods: {
      handleButtonClick() {
        console.log('Kliknięto przycisk');
      },
    },
  };
  </script>
  
  <style scoped>
  .about {
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
  
  .description {
    font-size: 18px;
    color: #555;
    line-height: 1.5;
    margin-bottom: 20px;
  }
  
  Button {
    background-color: #ff9800;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
  }
  </style>