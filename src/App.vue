<template>
  <div class="main-section">
      <div class="search-section">
          <div class="search-content">
            <form>
                <div class="search-group">
                  <input type="text" class="search" placeholder="Search for a word..." />
                  <button class="search-icon" v-on="click" type="submit"><img src="./assets/SearchIcon.svg" /></button>
                </div>
            </form>
            <div class="wordSugestion">
                <ul>
                  <li><a href="#">Meal</a></li>
                  <li><a href="#">Sink</a></li>
                  <li><a href="#">Meal</a></li>
                  <li><a href="#">Sink</a></li>
                  <li><a href="#">Meal</a></li>
                  <li><a href="#">Sink</a></li>
                </ul>
            </div>
          </div>
      </div>
      <div class="result-section">

          <div class="first-row">
            <div class="random-text">
                <button>
                  Random Text
                </button>
            </div>
            <div class="pronunciation">
              <button>
                  <img src="./assets/Lips.svg" />
                  <span>/dsjdsjdjsdnʌn/</span>
              </button>
            </div>
          </div>

          <div class="main-result">
              <div>
                <h2>Gabble</h2>
                <h5>[Kable]</h5>
                <p>To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately To chatter or talk inarticulately </p>
                <div class="box">
                  <h5>Antonyms</h5>
                   <ul class="antonyms">
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                </div>
                <div class="box">
                  <h5>synonyms</h5>
                   <ul class="synonyms">
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                </div>
              </div>
          </div>

          <div class="container">
            <h3>Verb</h3>
            <swiper class="otherDefinition" 
              :slides-per-view="3"
              :space-between="50"
              @swiper="onSwiper"
              @slideChange="onSlideChange">
                <swiper-slide class="definition">
                  <h4 class="lead"> A syntactic marker</h4>
                  <p class="text">All you ever do is surf the Internet. What will you do this afternoon?</p>
                  <div class="box">
                    <h6 class="synonyms">synonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  <div class="box">
                    <h6 class="antonyms">antonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  
                </swiper-slide>
                <swiper-slide class="definition">
                  <h4 class="lead"> A syntactic marker</h4>
                  <p class="text">All you ever do is surf the Internet. What will you do this afternoon?</p>
                  <div class="box">
                    <h6 class="synonyms">synonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  <div class="box">
                    <h6 class="antonyms">antonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  
                </swiper-slide>
                <swiper-slide class="definition">
                  <h4 class="lead"> A syntactic marker</h4>
                  <p class="text">All you ever do is surf the Internet. What will you do this afternoon?</p>
                  <div class="box">
                    <h6 class="synonyms">synonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  <div class="box">
                    <h6 class="antonyms">antonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  
                </swiper-slide>
                <swiper-slide class="definition">
                  <h4 class="lead"> A syntactic marker</h4>
                  <p class="text">All you ever do is surf the Internet. What will you do this afternoon?</p>
                  <div class="box">
                    <h6 class="synonyms">synonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  <div class="box">
                    <h6 class="antonyms">antonyms</h6>
                    <ul>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                      <li>Meal</li>
                      <li>Sink</li>
                    </ul>
                  </div>
                  
                </swiper-slide>
            </swiper>
          </div>
          
          <div class="anotherWordSugestion">
              <h3>Other Word Suggestions</h3>
              <ul>
                <li>Meal</li>
                <li>Sink</li>
                <li>Meal</li>
                <li>Sink</li>
                <li>Meal</li>
                <li>Sink</li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import axios from 'axios';

export default {
  name: 'App',
  components: {
      Swiper,
      SwiperSlide,
  },
  data() {
    return {
      firstSuggestion: [],
    }
  },
  mounted () {
    console.clear()
    console.log(axios);


  },
   methods: {

  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
      onSlideChange,
    };
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins";
}

.main-section {
  background-color: transparent;
}

.search-section {
  background: lightgray;
  position: sticky;
  top: 0;
  z-index: 5;
}

.search-section .search-content {
  text-align: center;
  padding: 2em;
}

.search-section .search-content .search-group {
  position: relative;
}

.search-section .search-content form{
  padding: 1em;
}

.search-section .search-content form .search{
  background-color: inherit;
  border: none;
  outline: 0.1em solid #000000;
  min-width: 25em;
  border-radius: 5em;
  padding: 0.5em 1em;
  font-size: 2em;
  text-transform: uppercase;
}
.search-icon {
  background-color: transparent;
  border: none;
  position: relative;
  right: 5em;
  top: 1em;
}
.search-icon img{
  max-width: 3em;
  cursor: pointer;
}

.search-section .search-content .wordSugestion ul{
  list-style: none;
  text-align: center;
  width: 100%;
  display: flex;
  justify-content: center;
}


.search-section .search-content .wordSugestion ul li a{
  display: block;
  background-color: transparent;
  margin: 1em;
  padding: 1em;
  min-width: 10em;
  outline: .2em solid #000000;
  text-decoration: none;
  text-transform: uppercase;
  color: #000000;
}

.search-section .search-content .wordSugestion ul li a:hover {
  display: block;
  background-color: #ffffff;
  outline: .2em solid #000000;
  color: #000000;
}

.result-section {
  background: grey;
  padding: 2em 6em;
}

.result-section .first-row {
  display: block;
  height: 5 em;
}

.result-section .first-row .random-text{
  float: left;
}

.result-section .first-row .random-text button{
  background-color: transparent;
  border: none;
  outline: 2px solid #000000;
  font-size: 1.5em;
  padding: .4em;
  cursor: pointer;
}

.result-section .first-row .random-text button:hover{
  background-color: #ffffff;
}

.result-section .first-row .pronunciation{
  float: right;
}


.result-section .first-row .pronunciation button{
  display: flex;
  background-color: transparent;
  border: none;
  cursor: pointer;
  flex-direction: column;
  align-items: center;
}

.result-section .first-row .pronunciation button img{
  width: 4em;
}

.result-section .first-row .pronunciation button span{
  font-size: 2em;
}

.result-section .main-result {
  text-align: center;
  margin: 0 auto;
  margin-top: -1em;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 60%;
}

.result-section .main-result p {
  width: 100%;
  padding: .5em 3em;
}

.result-section .main-result .box {
  border: .2em solid #000000;
  margin: .5em;
  border-radius: 1em;
  padding: 1em;
  width: auto;
}

.result-section .main-result .box h5 {
  text-transform: uppercase;
  margin-bottom: 1.5em;
}

.result-section .main-result .box  ul{
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}
.result-section .main-result .box ul li {
  margin: .5em 1em;
  padding: .2em .5em;
  outline: .2em solid #000000;
  flex: auto;
  cursor: pointer;
}
.result-section .main-result .box ul li:hover {
  background: #ffffff;
}

.anotherWordSugestion {
  width: 100%;
  text-align:center;
  padding: 2em;
}


.anotherWordSugestion ul {
  display: flex;
  flex-direction: row;
  text-decoration: none;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}

.anotherWordSugestion ul li {
  flex: auto;
  list-style: none;
  outline: .2em solid #000000;
  margin: 1em;
  cursor: pointer;
}
.anotherWordSugestion ul li:hover {
  background: #ffffff;
}

.otherDefinition {
  display: block;
  text-align: center;
  margin-top: .1em;
}

.container>h3 {
  text-transform: uppercase;
}

.otherDefinition .definition{
  width: 30%;
  padding: 1em;
  outline: .2em solid #000000;
  border-radius: 1em;
}

.otherDefinition .definition .lead{
   font-weight: bold;
}

.otherDefinition .definition .text::before{
  content: "~";
}

.otherDefinition .definition .box{
  text-align: left;
  padding-left: 1em;
}

.otherDefinition .definition .box ul{
  display: flex;
  gap: .1em;
  flex-wrap: wrap;
}

.otherDefinition .definition .box ul li{
  list-style: none;
}
.otherDefinition .definition .box ul li::after{
  content: ", ";
  margin-right: .1em;
}
.otherDefinition .definition .box ul li:last-child::after{
  content: ".";
}

.container {
  width: 100%;
  padding : 1em;
  text-align: center;
}

.swiper-wrapper {
  padding: 2em;
}
</style>
