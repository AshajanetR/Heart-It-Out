<template>
  <div id="carouselExampleDark" class="carousel carousel-dark slide sec-3">
    <div class="title">
      <h2 class="t1">SECTION III [25 points]</h2>
    </div>
    <div class="carousel-indicators" style="margin-bottom: 100px;">
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="0"
        class="active btns"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="1"
        aria-label="Slide 2"
        class="btns"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="2"
        aria-label="Slide 3"
        class="btns"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="3"
        aria-label="Slide 4"
        class="btns"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="4"
        aria-label="Slide 5"
        class="btns"
      ></button>
    </div>

    <div class="carousel-inner" style="background-color: #EBF7FC; height: 812px">
      <!-- Slide 1 -->
      <div class="carousel-item active box" data-bs-interval="10000">
        <p class="title-text">Lorem Ipsum</p>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="35"
          height="35"
          fill="#455A64"
          class="bi bi-quote left"
          viewBox="0 0 16 16"
        >
          <path
            d="M12 12a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1h-1.388q0-.527.062-1.054.093-.558.31-.992t.559-.683q.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 9 7.558V11a1 1 0 0 0 1 1zm-6 0a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1H4.612q0-.527.062-1.054.094-.558.31-.992.217-.434.559-.683.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 3 7.558V11a1 1 0 0 0 1 1z"
          />
        </svg>
        <div class="carousel-caption d-none d-md-block">
          <div>
            <p class="p-text">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
            </p>
          </div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="35"
            height="35"
            fill="#455A64"
            class="bi bi-quote right"
            viewBox="0 0 16 16"
          >
            <path
              d="M12 12a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1h-1.388q0-.527.062-1.054.093-.558.31-.992t.559-.683q.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 9 7.558V11a1 1 0 0 0 1 1zm-6 0a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1H4.612q0-.527.062-1.054.094-.558.31-.992.217-.434.559-.683.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 3 7.558V11a1 1 0 0 0 1 1z"
            />
          </svg>
        </div>
      </div>

      <!-- Slide 2 -->
      <div class="carousel-item box">
        <p class="title-text">Brittany</p>
        <p class="p-text sec">
          Not all battles are visible and neither are the victories.
        </p>
      </div>

      <!-- Slide 3 -->
      <div class="carousel-item box">
        <p class="title-text">Mike Moreno</p>
        <p class="p-text sec">
          Just remember, you are not alone, in fact, you are in a very commonplace with millions of others.
        </p>
      </div>

      <!-- Slide 4 -->
      <div class="carousel-item box">
        <p class="title-text">Raymond</p>
        <p class="p-text sec">
          Change what you can, manage what you can’t.
        </p>
      </div>

      <!-- Slide 5 -->
      <div class="carousel-item box">
        <p class="title-text">Selena</p>
        <p class="p-text sec">
          If you are broken, you do not have to stay broken.
        </p>
      </div>
    </div>

    <div class="circle">
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
    </div>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleDark"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
    <div>
      <button type="button" class="slider">Slider Button</button>
    </div>
  </div>
</template>


<script>
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.bundle.min.js";

export default {
  mounted() {
    const carouselElement = document.getElementById("carouselExampleDark");
    if (carouselElement) {
      new bootstrap.Carousel(carouselElement, {
        interval: 5000,
      });
    }
  },
};
</script>

<style scoped>

.sec-3{
  position:absolute;
  width: 1152px;
  height: 642px;
  top: 1915px;
  background-color:#EBF7FC;
  display:flex;
  flex-direction:column;
}
.btns{
width:15px;
height:15px;
background-color:#043953;
border-radius: 50%

}
.title{
width:395px;
height:36px;
margin-top:40px;
margin-left:385px;
color:#043953;
}
.t1{
font-family:'Roboto';
font-weight:500;
font-size:30px;
line-height: 32px;
text-align:center;
}
.slider{
  width:165px;
  height:54px;
  margin-left:490px;
  border-radius:4px;
  padding:13px 18px 13px 18px;
  margin-bottom:35px;
  background-color: #043953;
  color:#FFFFFF;
  font-family: 'Roboto';
  font-size:20px;
  font-weight: 700;
  line-height: 28px;
  text-align: center;
}

.box{
  height:350px;
  width:680px;
  left:235px;
  margin-top:70px;
  background-color:whitesmoke;

}

.p-text{
font-family: 'Roboto';
font-size: 20px;
font-weight: 400;
line-height: 28px;
text-align:justify;
text-underline-position: from-font;
text-decoration-skip-ink: none;

}
.title-text{
width: 138px;
height: 29px;
margin-top:30px;
margin-left: 269px;
color:#043953;
font-family: 'Roboto';
font-size: 22px;
font-weight: 700;
line-height: 28px;
text-align: center;
}
.left{
  margin-left:50px;
}
.right{
  margin-left:450px;
}
.sec{
margin:100px 100px 0px 100px;
}
</style>