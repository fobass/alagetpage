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
        <!-- <h2 class="mb-5 font-weight-bold text-center">Gallery heading</h2> -->
        <div class="row">
          <div class="col-md-5">
            <img
              src="https://mdbootstrap.com/img/Photos/Others/images/48.jpg"
              class="img-fluid"
              alt=""
            />
          </div>
          <div class="col-md-6">
            <!-- <h4 class="mb-3"><strong>This is title of the news</strong></h4> -->
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
            <a class="btn btn-primary btn-md">Learn more</a>
          </div>
        </div>
      </section>


      

      <h2 class="h1-responsive font-weight-bold text-center my-5">Recent posts</h2>
    <p class="text-center w-responsive mx-auto mb-5">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    <mdb-row>
      <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
          <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(27).jpg" alt="Sample image" />
          <a>
            <mdb-mask overlay="white-slight" waves/>
          </a>
        </mdb-view>
      </mdb-col>
      <mdb-col lg="7">
        <a class="green-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="utensils" class="pr-2" />Food</h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat mdb-iconcere
          possimus, omnis voluptas assumenda est, omnis dolor repellendus et aut officiis debitis.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 19/08/2018</p>
        <mdb-btn color="success" size="md" class="waves-light ">Read more</mdb-btn>
      </mdb-col>
    </mdb-row>
    <hr class="my-5" />
    <mdb-row>
      <mdb-col lg="7">
        <a class="pink-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="image" class="pr-2" />Lifestyle
          </h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti
          quos dolores et quas molestias excepturi sint occaecati cupiditate non provident.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 14/08/2018</p>
        <mdb-btn color="pink" size="md" class="mb-lg-0 mb-4 waves-light">Read more</mdb-btn>
      </mdb-col>
      <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
          <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(34).jpg" alt="Sample image" />
          <a>
            <mdb-mask overlay="white-slight" waves/>
          </a>
        </mdb-view>
      </mdb-col>
    </mdb-row>
    <hr class="my-5" />
    <mdb-row>
      <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
          <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img (28).jpg" alt="Sample image" />
          <a>
            <mdb-mask overlay="white-slight" waves/>
          </a>
        </mdb-view>
      </mdb-col>
      <mdb-col lg="7">
        <a class="indigo-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="suitcase" class="pr-2" />Food</h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos
          qui ratione voluptatem sequi nesciunt. Neque porro qui dolorem ipsum quia sit amet.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 11/08/2018</p>
        <mdb-btn color="indigo" size="md" class="waves-light ">Read more</mdb-btn>
      </mdb-col>
    </mdb-row>
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
.con{
  background: tomato;
  padding-top: 300px;
  
}

#gallery{
  background: forestgreen;

}

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
  background: tomato;
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
  box-shadow: 0 0 5px rgba(65, 64, 64, 0.5) !important;
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
