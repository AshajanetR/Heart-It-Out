<template>
  <nav class="navbar bg shadow-lg custom-shadow">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="https://s3-alpha-sig.figma.com/img/ab0e/2d02/66f8fcfdf227ae5bea57d3d98a8f7e49?Expires=1733097600&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=mg0FvOwZW1O46OclDOX8rkS-4384utpwJsEbWC~f9mRvIiHtQDUQwaNK4jIsACL3-Vq~YjpMcqO1pdS1takrSGtstx4iCe4yroh7S9Vb6MbDrbdcc-vYTKQ5D7MtLZ3pX6IsAhU7qEZUe~3b-jkSLcdqGpdrAZZzUn8WZQByrRCFm97Ow2rYarP26TkbD43iqnXUFS7BfsIXTTLpACumjZiy0OISGwAs96PiZ3FPD~ClUFPLNmp9DkR3PtzSIsJv1osvb3IceB40XAy3bYjTDI-A4V25ywu6UUtrBslcldvdXwW9D-WSGhEGoGbzV~SgDFlW~L5Wbar20jUdpV1QIw__" 
      alt="Bootstrap" class="custom-logo">
    </a>
  </div>
</nav>
</template>

<style scoped>
.bg{
  position:absolute;
  background:#FFFFFF ;
  width: 1152px;
  height:60px;
}
.custom-shadow{
box-shadow: 2px 4px 8px 0 #00000040;
}
.custom-logo{
  width: 97px;
  height: 44.92px;
  position: absolute;
  top: 8px;
  left: 513px;
}

@media screen and (max-width: 375px) {
  .bg {
    width: 100%;
    height: 60px;
    position: relative;
  }
  .custom-logo {
    width: 80px;
    height: auto;
    position: absolute;
    top: 8px;
    left: 10px;
  }
}
</style>
