<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div class="main-section">
      <div class="search-section">
          <div class="search-content">
            <form>
                <div>
                  <input type="text" class="search" placeholder="Search for a word..." />
                  <span class="search-icon">Search</span>
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
          <div>
            <div>
                <button>
                  Random Text
                </button>
            </div>
            <div>
              <button>
                  Pronunciation
              </button>
            </div>
          </div>
          <div class="main-result">
              <div>
                <h3>Title</h3>
                <h2>Result Title</h2>
                <p>Meaning paragraph</p>
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

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.main-section {
  background-color: red;
}

.search-section {
  background: lightgray;
  /* height: 30vh; */
  position: sticky;
  top: 0;
}

.search-section .search-content {
  text-align: center;
  padding: 2em;
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

/* 
.search-section .search-content .wordSugestion{

} */


.search-section .search-content .wordSugestion ul{
  /* background-color: blue; */
  list-style: none;
  text-align: center;
  width: 100%;
  display: flex;
  justify-content: center;
}

.search-section .search-content .wordSugestion ul li{

  /* background-color: transparent; */
  /* margin: 1em; */
  /* padding: 1em; */
  /* border-radius: 3em; */
  /* min-width: 10em; */
  /* outline: .2em solid #000000; */
}


.search-section .search-content .wordSugestion ul li a{
  display: block;
  background-color: transparent;
  margin: 1em;
  padding: 1em;
  border-radius: 3em;
  min-width: 10em;
  outline: .2em solid #000000;
  text-decoration: none;
  text-transform: uppercase;
  color: #000000;
}



.result-section {
  background: grey;
  padding: 2em;
  height: 100vh;
}


</style>
