<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
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


          <div class="AnotherWordSugestion">
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
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
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
  height: 100vh;
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
  /* background: red; */
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
}

</style>
