<template>
  <div id="ceremonie" class="container">
    <h3>donderdag 9 mei</h3>
    <h1 class="event-title">13:30</h1>
    <h1 class="event-title" style="margin-bottom: 0.5rem;">CEREMONIE</h1>
    <div class="section">
      <h1 class="section-title">LOCATIE</h1>
      <p class="subtitle">Sint-Lambertuskapel</p>
    <a target="_blank" href="https://maps.app.goo.gl/kZbFhXgs8tvMypBF9">Kasteelpark Arenberg 29, 3001 Leuven</a>
      <Location class="location" address="Mechelsestraat 202, 3000 Leuven" location="Abdij Keizersberg" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2518.291939083328!2d4.685161976848573!3d50.86279485758849!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c1613d8ed7e757%3A0xb5010ffd979d8914!2sKasteelpark%20Arenberg%2029%2C%203001%20Leuven!5e0!3m2!1snl!2sbe!4v1709498511999!5m2!1snl!2sbe"></Location>    
    </div>
  </div>
</template>
<script>
/* eslint-disable vue/multi-word-component-names */
import Location from './Location.vue';

export default {
  name: 'BurgerlijkeInfo',
  components: {
    Location
  },
  props: {},
  data() {
    return {

    }
  },
  watch: {

  },
  computed: {

  }
}
</script>

<style scoped>
h1 {
  text-align: start;
  font-weight: 900;
  font-size: 2rem;
  text-align: center;
}

h2 {
  
}

h3 {
  font-size: 2.5rem;
}

.event-title {
  font-size: 1.5rem;
}

.section-title {
  font-size: 1rem;
  margin-bottom: 0.5rem;
}
.container {
  box-sizing: border-box;
  overflow-y: auto;
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  justify-content: center;
  padding: 3rem 2rem 3rem 2rem;
  background-color: #ebebeb;
  color: #39393A !important;
}

a {
  color: #39393A !important;
  font-weight: bold;
}

.subtitle {
  font-size: 1rem;
}


.section {
  margin: 1.5rem 0 0 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 50%;
  align-self: center;

  h2 {
    align-self: center;
    text-align: center;
    border-bottom:  1px solid #F0EFE4;
    font-weight: normal;
  }
  
}

.location {
  align-self: center;
}

@media only screen and (max-width: 600px) {
  .section {
    width: 100%;

    h2 {
      width: 100%;
    }
  }
}
</style>
