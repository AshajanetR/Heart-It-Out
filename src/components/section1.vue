<template>
  <!-- Section 1 Header -->
  <form class="custom-form">
    <div class="custom-header-layout">
      <h2 class="custom-header">SECTION I [15 points]</h2>
    </div>

    <!-- Section 1 Radio Buttons -->
    <label class="labelradio">Lorem ipsum dolor sit amet</label>
    <div class="form-check indi-radio1">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
      <label class="form-check-label" for="flexRadioDefault1">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio2">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2">
      <label class="form-check-label" for="flexRadioDefault2">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio3">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3">
      <label class="form-check-label" for="flexRadioDefault3">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio4">
      <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault4">
      <label class="form-check-label" for="flexRadioDefault4">
        Radio Button Option
      </label>
    </div>

    <!-- Section 1 Dropdown -->
    <p class="para">Lorem ipsum dolor sit amet</p>
    <select class="form-select select-drop" aria-label="Default select example">
      <option selected>Drop Down Option</option>
      <option value="1">One</option>
      <option value="2">Two</option>
      <option value="3">Three</option>
    </select>

    <!-- Section 1 Checkboxes -->
    <label class="labelradio0">Lorem ipsum dolor sit amet</label>
    <div class="form-check indi-radio11">
      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault1">
      <label class="form-check-label" for="flexCheckDefault1">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio22">
      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault2">
      <label class="form-check-label" for="flexCheckDefault2">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio33">
      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault3">
      <label class="form-check-label" for="flexCheckDefault3">
        Radio Button Option
      </label>
    </div>
    <div class="form-check indi-radio44">
      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault4">
      <label class="form-check-label" for="flexCheckDefault4">
        Radio Button Option
      </label>
    </div>

    <!-- Section 1 Submit Button -->
    <div class="button-box">
      <p class="button-text">SUBMIT</p>
    </div>
  </form>
</template>


<style scoped>
/* header */
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

.custom-header{
  font-family:'Roboto';
  font-size:30px;
  line-height:35.16px;
  text-align:center;
  font-weight:500;
  color:#01818C;
}

.custom-header-layout{
  position:absolute;
  width:289px;
  height:35px;
  top:105px;
  left:432px;
}

/* section1*/
.labelradio{
    position:absolute;
    width:250px;
    height:24px;
    top:228.34px;
    left:182.99px;
    font-family: 'Roboto';
    font-weight:400;
    font-size:20.37px;
    line-height:23.88px;
    color:#455A64;
}

.indi-radio1{
    position:absolute;
    width:174.52px;
    height:19px;
    top:268.07px;
    left:182.99px;
    color:#01818C;
}
.indi-radio2{
    position:absolute;
    width:174.52px;
    height:19px;
    top:301.69px;
    left:182.99px;
}
.indi-radio3{
    position:absolute;
    width:174.52px;
    height:19px;
    top:335.3px;
    left:182.99px;
}
.indi-radio4{
    position:absolute;
    width:174.52px;
    height:19px;
    top:368.92px;
    left:182.99px;
}
/* section1 drop*/
 .para{
    position:absolute;
    width:250px;
    height:24px;
    top:442.27px;
    left:169.75px;
    font-family:'Roboto';
    font-weight:400;
    font-size:20.37px;
    line-height:23.88px;
    color:#455A64;
}
.select-drop{
    position:absolute;
    width:862.86px;
    height:42.79px;
    top:476.91px;
    left:169.75px;
    border-radius: 9.17px;
    border: 1.02px solid #C6C6C6;
}
/*section1radio2*/
.labelradio0{
      position:absolute;
      width:250px;
      height:24px;
      top:598.13px;
      left:169.75px;
      font-family: 'Roboto';
      font-weight:400;
      font-size:20.37px;
      line-height:23.88px;
      color:#455A64;
  }
  
  .indi-radio11{
    position:absolute;
      width:174.52px;
      height:19px;
      top:636.13px;
      left:169.75px;
      color:#01818C;

  }
  .indi-radio22{
      position:absolute;
      width:174.52px;
      height:19px;
      top:671.48px;
      left:169.75px;
  }
  .indi-radio33{
      position:absolute;
      width:174.52px;
      height:19px;
      top:705.1px;
      left:169.75px;
  }
  .indi-radio44{
      position:absolute;
      width:174.52px;
      height:19px;
      top:738.75px;
      left:169.75px;
  }
  /*section1 submit*/
 .button-box{
  position: absolute;
  width:138.42px;
  height:51.6px;
  top:793.73px;
  left:510px;
  border-radius: 4.07px;
  padding:16.3px 38.71px 16.3px 38.71px;
  gap:10.19px;
  background-color:#01818C ;
 }
 .button-text{
  width:61px;
  height:19px;
  font-family: 'Roboto';
  font-weight: 700;
  font-size: 16.3px;
  line-height: 18.34px;
  text-align: center;
  color:#FFFFFF;
 }
</style>