<template>
  <div class="home">



    <body id="page-top" data-spy="scroll" data-target=".navbar-fixed-top">


      <!-- HEADER -->
      <header class="intro">
        <div class="intro-body">
          <div class="container">
            <div class="row">
              <div class="col-md-12 col-offset-2 text-center">
                <span class="intro-heading">Benjamin Holsinger</span>
                <p> </p>
                <p class="intro-text">Front End Web Developer
                </p>
                <a href="#about" class="btn btn-default page-scroll">Find Out More</a>
              </div>
            </div>
          </div>
        </div>
      </header>
      </Portfolio>
      </Contact>









      <!-- Portfolio Modals -->

      <!-- /Project Modals -->

    </body>
  </div>
</template>

<script>
  // @ is an alias to /src
  import HelloWorld from "@/components/HelloWorld.vue";
  import Portfolio from "@/components/Portfolio.vue";
  import Contact from "@/components/Contact.vue"

  export default {
    name: "home",
    components: {
      HelloWorld,
      Portfolio,
      Contact
    }
  };
</script>

<style scoped>
  body {
    overflow-x: hidden;
    font-family: "Lato", sans-serif;
    background: #000;
  }

  html {
    width: 100%;
    height: 100%;
  }

  h1,
  h2,
  h3,
  h4,
  h5,
  h6 {
    margin: 0 0 35px;
    text-transform: uppercase;
    font-family: "Montserrat", sans-serif;
    letter-spacing: 1.5px;
  }

  p {
    margin: 0 0 25px;
    font-size: 18px;
  }

  a:hover,
  a:focus,
  a:active {
    outline: none;
  }

  .btn {
    background: transparent;
    color: #fff;
    width: 150px;
    height: 35px;
    border-style: solid;
    border-radius: 0;
    font-family: Roboto;
    font-size: 15px;
    text-transform: uppercase;
  }

  .btn:hover {
    background-color: #ffffff;
    transition-duration: 0.5s;
    color: #0083ae;
    outline: none;
  }

  /*-----------------------------------------------------------------------------
NAVIGATION
-----------------------------------------------------------------------------*/
  .navbar-default .navbar-nav>.active>a,
  .navbar-default .navbar-nav>.active>a:hover,
  .navbar-default .navbar-nav>.active>a:focus {
    color: #fff;
    background-color: #0083ae;
  }

  .navbar-default .navbar-brand {
    color: #0083ae;
  }

  .navbar-default .navbar-nav>li>a {
    color: #5e5e5e;
  }

  .navbar-default .navbar-nav>li>a:hover {
    color: #0083ae;
  }

  .navbar-default .navbar-brand:hover,
  .navbar-default .navbar-brand:focus {
    color: #808080;
  }

  .navbar-default a.navbar-brand:visited {
    color: #808080;
  }

  .navbar {
    padding: 5px;
    background-color: #ffffff;
    border-bottom-color: #7f919b;
  }

  .navbar-brand {
    text-transform: uppercase;
    font-family: "Montserrat", sans-serif;
    font-size: 25px;
    letter-spacing: 1px;
  }

  .navbar li {
    font-family: "Montserrat", sans-serif;
    font-weight: 400;
    font-size: 18px;
    letter-spacing: 0.5px;
    text-transform: uppercase;
  }

  /*-----------------------------------------------------------------------------
HEADER and below is the body and layout
-----------------------------------------------------------------------------*/

  .intro {
    background: #000;
    background-position: center;
    background-repeat: no-repeat;
    display: table;
    width: 100%;
    height: auto;
    margin-top: -18px;
    padding: 180px 0;
    text-align: center;
    background-size: cover;
  }

  .intro .intro-body {
    display: table-cell;
    vertical-align: middle;
  }

  .intro .intro-body .intro-heading {
    font-family: "Roboto", sans-serif;
    font-size: 80px;
    color: #fff;
    margin-top: 80px;
  }

  .intro .intro-text {
    margin-top: -30px;
    font-size: 23px;
    font-family: "Roboto", sans-serif;
    color: #fff;
  }

  .contWriting {
    color: #fff;
  }

  section {
    background: #000;
    padding: 100px;
  }

  section h2.section-heading {
    margin-top: 0;
    margin-bottom: 15px;
    font-family: "Montserrat", sans-serif;
    font-size: 29px;
    font-weight: 300;
    color: #fff;
    line-height: 1;
    letter-spacing: -1px;
  }

  /* only needed in version 1
.portfolio-item {
  margin-top: 20px;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
}

#portfolio .portfolio-item .portfolio-link {
  display: block;
  position: relative;
  margin: auto;
  max-width: 350px;
}

.portfolio-item .img-responsive {
  margin: 0 auto;
}

#portfolio .portfolio-item .caption-content {
  margin: 0 auto;
  text-align: center;
}

.container{
  display: flex;
  justify-content: center;
}

*/

  #about {
    padding: 200px 50px 200px 50px;
  }

  #contact {
    padding: 150px 50px 120px 50px;
  }

  #footer {
    padding: 50px 50px 10px 50px;
  }

  /*-----------------------------------------------------------------------------
MEDIA QUERIES
-----------------------------------------------------------------------------*/

  @media (min-width: 769px) {
    .intro-heading {
      font-size: 80px;
    }

    .intro .intro-body .intro-text {
      font-size: 23px;
    }

    section h2.section-heading {
      font-size: 35px;
    }

    p {
      margin: 0 0 35px;
      font-size: 16px;
      line-height: 1.6em;
    }
  }

  @media (max-width: 768px) {
    .intro .intro-body .intro-heading {
      font-size: 60px;
    }

    .intro .intro-body .intro-text {
      font-size: 18px;
    }

    section h2.section-heading {
      font-size: 35px;
    }

    section {
      padding: 100px 0;
      margin: auto;
    }

    .flex-container {
      display: flex;
      text-align: center;
      margin-right: 30%;
      width: 100vw;
    }
  }

  @media (max-width: 565px) {
    .intro-text {
      padding: 30px;
    }

    .flex-container {
      display: flex;
      text-align: center;
      margin-right: 30%;
      width: 100vw;
    }
  }

  @media (max-width: 360px) {
    .intro .intro-body .intro-heading {
      font-size: 45px;
    }

    .intro .intro-body .intro-text {
      font-size: 18px;
    }

    .flex-container {
      display: flex;
      text-align: center;
      margin-right: 30%;
      width: 100vw;
    }
  }
</style>