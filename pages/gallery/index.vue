<template>
<div class="card card-1">
  <h1>Galeria</h1>
  <br>
  <br>
  <center>
     <a href="/z1.jpg" target="_blank"><img src="~/assets/z1_min.jpg" alt="Koncert"></a>
     <a href="/z2.jpg" target="_blank"><img src="~/assets/z2_min.jpg" alt="Koncert"></a>
     <a href="/z3.jpg" target="_blank"><img src="~/assets/z3_min.jpg" alt="Koncert"></a>
  </center>
  <center>
    <a href="/z4.jpg" target="_blank"><img src="~/assets/z4_min.jpg" alt="Koncert"></a>
    <a href="/z5.jpg" target="_blank"><img src="~/assets/z5_min.jpg" alt="Koncert"></a>
    <a href="/z6.jpg" target="_blank"><img src="~/assets/z6_min.jpg" alt="Koncert"></a>
  </center>
<br><br><br><br><br>
</div>
</template>


<style scoped>
h1 {
  text-align: center;
}

.card {
  background: #fff;
  border-radius: 2px;
  margin: 1rem;
  position: relative;
  padding: 30px;
  max-width: 98%;
}

.card-1 {
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

a {
  text-decoration: none;
  color:#b16a00;
}
a:hover {
  color: #dfb380;
  text-decoration: underline;
}

p {
  padding: 10px;
  font-size: 1.2em;
}

img {
    max-height: 334px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    box-shadow: 0 1px 30px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
    margin-right: 40px; 
    margin-block-start: 40px; 
    max-width: 100%;
    height: auto;
}
</style>