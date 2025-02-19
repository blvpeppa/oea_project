<template>
<link href="css/font-awesome.min.css" rel="stylesheet">
    <link href="css/animate.min.css" rel="stylesheet">
    <link href="css/prettyPhoto.css" rel="stylesheet">
    <link href="css/main.css" rel="stylesheet">
    <link href="css/responsive.css" rel="stylesheet">

  <div class="container">
    <header class="border-bottom lh-1 py-3">
      <div class="row flex-nowrap justify-content-between align-items-center">
        <div class="col-4 pt-1">
         
            <h1>Orthadox Church</h1>
            in<h2> East Africa</h2>
        
        </div>
        <div class="col-4 d-flex justify-content-end align-items-center">
          <a class="link-secondary" href="#" aria-label="Search">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img" viewBox="0 0 24 24"><title>Search</title><circle cx="10.5" cy="10.5" r="7.5"/><path d="M21 21l-5.2-5.2"/></svg>
          </a>
          <a class="btn btn-sm btn-outline-secondary" href="#">Sign up</a>
        </div>
      </div>
    </header>
    <div class=" py-1 mb-3 border-bottom">
      <nav class="nav nav-underline justify-content-between">
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#" >The Primate</a></li>
          <li><a class="dropdown-item" href="#">The Holy Synod</a></li>
          <li><a class="dropdown-item" href="#">Metropolitan Council</a></li>
          <li><a class="dropdown-item" href="#">Chancery Staff</a></li>
          <li><a class="dropdown-item" href="#">Departments</a></li>
          <li><a class="dropdown-item" href="#">Boards, Offices, & Commissions</a></li>
          <li><a class="dropdown-item" href="#">History & Archives</a></li>
          <li><a class="dropdown-item" href="#">Documents & Policies</a></li></ul>

            <a class="nav-item nav-link link-body-emphasis active" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">About the OCE</a>
        <a class="nav-item nav-link link-body-emphasis" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">News & Media</a>
        <a class="nav-item nav-link link-body-emphasis" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">The Orthodox Faith</a>
        <a class="nav-item nav-link link-body-emphasis" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Directories</a>
        <a class="nav-item nav-link link-body-emphasis" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Work of the Church</a>
      </nav>
    </div>
  </div>
  
  <div class="b-example-divider"></div>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">About</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">Contact</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">Help</a></li>
    </ul>
    <p class="text-center text-body-secondary">&copy; 2025  Orthadox, in association with Orgin Dreams .</p>
  </footer>
</div>
</template>

<script>
/*
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
} */
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.blog-header-logo {
  font-family: "Playfair Display", Georgia, "Times New Roman", serif/*rtl:Amiri, Georgia, "Times New Roman", serif*/;
  font-size: 2.25rem;
}

.blog-header-logo:hover {
  text-decoration: none;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Playfair Display", Georgia, "Times New Roman", serif/*rtl:Amiri, Georgia, "Times New Roman", serif*/;
}

.flex-auto {
  flex: 0 0 auto;
}

.h-250 { height: 250px; }
@media (min-width: 768px) {
  .h-md-250 { height: 250px; }
}

/* Pagination */
.blog-pagination {
  margin-bottom: 4rem;
}

/*
 * Blog posts
 */
.blog-post {
  margin-bottom: 4rem;
}
.blog-post-meta {
  margin-bottom: 1.25rem;
  color: #727272;
}

      .b-example-divider {
        width: 100%;
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

</style>