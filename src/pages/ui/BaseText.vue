<template>
  <button v-if="!link" :class="mode">
    <slot></slot>
  </button>

  <router-link v-else :class="mode">
    <slot></slot>
  </router-link>
</template>

<script>
export default {
  props: {
    mode: {
      type: String,
      required: false,
      default: null,
    },
  },
};
</script>

<style scoped>
.gray-text {
  font-family: Open Sans, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 28px;
  width: 272px;
  color: #5a7184;
}
.white-text {
  font-family: Open Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 28px;
  /* or 175% */
  text-align: center;
  color: #fafafb;
}
.black-text {
  font-family: Open Sans, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 28px;
  width: 272px;

  color: black;
}
.large-title {
  font-family: HK Grotesk;
  font-style: normal;
  font-weight: bold;
  font-size: 32px;
  line-height: 40px;
  /* or 125% */

  text-align: center;
  letter-spacing: 0.2px;

  color: #ffffff;

  opacity: 0.32;
}
.med-title {
  font-family: HK Grotesk, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.2px;

  color: #183b56;
}
</style>
