<template>
  <img src="{{url_image}}" alt="{{description}}" id="{{id}}">
</template>

<script>
export default {
  name: 'Image',
  props: {
    url_image:{
        type: String,
        default: "No_image"},
    description:{
        type: String,
        default: "No_description"},
    
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

</style>