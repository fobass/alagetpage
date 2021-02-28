<template>
  <div id="app">
    <!-- <mdb-navbar light color="white" position="top" scrolling :scrollingOffset="40"> -->
    <mdb-container>
      <!-- <mdb-navbar light color="white" position="top"> -->
      <mdb-navbar
        light
        color="white"
        position="top"
        scrolling
        :scrollingOffset="40"
      >
        <mdb-navbar-brand href="https://mdbootstrap.com/">
          Navbar
        </mdb-navbar-brand>
        <mdb-navbar-toggler>
          <mdb-navbar-nav right>
            <!-- <mdb-nav-item href="#">Home</mdb-nav-item>
            <mdb-nav-item href="#">Features</mdb-nav-item> -->
            <mdb-nav-item href="#" class="downloadbtn">Download</mdb-nav-item>
          </mdb-navbar-nav>
        </mdb-navbar-toggler>
      </mdb-navbar>
      <!-- <hr/> -->
    </mdb-container>

    <mdb-container class="con">
      <!-- <section id="main-view">
        <div class="main-section col-md-12">
          <h2 class="h1-responsive font-weight-bold my-5 headertext">
            Next generation courier app
          </h2>
          <p class="subtitle">
            Alaget helps you to find people near,
            <br />
            who are going to fly soon to different directions
          </p>
          <li class="list-inline-item">
            <div class="btn-learn-more">
              <a href="#learn-more-view" class="nav-link">GET STARTED TODAY</a>
            </div>
          </li>
        </div>
      </section> -->

      <section id="main-view">
        <h2 class="h1-responsive font-weight-bold text-center my-5 headertext">
          Next generation courier app
        </h2>
        <p class="text-center w-responsive mx-auto mb-5 subtitle">
          Alaget helps you to find people near,
          <br />
          who are going to fly soon to different directions
        </p>

        <li class="list-inline-item">
          <div class="btn-learn-more">
            <a href="#learn-more-view" class="nav-link">GET STARTED TODAY</a>
          </div>
        </li>
      </section>

      <section class="text-center my-5">
        <h2 class="h1-responsive font-weight-bold my-5">Why is it so great?</h2>
        <p class="lead grey-text w-responsive mx-auto mb-5">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam.
        </p>
        <mdb-row>
          <mdb-col md="4">
            <mdb-icon icon="chart-area" size="3x" class="red-text" />
            <h5 class="font-weight-bold my-4">Analytics</h5>
            <p class="grey-text mb-md-0 mb-5">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Reprehenderit maiores aperiam minima assumenda deleniti hic.
            </p>
          </mdb-col>
          <mdb-col md="4">
            <mdb-icon icon="book" size="3x" class="cyan-text" />
            <h5 class="font-weight-bold my-4">Tutorials</h5>
            <p class="grey-text mb-md-0 mb-5">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Reprehenderit maiores aperiam minima assumenda deleniti hic.
            </p>
          </mdb-col>
          <mdb-col md="4">
            <mdb-icon far icon="comments" size="3x" class="orange-text" />
            <h5 class="font-weight-bold my-4">Support</h5>
            <p class="grey-text mb-md-0 mb-5">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Reprehenderit maiores aperiam minima assumenda deleniti hic.
            </p>
          </mdb-col>
        </mdb-row>
      </section>
      <br>
      <footer>

        <hr />
        <div class="list-inline-item">
          <div class="footer-text">
            <p>Copyright © 2020 Alaget. All rights reserved.</p>
            <p class="font-small">
              <a href="http://192.168.0.101:8080/">www.alaget.com</a>
              <a href="/privacy.html"> Privacy </a>
              <a href="#"> Policy </a>
            </p>
          </div>
        </div>
      </footer>
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
  mdbRow,
  mdbCol,
  mdbIcon,
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
    mdbRow,
    mdbCol,
    mdbIcon,
  },
};
</script>

<style>
.footer-text > p {
  opacity: 0.5;
  font-size: 12px;
  /* margin: 27px 0 45px 0; */
  /* color: rgb(94, 95, 95); */
}
html {
  scroll-behavior: smooth;
}

.subtitle {
  font-family: "Raleway", Helvetica, Arial, sans-serif;
  font-size: 26px;
  margin: 45px 0 75px 0;
  color: #fff;
}

#main-view {
  height: 83vh;
}

.btn-learn-more {
  font-family: "Roboto Condensed", Arial, "Helvetica Neue", Helvetica,
    sans-serif !important;
  font-size: 15px !important;
  background-color: tomato !important;
  border: 1px solid rgba(212, 220, 224, 0.5);
  font-weight: bold !important;
  border-radius: 50px;
  /* margin-bottom: 22px; */
  margin-top: 20px;
  color: white;
  padding: 5px;
}

.btn-learn-more > a {
  color: white !important;
}

.btn-learn-more:hover {
  background-color: rgb(251, 108, 82) !important;
  border-color: #804d1e;
}

.headertext {
  font-family: "Ubuntu", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 72px;
  color: white;
  line-height: 115%;
  letter-spacing: -0.06em;
  margin-bottom: 24px;
}

.con {
  /* background: tomato; */
  padding-top: 220px;
  height: 100%;
}

/* #gallery{
  background: forestgreen;
} */
::selection {
  color: #2c3e50;
  background-color: #f5a794;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 80px; */
  background: url("https://mdbootstrap.com/img/Photos/Others/img (40).jpg")
    no-repeat center center;

  /* background: -webkit-linear-gradient(
      rgba(29, 38, 113, 0.8),
      rgba(195, 55, 100, 0.8)
    ),
    url("ttps://mdbootstrap.com/img/Photos/Others/img (40).jpg");
  background: linear-gradient(rgba(29, 38, 113, 0.8), rgba(195, 55, 100, 0.8)),
    url("ttps://mdbootstrap.com/img/Photos/Others/img (40).jpg"); */

  background-size: cover;
  height: 100vh;
}

.downloadbtn {
  padding-left: 5px;
  padding-right: 5px;
  background: tomato;
  border-radius: 5px;
  color: #2c3e50 !important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5);
}

.downloadbtn:active {
  padding-left: 5px;
  padding-right: 5px;
  background: rgb(209, 54, 54);
  border-radius: 5px;
  color: #2c3e50 !important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5);
}

.downloadbtn:hover {
  padding-left: 5px;
  padding-right: 5px;
  background: rgb(236, 96, 96);
  border-radius: 5px;
  color: #2c3e50 !important;
  font-weight: 800px;
  border: 1px solid rgba(212, 220, 224, 0.5);
  box-shadow: 0 0 0px rgba(65, 64, 64, 0.5);
}

.navbar:not(.top-nav-collapse) {
  background: transparent !important;
}

.navbar {
  padding: 50px !important;
  box-shadow: none !important;
}

.navbar-light:not(.top-nav-collapse) .navbar-brand {
  color: rgba(255, 255, 255, 0.9);
}
.navbar-light:is(.top-nav-collapse) {
  padding: 20px !important;
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5) !important;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link,
.navbar:not(.top-nav-collapse).navbar-light
  .navbar-nav
  .nav-item
  .nav-link:hover {
  color: rgb(199, 197, 197);
  -webkit-transition: 0.35s;
  transition: 0.35s;
  font-weight: 590;
  padding-left: 20px;
  padding-right: 20px;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link,
.navbar:not(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
  color: white;
  -webkit-transition: 0.35s;
  transition: 0.35s;
  font-weight: 590;
  padding-left: 20px;
  padding-right: 20px;
}

.navbar .navbar-light .breadcrumb .nav-item .nav-link,
.navbar:is(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
  color: rgb(75, 74, 74);
  -webkit-transition: 0.35s;
  transition: 0.35s;
  font-weight: 700;
  padding-left: 15px;
  padding-right: 15px;
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
  width: 4px;
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
  .subtitle {
    font-family: "Raleway", Helvetica, Arial, sans-serif;
    font-size: 22px;
  }

  .navbar {
    /* background:transparent!important; */
    /* color: #e1e2e4!important; */
    -webkit-transition: 0.35s;
    transition: 0.35s;
    font-weight: 500;
    padding: 15px !important;
    padding-left: 5px !important;
    padding-right: 5px !important;
  }

  .navbar:not(.top-nav-collapse) {
    background: transparent !important;
    /* color: #e1e2e4!important; */
    -webkit-transition: 0.35s;
    transition: 0.35s;
    font-weight: 500;
    padding: 15px !important;
    padding-left: 5px !important;
    padding-right: 5px !important;
  }

  .navbar .navbar-light .breadcrumb .nav-item .nav-link,
  .navbar:not(.top-nav-collapse).navbar-light
    .navbar-nav
    .nav-item:not(.downloadbtn)
    .nav-link {
    color: #2c3e50 !important;
    background: #f1f1f1;
    -webkit-transition: 0.35s;
    transition: 0.35s;
    font-weight: 590;
    padding-left: 0px !important;
    padding-right: 0px !important;
    padding: 10px !important;
  }

  .navbar .navbar-light .breadcrumb .nav-item .nav-link,
  .navbar:is(.top-nav-collapse).navbar-light .navbar-nav .nav-item .nav-link {
    color: rgb(75, 74, 74);
    -webkit-transition: 0.35s;
    transition: 0.35s;
    font-weight: 700;
    padding-left: 10px !important;
    padding-right: 10px !important;
    padding: 10px !important;
  }

  .navbar-light:not(.top-nav-collapse) .navbar-brand {
    color: white !important;
    -webkit-transition: 0.35s;
    transition: 0.35s;
    font-weight: 500;
    padding: 10px !important;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }

  .con {
    padding-top: 170px;
  }

  .headertext {
    color: white;
    font-size: 42px;
  }

  /* .navbar .navbar-light .breadcrumb .nav-item .nav-link, .navbar:not(.top-nav-collapse).navbar-light .navbar-nav .nav-item:is(.downloadbtn) .nav-link {
    padding-left: 5px;
    padding-right: 5px;
    background: tomato!important;
    border-radius: 5px;
    color: #2c3e50!important;
    font-weight: 800px;
    border: 1px solid rgba(212, 220, 224, 0.5);
    box-shadow: 0 0 5px rgba(65, 64, 64, 0.5);   
  } */

  /* .navbar-toggler{
    color: white!important;
     background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,255,255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
  }

  .navbar-toggler-icon {
    color: white!important;
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,255,255, 1)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
  } */

  /* .navbar-toggler {
    border-color: rgb(255,102,203);
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,255,255, 1)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
  }  */
}
</style>
