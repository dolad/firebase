<template>
    <div class="hero">
        <div class="container">
          <div class="row justify-content-center align-items-center ">
            <div class="col col-md-9">
              <div class="hero-content col-md-8">
               <vue-typed-js :strings="['First text', 'Second Text']" :loop="true">
                   <h1><span  class="typing"></span></h1>
                  </vue-typed-js>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos numquam tempora, iure delectus totam minus quam aperiam ratione dolores magni voluptates ut necessitatibus odio ipsum fuga, voluptas ab praesentium nihil?
                </p>
                
                <div class="hero-btn mt-5">
                    <button class="btn custom-btn btn-info mr-5">Explore</button>
                    <button class="btn custom-btn btn-info">Products</button>
                </div>
              </div>
            </div>
            <div class="col col-md-3 images">
                <div class="graphic">
                    <img src="/img/svg/hero_landing.svg" alt="">
                </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>


export default {
  name: "LandingPage",
 

  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hero{
    padding-top: 7rem;
    padding-left:0px;
    width: 100%;
    height: 50vh;
    text-align: left;
  }
  .images{
    
    img{
      height:250px;
    }
  }
 
</style>