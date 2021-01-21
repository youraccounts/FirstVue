<template>
  <div><h1>Seakthong.Queen.JS</h1></div>
  <div>
    <h3>Start On : {{ msg }}</h3>
  </div>
</template>

<script>
export default {
  name: "SQ",
  props: {
    msg: String,
  },
};
</script>