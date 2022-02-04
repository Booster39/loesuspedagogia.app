<template>

  <div id = "app" >
    <header>
      <div id = "head-page" >
        <div id = "wrap-menu" >
        </div>
        <div id = "search-bar" >
        </div>
        <div id = "logo">
        </div>
        <div id = "account" >
        </div>
        <div id = "my-cart" >
        </div>
      </div>
    </header>

    <body>
        <!--<router-link to="/">Home</router-link> |-->
        <!--<router-link to="/about">About</router-link>-->
      <!--<router-view />-->
      <div id = "page">
        <div id = "articles">
          <div id = "item">
            <div id = "image">
            </div>
            <div id = "description">
            </div>
            <div id = "title">
            </div>
            <div id = "price">
            </div>
            <div id = "rate">
            </div>
            <div count = "count">
            </div>
      </div>
    </body>

    <footer>
        <div id = "footer" >
        </div>
    </footer>
  </div>
</template>

<style>

all {
  box-sizing: border-box;
}

#app {

  box-sizing: border-box;
  font-size: 15px;
  color: #333;
  line-height: 1.4;
  background-color: #f6f1eb;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

#nav {
  padding: 30px;
  
}

#nav a {
  font-weight: bold;
  color: #1786f5;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>