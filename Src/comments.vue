<template>

<span v-bind:title="comment">
        <!-- Create a binding between the searchString model and the text field -->

        <input type="text"  class="bar" v-model="comment" placeholder="Write a Comment...." />
 </span>   

</template>

<script>
export default {
name:'comment',
 
};
</script>
<style>
.bar{
width:80%;
}
input{
background-image:url(https://www.google.co.in/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiApqDbp7XdAhUDerwKHeSFDNAQjRx6BAgBEAU&url=https%3A%2F%2Fwww.vectorstock.com%2Froyalty-free-vector%2Fline-camera-icon-on-white-background-vector-17696448&psig=AOvVaw2Zm1rkMLMLVZg29iE-ymi0&ust=1536836355515235);
}
</style>

