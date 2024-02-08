<template>
    <div class="contenitore">
      <figure>
        <img :src="propssrc" :alt="propsSeries"/>
      </figure>
      <h4>{{ propsSeries }}</h4>
    </div>
  </template>
  
  <script>
  export default {
    name: "PropsSlides",
    props: {
      propssrc: String,
      propsSeries: String
    }
  }
  </script>
  
  <style scoped lang="scss">

  .contenitore{
    flex-basis: calc( 100% / 6 - 20px);
    padding: 10px;
    h4{
            color: white;
        }
    
    figure{
        img{
            width: 100%;
            display: block; 
            aspect-ratio: 1;   
            }
    }
  }
  </style>