<template>
<div class="card card-1">
  <h1>O Danielu</h1>
  <p>Daniel Rupiński niewidomy, bardzo utalentowany muzyk z Olsztyna. Gra na trąbce, pianinie, akordeonie, pięknie śpiewa i też komponuje. Najbardziej lubi grać i śpiewać standardy jazzowe, dobrze też czuje się w muzyce pop, ale też w innych gatunkach muzycznych.
Daniela można usłyszeć codziennie o godzinie 12:00, jak gra na trąbce na balkonie olsztyńskiego ratusza hymn Warmii "O Warmio moja miła" do muzyki Feliksa Nowowiejskiego.</p>
<br><br>
  <center><img src="ratusz.jpg" alt="Ratusz Miejski"></center>
<br><br><br><br><br>
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
    max-height: 1000px;
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