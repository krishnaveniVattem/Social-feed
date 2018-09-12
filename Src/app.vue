<template>
<div class=center>
            <div class = "nav" >
              <icon iconname="fa fa-thumbs-up" status="status"/>
              <icon iconname="fa fa-camera-retro" status="Photo/Video"/>
              <profilepic class="right"></profilepic>
            </div>

               <div class= second>
                 <profilepic ></profilepic>
                 <comment></comment>
               </div>

                    <div>
                     <profilepic></profilepic>                 
                     <temp></temp>
                    </div>

                 <div>
                    <mainpic></mainpic>
                  </div>

                 <div class=footer1>
                     <footer1></footer1>
                    <profilepic class= f1></profilepic>
                 </div>

            <div>
             <footer2></footer2>
            </div>

                            <div>
                                 <profilepic class="left"></profilepic>  
                                <comment></comment>                                                        
                               <icon iconname="fa fa-camera-retro" />
                                <i class="material-icons"></i>
                            </div>
    </div>
</template>

<script>
import  comment from './comments.vue';
import  icon from './navicons.vue';
import  profilepic from './profileimg.vue';
import  temp from './text.vue';
import  tem from './text2.vue';
import  mainpic from './bodyimg.vue';
import  footer1 from './footer1.vue';
import  footer2 from './footer2.vue';

export default {
  components:{
comment,icon,profilepic,temp,tem,mainpic,footer1,footer2
},
}
</script>

<style>
.nav{
border:1px solid black;
display:inline-block;
width:100%;
height:50px;
padding:10px ;
background-color: ;
}
.second{
height:50px;
display:inline-block;
background-color:#f2f2f2;
display:inline;
}
.left{
    float:left;
padding:0px;
}
.right{
    float:right;
  padding:0px;
}

.small{
    float:right;

  
}
.footer1{
background-color:#f2f2f2;
overflow:hidden;
}
.center{
    width:80%;
    margin:auto;
}
.f1{
float:right;
}
</style>

