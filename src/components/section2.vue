<template>
  <!-- section2 header -->
   <div>
      <h2 class="header">SECTION II [20 points]</h2>
   </div>
  
      <!-- dropdown -->
      <select class="form-select drops" aria-label="Default select example" @change="fetchShows" v-model="selectedOption">
          <option value="cars">cars</option>
          <option value="movie">movie</option>
          <option value="2">Two</option>
          <option value="3">Three</option>
          <option value="4">Four</option>
      </select>
      
    <!-- cards -->
   <div class="cards">
      <div class="card-names">
         <p class="f-title">{{ shows[0]?.show?.type}}</p>
         <p class="f-title">{{ shows[1]?.show?.type }}</p>
         <p class="f-title">{{ shows[2]?.show?.type}}</p>
      </div>
      <div class="c-group">
    <div class=" custom-card">
      <p class="c-title">{{ shows[0]?.show?.name}}</p>
      <p class="c-para">{{ shows[0]?.show?.summary}}</p>
      <p class="c-price">Price:<span class="line">4999/-</span></p>
      <p class="new-price">4499/-</p>
      <button type="button" style="color:#FFFFFF;"class=" custom-btn">Click</button>
    </div>
  
    <div class="custom-card">
      <p class="c-title">{{ shows[1]?.show?.name}}</p>
      <p class="c-para">{{ shows[1]?.show?.summary}}</p>
      <p class="c-price">Price:<span class="line">4999/-</span></p>
      <p class="new-price" style="color:#32959D ;">4499/-</p>
      <button type="button" style="background-color:#32959D;color:#FFFFFF;"class="custom-btn">Click</button>
    </div>
  
    <div class=" custom-card">
      <p class="c-title">{{ shows[2]?.show?.name}}</p>
      <p class="c-para">{{ shows[2]?.show?.summary}}</p>
      <p class="c-price">Price: <span class="line">4999/-</span></p>
      <p class="new-price" style="color: #9C7777;">4499/-</p>
      <button type="button" style="color:#FFFFFF;background-color: #9C7777;" class=" custom-btn">Click</button>
    </div>
  </div>
   </div>
  
  <!-- dropdown -->
  <select class="form-select drops1" aria-label="Default select example">
          <option selected >Lorem ipsum dolor sit amet</option>
          <option value="1">One</option>
          <option value="2">Two</option>
          <option value="3">Three</option>
          <option value="4">Four</option>
      </select>
  <!-- dropdown -->
  <select class="form-select drops2" aria-label="Default select example">
          <option selected >Lorem ipsum dolor sit amet</option>
          <option value="1">One</option>
          <option value="2">Two</option>
          <option value="3">Three</option>
          <option value="4">Four</option>
      </select>    
  </template>
  
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;700&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');
  
  .header{
      position:absolute;
      width:275px;
      height:33px;
      top:929px;
      left:439px;
      font-family: 'Roboto';
      font-weight: 400;
      font-size: 28px;
      line-height: 32.81px;
      text-align: center;
      color:#2B7397;
  }
  
  .drops{
      position: absolute;
      width:701.61px;
      height:65px;
      top:1013px;
      left:225.2px;
      border-radius: 6px;
      color:#455A64;
      font-family: 'Roboto';
      font-weight: 400;
      font-size: 20.37px;
      line-height:22.88px;
      background-color: #F4FBFF;
  }
  .cards{
      position: absolute;
      width:1162px;
      height:505px;
      top:1097px;
      left:-5px;
      background-color:#F7FBFD;
    }
    .c-group{
      display:flex;
      flex-direction:row;
      justify-content: center;
      background-color: #F4FBFF;
    }
  .custom-card {
      width: 277.56px; 
      height:auto;
      margin: 20px;
      border-radius: 10px;
      border: 1px solid #2B7397;
      display:flex;
      flex-direction: column;
      align-items:center;
    }
  .c-title{
      margin-top:50px;
      width:103.53px;
      height:25px;
      font-family: 'Roboto';
      font-size: 16px;
      font-weight: 400;
      line-height: 25px;
      text-align: center;
      color:#3B3019;
  }  
  .c-para {
    margin-top: 0px;
    margin-bottom:0px;
    width: 220.28px;
    height:180px;
    font-family: 'Quicksand', sans-serif;
    font-weight: 500;
    font-size: 16px;
    line-height: 25px;
    text-align: justify;
    overflow-y: scroll;
    overflow-x: hidden;
    padding: 10px;
    box-sizing: border-box;
    -ms-overflow-style: none;
    scrollbar-width: none; 
    color:#455A64;
}

.c-para::-webkit-scrollbar {
    display: none;
}
  .c-price{
      width:101.33px;
      height:25px;
      margin-top:20px;
      margin-bottom:0px;
      font-family:'Roboto';
      font-weight:500;
      font-size:16px;
      line-height:25px;
      text-align:center;
      color:#455A64;
      }
  .line{
      text-decoration: line-through;
  }   
  .new-price{
      color:#04547B;
      margin-top:5px;
      width:64.98px;
      height:25px;
      font-family:'Roboto';
      font-weight:400;
      font-size:20px;
      line-height:25px;
      text-align:center;
  }
  .custom-btn{
      width:277.56px;
      height:49px;
      background-color: #2B7397;
      border-color: #2B7397;
      border-bottom-left-radius: 10px;
      border-bottom-right-radius: 10px;
      border-width: 0px;
      font-family:'Roboto';
      font-weight: 300;
      font-size: 16px;
      line-height: 25px;
      text-align: center;
  }
  .drops1{
      position:absolute;
      top:1651px;
      left:225.2px;
      width:701.61px;
      height:65px;
      border-radius: 6px;
      background-color:#F4FBFF ;
  }
  .drops2{
  position:absolute;
  width: 701.61px;
  height: 65px;
  top: 1731px;
  left: 225.2px;
  border-radius: 6px;
  background-color:#F4FBFF ;
  }
  
  .f-title{
      margin-top:25px;
      width:277.56px;
      height:24px;
      margin-left:30px;
      font-family: 'Roboto';
      font-size: 20.37px;
      font-weight: 400;
      line-height: 23.88px;
      color:#455A64;


  }
  .card-names{
      display:flex;
      flex-direction:row;
      justify-content:space-evenly;
      margin-left:95px;
      padding-left: 90px;
  }
  </style>

<script>
import axios from 'axios';

export default {
  data() {
    return {
      selectedOption: "cars", 
      shows: []
    };
  },
  mounted() {
    this.fetchShows();
  },
  methods: {
    async fetchShows() {
      if (this.selectedOption) {
        try {
          const response = await axios.get(
            `http://api.tvmaze.com/search/shows?q=${this.selectedOption}`
          );
          this.shows = response.data;
          console.log(response.data)
        } catch (error) {
          console.error("Error fetching data:", error);
        }
      }
    }
  }
};
</script>