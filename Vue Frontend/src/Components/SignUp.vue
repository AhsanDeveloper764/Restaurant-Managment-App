<template>
    <div class="main" >
        <img src="../Assets/logo.jpg" alt="img-logo" class="img-logo" >
        <h1 class="text-signUp">Sign Up Page</h1>
    </div>
</template>

<script >
    export default {
        name:"SignUp"
    }
</script>

<style scoped>
    .main{
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;
        width: 100%;
        line-height: 0px;
        margin: 0 auto;
    }
    .img-logo{
        width: 10%;
    }
    .text-signUp{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-size: 30px;
    }
</style>