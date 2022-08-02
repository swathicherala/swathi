<template>
  <v-container>
    <div class="component-profile d-flex flex-column justify-center align-center">
       <img src="../assets/lady.jpg" />
       <h1>
         {{name}}
       </h1>
       <p>
        {{description}}
       </p>
       <div class="d-flex">
        <a href="https://stackoverflow.com/" target="_blank" title="Stack Overflow"><i class="fab fa-stack-overflow mx-2"></i></a>
        <a href="https://www.linkedin.com/company/linkedin" target="_blank" title="LinkedIn"><i class="fab fa-linkedin mx-2"></i></a>
        <a href="https://mail.google.com/" target="_blank" title="Email"><i class="far fa-envelope mx-2"></i></a>
       </div>
    </div>
  </v-container>
</template>

<script>
export default {
   data(){
       return{
        name:"Swathi",
        description:"I am a Fullstack Developer"
       }
   }
}
</script>

<style scoped lang="scss">
.component-profile{
height: 100vh;
}
img{
    height:100px;
    border-radius: 230px;
}
i{
    font-size: 24px;
    color:orange;
}
</style>