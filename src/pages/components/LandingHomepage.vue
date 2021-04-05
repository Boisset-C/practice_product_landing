<template>
  <section class="homepage">
    <div class="header">
      <base-header></base-header>
    </div>

    <div class="title">
      <p>Powerful <br />analytics tools for your  business</p>
    </div>

    <div class="text">
      <p>An awesome and powerful tool for your business, increase business revenue with enterprise-grade links built to acquire and engage customers.</p>
    </div>
   
    <div class="get-started-btn">
      <base-button mode="outline">Get Started</base-button>
    </div> 
    
    <div class="watch-demo-btn">
      <base-button mode="flat">Watch Demo</base-button>
    </div>
    
    <div class="macbook">
      <img :src="require(`@/assets/homepage-images/macbook-image.png`)"/>
    </div>
  </section>
</template>


<script>
  import BaseButton from '../ui/BaseButton.vue';
  import BaseHeader from '../ui/BaseHeader.vue';

export default {
 components: {
  BaseHeader,
  BaseButton,
  },
};
</script>

<style scoped>
.homepage {
  display: grid;
 
  background-color: #1565d8;
  
}

</style>