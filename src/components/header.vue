<template>
<div class="top">
<nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#"><img src="../assets/logo.png"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
</nav>
<banner/>
</div>


</template>

<script>
import Banner from "./banner";

export default {
  name: "app",
  components: {Banner}
};
</script>

<style>
.top{
    position: relative;
    background: -moz-linear-gradient(top, rgba(78,25,186,0.87) 0%, rgba(20,102,234,0.97) 100%);
    background: -webkit-linear-gradient(top, rgba(78,25,186,0.87) 0%,rgba(20,102,234,0.97) 100%);
    background: linear-gradient(to bottom, rgba(78,25,186,0.87) 0%,rgba(20,102,234,0.97) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#de4e19ba', endColorstr='#f71466ea',GradientType=0 );
   
}
.top img{
  width:100%;
}
</style>