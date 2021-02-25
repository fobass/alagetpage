<template>
  <div id="app">
    <!-- <mdb-navbar light color="white" position="top" scrolling :scrollingOffset="40"> -->
    <mdb-container>
      <!-- <mdb-navbar light color="white" position="top"> -->
        <mdb-navbar light color="white" position="top" scrolling :scrollingOffset="40">
        <mdb-navbar-brand href="https://mdbootstrap.com/">
          Navbar
        </mdb-navbar-brand>
        <mdb-navbar-toggler>
          <mdb-navbar-nav right>
            <mdb-nav-item href="#">Home</mdb-nav-item>
            <mdb-nav-item href="#">Features</mdb-nav-item>
            <mdb-nav-item href="#" class="downloadbtn">Download</mdb-nav-item>
          </mdb-navbar-nav>
        </mdb-navbar-toggler>
      </mdb-navbar>
      <!-- <hr/> -->
    </mdb-container>

    <mdb-container class="con">
      <section id="gallery">
        <h2 class="mb-5 font-weight-bold text-center">Gallery heading</h2>
        <div class="row">
          <div class="col-md-6 mb-4">
            <img
              src="https://mdbootstrap.com/img/Photos/Others/images/48.jpg"
              class="img-fluid"
              alt=""
            />
          </div>
          <div class="col-md-6">
            <h4 class="mb-3"><strong>This is title of the news</strong></h4>
            <p>
              Nam libero tempore, cum soluta nobis est eligendi optio cumque
              nihil impedit quo minus id quod maxime placeat facere possimus,
              omnis voluptas assumenda est, omnis dolor repellendus et aut
              officiis debitis aut rerum.
            </p>

            <p>
              Nam libero tempore, cum soluta nobis est eligendi optio cumque
              nihil impedit quo minus id quod maxime placeat facere possimus,
              omnis voluptas assumenda est, omnis dolor repellendus et aut
              officiis debitis aut rerum.
            </p>
            <p>
              by <a><strong>Jessica Clark</strong></a
              >, 26/08/2016
            </p>
            <a class="btn btn-primary btn-md">Read more</a>
          </div>
        </div>
      </section>


      

      <h2 class="h1-responsive font-weight-bold text-center my-5">
        Recent posts
      </h2>
      <p class="text-center w-responsive mx-auto mb-5">
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <div id="intro" class="view">
        <div class="mask rgba-black-strong">
          <div
            class="container-fluid d-flex align-items-center justify-content-center h-100"
          >
            <div class="row d-flex justify-content-center text-center">
              <div class="col-md-10">
                <!-- Heading -->
                <h2 class="display-4 font-weight-bold white-text pt-5 mb-2">
                  Travel
                </h2>

                <!-- Divider -->
                <hr class="hr-light" />

                <!-- Description -->
                <h4 class="white-text my-4">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Deleniti consequuntur.
                </h4>
                <button type="button" class="btn btn-outline-white">
                  Read more<i class="fa fa-book ml-2"></i>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <main class="mt-5">
        <div class="container">
          <!--Section: Best Features-->
          <section id="best-features" class="text-center">
            <!-- Heading -->
            <h2 class="mb-5 font-weight-bold">Best Features</h2>

            <!--Grid row-->
            <div class="row d-flex justify-content-center mb-4">
              <!--Grid column-->
              <div class="col-md-8">
                <!-- Description -->
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Quasi voluptate hic provident nulla repellat facere esse
                  molestiae ipsa labore porro minima quam quaerat rem, natus
                  repudiandae debitis est sit pariatur.
                </p>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->

            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-md-4 mb-5">
                <i class="fa fa-camera-retro fa-4x orange-text"></i>
                <h4 class="my-4 font-weight-bold">Experience</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-md-4 mb-1">
                <i class="fa fa-heart fa-4x orange-text"></i>
                <h4 class="my-4 font-weight-bold">Happiness</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-md-4 mb-1">
                <i class="fa fa-bicycle fa-4x orange-text"></i>
                <h4 class="my-4 font-weight-bold">Adventure</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->
          </section>
          <!--Section: Best Features-->

          <hr class="my-5" />

          <!--Section: Examples-->
          <section id="examples" class="text-center">
            <!-- Heading -->
            <h2 class="mb-5 font-weight-bold">Stunning Examples</h2>

            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-lg-4 col-md-12 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/48.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-4 col-md-6 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/49.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-4 col-md-6 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/29.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->

            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-lg-4 col-md-12 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/10.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-4 col-md-6 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/11.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-4 col-md-6 mb-4">
                <div class="view overlay z-depth-1-half">
                  <img
                    src="https://mdbootstrap.com/img/Photos/Others/images/13.jpg"
                    class="img-fluid"
                    alt=""
                  />
                  <div class="mask rgba-white-slight"></div>
                </div>

                <h4 class="my-4 font-weight-bold">Heading</h4>
                <p class="grey-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reprehenderit maiores nam, aperiam minima assumenda deleniti
                  hic.
                </p>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->
          </section>
          <!--Section: Examples-->

          <hr class="my-5" />

          <!--Section: Gallery-->
          <section id="gallery">
            <!-- Heading -->
            <h2 class="mb-5 font-weight-bold text-center">Gallery heading</h2>

            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-md-6 mb-4">
                <!--Carousel Wrapper-->
                <div
                  id="carousel-example-1z"
                  class="carousel slide carousel-fade carousel-fade"
                  data-ride="carousel"
                >
                  <!--Indicators-->
                  <ol class="carousel-indicators">
                    <li
                      data-target="#carousel-example-1z"
                      data-slide-to="0"
                      class="active"
                    ></li>
                    <li
                      data-target="#carousel-example-1z"
                      data-slide-to="1"
                    ></li>
                    <li
                      data-target="#carousel-example-1z"
                      data-slide-to="2"
                    ></li>
                  </ol>
                  <!--/.Indicators-->
                  <!--Slides-->
                  <div class="carousel-inner z-depth-1-half" role="listbox">
                    <!--First slide-->
                    <div class="carousel-item active">
                      <img
                        class="d-block w-100"
                        src="https://mdbootstrap.com/img/Photos/Slides/img%20(130).jpg"
                        alt="First slide"
                      />
                    </div>
                    <!--/First slide-->
                    <!--Second slide-->
                    <div class="carousel-item">
                      <img
                        class="d-block w-100"
                        src="https://mdbootstrap.com/img/Photos/Slides/img%20(129).jpg"
                        alt="Second slide"
                      />
                    </div>
                    <!--/Second slide-->
                    <!--Third slide-->
                    <div class="carousel-item">
                      <img
                        class="d-block w-100"
                        src="https://mdbootstrap.com/img/Photos/Slides/img%20(70).jpg"
                        alt="Third slide"
                      />
                    </div>
                    <!--/Third slide-->
                  </div>
                  <!--/.Slides-->
                  <!--Controls-->
                  <a
                    class="carousel-control-prev"
                    href="#carousel-example-1z"
                    role="button"
                    data-slide="prev"
                  >
                    <span
                      class="carousel-control-prev-icon"
                      aria-hidden="true"
                    ></span>
                    <span class="sr-only">Previous</span>
                  </a>
                  <a
                    class="carousel-control-next"
                    href="#carousel-example-1z"
                    role="button"
                    data-slide="next"
                  >
                    <span
                      class="carousel-control-next-icon"
                      aria-hidden="true"
                    ></span>
                    <span class="sr-only">Next</span>
                  </a>
                  <!--/.Controls-->
                </div>
                <!--/.Carousel Wrapper-->
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-md-6">
                <!--Excerpt-->
                <a href="" class="teal-text">
                  <h6 class="pb-1">
                    <i class="fa fa-heart"></i><strong> Lifestyle </strong>
                  </h6>
                </a>
                <h4 class="mb-3"><strong>This is title of the news</strong></h4>
                <p>
                  Nam libero tempore, cum soluta nobis est eligendi optio cumque
                  nihil impedit quo minus id quod maxime placeat facere
                  possimus, omnis voluptas assumenda est, omnis dolor
                  repellendus et aut officiis debitis aut rerum.
                </p>

                <p>
                  Nam libero tempore, cum soluta nobis est eligendi optio cumque
                  nihil impedit quo minus id quod maxime placeat facere
                  possimus, omnis voluptas assumenda est, omnis dolor
                  repellendus et aut officiis debitis aut rerum.
                </p>
                <p>
                  by <a><strong>Jessica Clark</strong></a
                  >, 26/08/2016
                </p>
                <a class="btn btn-primary btn-md">Read more</a>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->
          </section>
          <!--Section: Gallery-->

          <hr class="my-5" />

          <!--Section: Contact-->
          <section id="contact">
            <!-- Heading -->
            <h2 class="mb-5 font-weight-bold text-center">Contact us</h2>

            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-lg-5 col-md-12">
                <!-- Form contact -->
                <form class="p-5 grey-text">
                  <div class="md-form form-sm">
                    <i class="fa fa-user prefix"></i>
                    <input
                      type="text"
                      id="form3"
                      class="form-control form-control-sm"
                    />
                    <label for="form3">Your name</label>
                  </div>
                  <div class="md-form form-sm">
                    <i class="fa fa-envelope prefix"></i>
                    <input
                      type="text"
                      id="form2"
                      class="form-control form-control-sm"
                    />
                    <label for="form2">Your email</label>
                  </div>
                  <div class="md-form form-sm">
                    <i class="fa fa-tag prefix"></i>
                    <input
                      type="text"
                      id="form32"
                      class="form-control form-control-sm"
                    />
                    <label for="form34">Subject</label>
                  </div>
                  <div class="md-form form-sm">
                    <i class="fa fa-pencil prefix"></i>
                    <textarea
                      type="text"
                      id="form8"
                      class="md-textarea form-control form-control-sm"
                      rows="4"
                    ></textarea>
                    <label for="form8">Your message</label>
                  </div>
                  <div class="text-center mt-4">
                    <button class="btn btn-primary">
                      Send <i class="fa fa-paper-plane-o ml-1"></i>
                    </button>
                  </div>
                </form>
                <!-- Form contact -->
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-7 col-md-12">
                <!--Grid row-->
                <div class="row text-center">
                  <!--Grid column-->
                  <div class="col-lg-4 col-md-12 mb-3">
                    <p>
                      <i class="fa fa-map fa-1x mr-2 grey-text"></i>New York, NY
                      10012
                    </p>
                  </div>
                  <!--Grid column-->

                  <!--Grid column-->
                  <div class="col-lg-4 col-md-6 mb-3">
                    <p>
                      <i class="fa fa-building fa-1x mr-2 grey-text"></i>Mon -
                      Fri, 8:00-22:00
                    </p>
                  </div>
                  <!--Grid column-->

                  <!--Grid column-->
                  <div class="col-lg-4 col-md-6 mb-3">
                    <p>
                      <i class="fa fa-phone fa-1x mr-2 grey-text"></i>+ 01 234
                      567 89
                    </p>
                  </div>
                  <!--Grid column-->
                </div>
                <!--Grid row-->

                <!--Google map-->
                <div
                  id="map-container"
                  class="z-depth-1-half map-container mb-5"
                  style="height: 400px"
                ></div>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->
          </section>
          <!--Section: Contact-->
        </div>
      </main>
    </mdb-container>
  </div>
</template>

<script>
import {
  mdbNavbar,
  mdbContainer,
  mdbNavbarBrand,
  mdbNavbarToggler,
  mdbNavbarNav,
  mdbNavItem,
} from "mdbvue";
export default {
  name: "app",
  components: {
    mdbNavbar,
    mdbNavbarBrand,
    mdbNavbarToggler,
    mdbNavbarNav,
    mdbNavItem,
    mdbContainer,
  },
};
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 80px; */
  background: url("https://mdbootstrap.com/img/Photos/Others/img (40).jpg")no-repeat center center;
  background-size: cover;
  height: 100vh;
}

.downloadbtn {
  padding-left: 5px;
  padding-right: 5px;
  background: rgb(248, 107, 107);
  border-radius: 5px;
  color: #2c3e50!important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5);   
}

.downloadbtn:active {
  padding-left: 5px;
  padding-right: 5px;
  background: rgb(209, 54, 54);
  border-radius: 5px;
  color: #2c3e50!important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5);   
}

.downloadbtn:hover {
  padding-left: 5px;
  padding-right: 5px;
  background: rgb(236, 96, 96);
  border-radius: 5px;
  color: #2c3e50!important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 0px rgba(65, 64, 64, 0.5);   
}

.navbar:not(.top-nav-collapse) {
  background: transparent!important;
}

.navbar {
  padding: 50px!important;
  box-shadow: none !important;
}

.navbar-light:not(.top-nav-collapse) .navbar-brand {
    color: rgba(255, 255, 255, 0.9);
}
.navbar-light:is(.top-nav-collapse){
   padding: 20px!important;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:not(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link:hover {
  color:rgb(199, 197, 197);
  -webkit-transition: .35s;
  transition: .35s;
  font-weight: 590;
  padding-left: 20px;
  padding-right: 20px;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:not(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
  color: white;
  -webkit-transition: .35s;
  transition: .35s;
  font-weight: 590;
  padding-left: 20px;
  padding-right: 20px;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:is(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
  color:rgb(75, 74, 74);
  -webkit-transition: .35s;
  transition: .35s;
  font-weight: 700;
  padding-left: 15px;
  padding-right: 15px;
}

.ripple {
  display:none !important;
  color:rgb(75, 74, 74);
}

/* 
.navbar.navbar-light .nav-item .nav-link:hover { 
  color: #CC0000!important; 
} 

.navbar.navbar-light .nav-item .nav-link:focus { 
  color: #FF8800!important; 
} 

.navbar.navbar-light .nav-item .nav-link:active { 
  color: #007E33!important; 
} 

.navbar.navbar-light .nav-item .nav-link:visited { 
  color: #ffffff!important; 
}  */

/* width */
::-webkit-scrollbar {
  width: 7px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: rgb(250, 148, 148);
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: rgb(248, 107, 107);
}

@media only screen and (max-width: 990px) {
  .navbar:not(.top-nav-collapse) {
    background: white!important;
    color: #2c3e50!important;
    -webkit-transition: .35s;
    transition: .35s;
    font-weight: 500;
    padding: 5px!important;
    padding-left: 5px!important;
    padding-right: 5px!important;
  }

  .navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:not(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
    color: #2c3e50!important;
    -webkit-transition: .35s;
    transition: .35s;
    font-weight: 590;
    padding-left: 20px!important;
    padding-right: 20px!important;
    padding: 5px!important;
  }

  .navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:is(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
    color:rgb(75, 74, 74);
    -webkit-transition: .35s;
    transition: .35s;
    font-weight: 700;
    padding-left: 1px!important;
    padding-right: 1px!important;
    padding: 5px!important;
  }

  .navbar-light:not(.top-nav-collapse) .navbar-brand {
    color: rgba(0,0,0,.9)!important;
    -webkit-transition: .35s;
    transition: .35s;
    font-weight: 500;
    padding: 1px!important;
    padding-left: 0px!important;
    padding-right: 0px!important;
  }
}
</style>
