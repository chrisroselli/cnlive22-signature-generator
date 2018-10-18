<template>
<svg xmlns="http://www.w3.org/2000/svg"
    :width="width"
    viewBox="0 0 391 65"
    :aria-labelledby="iconName"
    role="presentation"
  >
  <title :id="iconName" lang="en">{{iconName}} icon</title>
      <slot/>
</svg> 
</template>

<script>
export default {
  props: {
    iconName: {
      type: String,
      default: 'logo'
    },
    width: {
      type: [Number, String],
      default: 350
    }
  }
}
</script>


<style scoped>
svg {
  display: inline-block;
  vertical-align: baseline;
  margin-top: 20px; /* yes, I'm that particular about formatting */
}
</style>