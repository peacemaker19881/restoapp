<template>
    <img src="../assets/download.jpg"/>
<h1>Welcome on sign up form</h1>
<div class="register">
    <input type="text" placeholder="Enter your name"/><br><br>
    <input type="text" placeholder="Enter your name"/><br><br>
    <input type="password" placeholder="Enter your password"/><br><br>
    <button>Sign up</button>
</div>
</template>

<script>
export default{
    name:'signup_component',
    components:{}
}
</script>
<style>
.register input{
width: 300px;
height: 40px;
padding-left: 20px;
display: block;
margin-bottom: 30px;
margin-right: auto;
margin-left: auto;
border: 1px solid skyblue;
}
</style>
