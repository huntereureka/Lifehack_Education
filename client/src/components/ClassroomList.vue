<!-- <template>
    <div class="container">
        <div article class="list-group row" id="nav">
        <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Adaptability</h5>
            <small>2 days ago</small>
            </div>
            <p class="mb-1">Abigail, Alexandra, Alison, Amanda, Amelia, Amy, Andrea</p>
            <small>And some small print.</small>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Brilliant</h5>
            <small class="text-muted">2 days ago</small>
            </div>
            <p class="mb-1">Bella, Bernadette, Carol, Caroline, Carolyn, Chloe, Claire</p>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Compassionate</h5>
            <small class="text-muted">2 days ago</small>
            </div>
            <p class="mb-1">Diana, Dorothy, Elizabeth, Faith, Grace</p>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Determination</h5>
            <small class="text-muted">2 days ago</small>
            </div>
            <p class="mb-1">Sarah, Ruth, Sonia, Sophie, Stephanie</p>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Enterprise</h5>
            <small class="text-muted">2 days ago</small>
            </div>
            <p class="mb-1">Vanessa, Zoe, Tracy, Rebecca, Penelope</p>
        </a>
        </div>
            
        <div id="classes" class="row">
            test
        </div>
    </div> 
</template> -->

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
    <div class="col-3" id="nav">
      <div>
        <div id="class1" @click="showclass1">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">4 Adaptability</h5>
                <small>3 days ago</small>
                </div>
                <p class="mb-1">Abigail, Alexandra, Alison, Amanda, Amelia, Amy, Andrea</p>
            </a>
        </div>

        <div id="class2" @click="showclass2">            
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">4 Brilliant</h5>
                <small class="text-muted">1 day ago</small>
                </div>
                <p class="mb-1">Bella, Bernadette, Carol, Caroline, Carolyn, Chloe, Claire</p>
            </a>
        </div>
            

        <div id="class3" @click="showclass3">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">4 Compassionate</h5>
                <small class="text-muted">2 days ago</small>
                </div>
                <p class="mb-1">Diana, Dorothy, Elizabeth, Faith, Grace</p>
            </a>
        </div>

        <div id="class4" @click="showclass4">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">4 Determination</h5>
                <small class="text-muted">4 days ago</small>
                </div>
                <p class="mb-1">Sarah, Ruth, Sonia, Sophie, Stephanie</p>
            </a>
        </div>

        <div id="class5" @click="showclass5">
            <a href="#" class="list-group-item list-group-item-action">
                <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">4 Enterprise</h5>
                <small class="text-muted">5 days ago</small>
                </div>
                <p class="mb-1">Vanessa, Zoe, Tracy, Rebecca, Penelope</p>
            </a>
        </div>

        <!-- <div id="inline-handler">
            <button @click="say('hi')">Say hi</button>
            <button @click="say('what')">Say what</button>
        </div> -->
      </div>
    </div>

    <div class="col" id="content">
      <div>
        <!-- <h1 class="mb-1">Students:</h1> -->
        <!-- <a href="#" class="list-group-item list-group-item-action">
            <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">4 Enterprise</h5>
            <small class="text-muted">2 days ago</small>
            </div>
            <p class="mb-1">Vanessa, Zoe, Tracy, Rebecca, Penelope</p>
        </a> -->

        <ul class="list-group">
        <div class="list-group-item list-group-item-action information">        
            <h class=students> <b>{{ displayClass }}</b> <br/> {{ students }} </h>
        </div>
        <div class="list-group-item list-group-item-action time-elapsed">
            <h class=time-elapsed> Last modified: {{ timeElapsed }} ago</h>
        </div>
        <li class="list-group-item">Example question</li>
        <li class="list-group-item">Example question</li>
        <li class="list-group-item">Example question</li>
        <li class="list-group-item">Example question</li>
        <li class="list-group-item">Example question</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
    name: "ClassroomList",
    data() {
        return {
            displayClass: "4 Adaptability",
            students: "Abigail, Alexandra, Alison, Amanda, Amelia, Amy, Andrea",
            timeElapsed: "2 days"
        }
    },
    methods: {
    say(message) {
      alert(message)
    }, 
    showclass1() {
        this.displayClass = '4 Adaptability'
        this.students = 'Abigail, Alexandra, Alison, Amanda, Amelia, Amy, Andrea'
        this.timeElapsed = '3 days'
    }, 
    showclass2() {
        this.displayClass = '4 Brilliant'
        this.students = 'Bella, Bernadette, Carol, Caroline, Carolyn, Chloe, Claire'
        this.timeElapsed = '1 day'
    }, 
    showclass3() {
        this.displayClass = '4 Compassionate'
        this.students = 'Diana, Dorothy, Elizabeth, Faith, Grace'
        this.timeElapsed = '2 days'
    }, 
    showclass4() {
        this.displayClass = '4 Determination'
        this.students = 'Sarah, Ruth, Sonia, Sophie, Stephanie'
        this.timeElapsed = '4 days'
    }, 
    showclass5() {
        this.displayClass = '4 Enterprise'
        this.students = 'Vanessa, Zoe, Tracy, Rebecca, Penelope'
        this.timeElapsed = '5 days'
    } 
  }
}
</script>

<style>
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

.time-elapsed{
    text-align: right;
    align-content: right;
}

.information{
    font-size:larger
}
</style>