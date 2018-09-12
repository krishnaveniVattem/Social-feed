<template>
  <div id="icon_container">
   <i id="icon" :class=iconname></i>
    <p id="icon_status">{{status}}</p>

  </div>
</template>

<script>
export default {
  name:"icon",

  data () {
    return {
         iconname:'',
         status:'',
    }
  },
  props:[
    'iconname',
    'status'
  ],  
}
</script>

<style>
#icon_container{
  display:inline;
 
}
#icon{
 display:inline;
 float:left;

}
 
#icon_status{
  float:left;
  display:inline;
  padding-left:10px;
 padding-bottom:50px;
margin:0px 2px 1px 1px;
  
}
</style>
