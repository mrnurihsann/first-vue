<template>
  <div class="first-wrapper">
    <h2 class="title-header">HelloWorld</h2>
    <div class="first-item">
     <img class="logo" alt="Nasa" src="../assets/nasa.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Google" src="../assets/google.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Motorola" src="../assets/motorola.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="React" src="../assets/react.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Skype" src="../assets/skype.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Windows" src="../assets/windows.png">
    </div>
     <div class="first-item">
     <img class="logo" alt="Google" src="../assets/google.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Motorola" src="../assets/motorola.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="React" src="../assets/react.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Skype" src="../assets/skype.png">
    </div>
    <div class="first-item">
     <img class="logo" alt="Windows" src="../assets/windows.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'FirstComponent',
  
};
</script>

<style scoped>
.title-header {
  margin-bottom: 100px;
  text-align: left;
}

.first-wrapper  {
  width: 60%;
  overflow: hidden;
  margin: auto;
}

.first-item {
  float: left;
  margin-right: 70px;
  margin-bottom: 70px;
  width: 150px;
  height: 150px;
}

.first-item .logo {
  width: 165px;
  height: 150px;
}
</style>
