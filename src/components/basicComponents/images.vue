<template>
  <img :src="src" :alt="alt" :id="id">
</template>

<script>
export default {
  name: 'Image',
  props: {
    src:{
        type: String,
        default: "No_image"},
    alt:{
        type: String,
        default: "No_alt"},
    
    id:{
        type: String,
        default: "No_id"}
    
  },
  data() {
    return {
      nav:true,
      mobileView:false,
    }
  }

}
</script>

<style>
img{
    width: 100%;
    height: 100px;
}

</style>