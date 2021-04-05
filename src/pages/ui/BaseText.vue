<template>
  <div class="gray-text">
    <p><slot></slot></p>
  </div>
  <div class="white-text">
    <p><slot></slot></p>
  </div>
  <div class="black-text">
    <p><slot></slot></p>
  </div>
  <div class="large-title">
    <p><slot></slot></p>
  </div>
  <div class="med-title">
    <p><slot></slot></p>
  </div>
</template>

<script>
export default {
  props: {
    mode: {
      type: String,
      required: false,
      default: null
    },
  }
}
  </script>

  <style scoped>
  .gray-text {
  font-family: Open Sans, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 28px;
  width: 272px;
  color: #5A7184;
  }
  .white-text {
  font-family: Open Sans, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 28px;
  width: 272px;
  
  color: white;
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
  font-family: HK Grotesk, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.2px;

  color: #183b56;
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