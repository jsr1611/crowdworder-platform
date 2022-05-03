<template>
<div class="row m-auto">
    <div class="col-3 image-block" v-for="(item, index) in list_items" :key="index">
        <h4> {{item}} </h4>
    </div>
</div>
</template>

<script>
export default {
  name: 'ImageCompo',
  props:{
      list_items: Object,
  },
}
</script>

<style scoped>
h4 {
 font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
 font-size: 24px;
}
.image-block{
    width: 300px;
    height: 300px;
    border: solid 1px;
    border-color: black;
    margin: 10px;
    align-content: center;
    position: relative;
    
    
}

</style>