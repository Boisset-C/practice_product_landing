<template>
  <section class="homepage">
    <header>
      <base-header></base-header>
    </header>

    <h2>POWERFUL ANALYTICS TOOLS FOR YOUR BUSINESS</h2>

    <p>
      An awesome and powerful tool for your business, increase business revenue
      with enterprise-grade links built to acquire and engage customers.
    </p>

    <label id="top-btn">
      <base-button mode="outline">Get Started</base-button>
    </label>

    <label id="bottom-btn">
      <base-button mode="flat">Watch Demo</base-button>
    </label>

    <div class="macbook">
      <img :src="require(`@/assets/homepage-images/macbook-image.png`)" />
    </div>
  </section>
</template>

<script>
import BaseButton from "../ui/BaseButton.vue";
import BaseHeader from "../ui/BaseHeader.vue";

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

h2 {
  font-family: HK Grotesk;
  font-style: normal;
  font-weight: bold;
  font-size: 32px;
  line-height: 40px;
  /* or 125% */

  text-align: center;
  letter-spacing: 0.2px;

  color: #ffffff;

  opacity: 0.12;
}
p {
  font-family: Open Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 28px;
  /* or 175% */

  text-align: center;

  color: #fafafb;
}

#top-btn {
  margin-left: 60px;
}
#bottom-btn {
  margin-top: 10px;
  margin-left: 60px;
}
</style>
