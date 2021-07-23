<template>
<div class="nav">
      <nav class="mb-1 navbar navbar-expand-lg navbar-dark default-color">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent-3" aria-controls="navbarSupportedContent-3" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent-3">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link waves-effect waves-light" href="#">Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
        </ul>
        <ul class="navbar-nav ml-auto nav-flex-icons">
          <li class="nav-item">
            <a class="nav-link waves-effect waves-light">
              <i class="fab fa-twitter"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link waves-effect waves-light">
              <i class="fab fa-facebook"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link waves-effect waves-light">
              <i class="fab fa-github"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link waves-effect waves-light">
              <i class="fab fa-linkedin"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link waves-effect waves-light">
              <i class="fab fa-google-plus-g"></i>
            </a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle waves-effect waves-light" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              <i class="fas fa-user"></i>
            </a>
            <div class="dropdown-menu dropdown-menu-right dropdown-default" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item waves-effect waves-light" href="#">Action</a>
              <a class="dropdown-item waves-effect waves-light" href="#">Another action</a>
              <a class="dropdown-item waves-effect waves-light" href="#">Something else here</a>
            </div>
          </li>
        </ul>
      </div>
    </nav>
</div>
<div class="container">
  <div class="row">
    <div class="col-5" id="nav">
      <div>
        <div id="class1" @click="displayMod1">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">IT3150 - English</h5>
                </div>
              </a>
        </div>

        <div id="class2" @click="displayMod2">            
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">IT3151 - Mathematics</h5>
                </div>
                </a>
        </div>
            

        <div id="class3" @click="displayMod3">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">IT3152 - Science</h5>
                </div>
                </a>
        </div>

        <div id="class4" @click="displayMod4">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">IT3153 - Social Studies</h5>
                </div>
                </a>
        </div>

        <div id="class5" @click="displayMod5">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">IT3154 - Mental Health & Awareness</h5>
                </div>
                </a>
        </div>
      </div>
    </div>

    <div class="col-7 subject" id="content">
      <div class="list-group-item list-group-item-action">
        <h> <b>{{ displayMod }} - {{ subject }}</b> </h>
      </div>
      <br/>
      
      <div class="question">
        <label for="w3review">Enter your question for {{ displayMod }} - {{subject}} here!</label>
        <br/>
        <textarea rows="4" cols="50" placeholder="Type your questons here..."></textarea>
        <br><br>
        <input type="submit" value="Submit">
    </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      displayMod: "IT3150",
      subject: "English"
    }
  },
  methods: {
    displayMod1() {
      this.displayMod = "IT3150",
      this.subject = "English"
    },
    displayMod2() {
      this.displayMod = "IT3151",
      this.subject = "Mathematics"
    },
    displayMod3() {
      this.displayMod = "IT3152",
      this.subject = "Science"
    },
    displayMod4() {
      this.displayMod = "IT3153",
      this.subject = "Social Studies"
    },
    displayMod5() {
      this.displayMod = "IT3154",
      this.subject = "Mental Health & Awareness"
    },
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

body{
    background: #24305e;
}

#nav {
    background: white;
}

#content{
    background: silver;
}

.subject{
    font-size:larger;
    text-align:right;
}

.question {
  background: silver;
  text-align: center;
}
</style>
