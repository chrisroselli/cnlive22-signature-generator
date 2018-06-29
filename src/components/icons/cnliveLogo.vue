<template>
<g>
<g :fill="iconColorOne">
  <path class="cn-orange" d="M24.1,59.8c-3.1,0-5.8-0.3-8-1c-2.2-0.7-4-1.6-5.4-2.8c-1.4-1.2-2.4-2.6-3-4.2c-0.6-1.6-0.9-3.4-0.9-5.4V17.7
      c0-2,0.3-3.8,0.9-5.4c0.6-1.6,1.6-3,3-4.2C12,6.9,13.8,6,16,5.3s4.9-1,8-1h44.7v8.2H24.1c-4.6,0-6.9,1.7-6.9,5.1v28.8
      c0,3.4,2.3,5.1,6.9,5.1h44.7v8.2H24.1z"></path>
  <path class="cn-orange" d="M145.8,59.8L86.7,16.6v43.2h-9.1V4.3h9.1l55.2,41.2V4.3h9.1v55.4H145.8z"></path>
</g>
<g :fill="iconColorTwo">
    <path class="cn-white" d="M161.2,59.8V4.3h10.6v47.3h45v8.2H161.2z"></path>
    <path class="cn-white" d="M224.4,59.8V4.3h10.5v55.4H224.4z"></path>
    <path class="cn-white" d="M277.2,59.8L240.4,4.3h11.9l29,44.7l28.7-44.7h11.6l-36.6,55.4H277.2z"></path>
    <path class="cn-white" d="M326.6,59.8V4.3h57v8.2h-46.5v13.9h44.2v8.2h-44.2v17h46.5v8.2H326.6z"></path>
  </g>
</g>
</template>
<script>
export default {
  props: {
    iconColorOne: {
      type: String,
      default: '#FF7F30'
    },
    iconColorTwo: {
      type: String,
      default: '#FFF'
    }
  }
}
</script>