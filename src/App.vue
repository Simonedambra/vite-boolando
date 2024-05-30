<script>
import headercomponets from './components/HeaderComponents.vue';
import maincomponents from './components/MainComponents.vue';

export default {
  name:'myapp',
  data() {
    return {}
  },
  components: {
    headercomponets,
    maincomponents,
  }
}

</script>
<template>


    <!-- inizio header -->
    <headercomponets/>
    <!-- fine header -->
    <!-- inizio main -->
    <maincomponents/>
    <!-- fine main -->




</template>
<style lang="scss">
* {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
  }
  
  /* classi base */
  .row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    height: 100%;
    width: 100%;
  
  }
  
  body {
    font-family: Arial, sans-serif;
  }
  
  .container {
    display: flex;
    flex-wrap: wrap;
    margin: 100px 0px;
    height: 1250px;
    width: 1200px;
  
  }
  
  .col-33 {
    position: relative;
    margin: 10px 0px;
    width: calc(100%/3);
    height: calc(100%/2);
    padding: 0px 0px 60px 0px;
  
  }
  
  /* inizio header */
  header {
    position: fixed;
    top: 0px;
    left: 0;
    right: 0;
    height: 50px;
    z-index: 1;
  }
  
  .container-header {
  
    height: 100%;
    width: 1400px;
  
  
  }
  
  .header-box {
    display: flex;
    flex-direction: row;
    height: 100%;
    width: 100%;
    background-color: rgb(255, 111, 0);
  }
  
  .col-30 {
    height: 100%;
    width: calc(100%/4);
    background-color: rgb(255, 111, 0);
    color: white;
  }
  
  .header-list {
    list-style: none;
    margin: 0px 15px;
  }
  
  li {
    list-style: none;
    margin: 3px;
  }
  
  .col-40 {
    position: relative;
    height: 100%;
    width: calc(100%/4*2);
  
  
  }
  
  .logo {
    height: 30px;
    width: 100px;
    background-size: contain;
    background-repeat: no-repeat;
    background-image: url(./components/img/boolean-logo.png);
  
  }
  
  /* fine header */
  
  
  /* inizio main */
  
  /* sconti */
  .labels {
    position: absolute;
    bottom: 90px;
    left: 0;
  
  }
  
  .sales1 {
    display: inline-block;
    background-color: red;
    color: white;
    padding: 5px 10px;
    bottom: 90px;
  
  }
  
  .sales {
    display: inline-block;
    background-color: green;
    color: white;
    padding: 5px 10px;
  
  }
  
  .sales2 {
    display: inline-block;
    background-color: green;
    color: white;
    padding: 5px 10px;
  
  
  }
  
  .bg-red {
    color: red;
  }
  
  .bar {
    text-decoration: line-through;
    margin: 0px 5px;
    color: rgb(34, 33, 33);
  }
  
  /* fine sconti */
  /* heart */
  .heart {
    position: absolute;
    right: 5px;
    top: 10px;
    background-color: white;
    padding: 10px;
  
  }
  
  .heart:hover {
    position: absolute;
    right: 5px;
    top: 10px;
    background-color: white;
    padding: 10px;
    color: red;
  
  }
  
  /* fine heart */
  
  /* inizio classi img */
  .image1 {
    background-image: url(./components/img/1.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image2 {
    background-image: url(./components/img/2.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image3 {
    background-image: url(./components/img/3.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image4 {
    background-image: url(./components/img/4.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image5 {
    background-image: url(./components/img/5.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image6 {
    background-image: url(./components/img/6.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  /* fine classi img */
  /* inizio classi img hover */
  .image1:hover {
    background-image: url(./components/img/1b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image2:hover {
    background-image: url(./components/img/2b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image3:hover {
    background-image: url(./components/img/3b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image4:hover {
    background-image: url(./components/img/4b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image5:hover {
    background-image: url(./components/img/5b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  .image6:hover {
    background-image: url(./components/img/6b.webp);
    background-size: contain;
    background-repeat: no-repeat;
    height: 100%;
    width: 100%;
  }
  
  /* fine classi hoverk */

</style>