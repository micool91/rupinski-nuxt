<template>
<div class="card card-1">
  <h1>Koncerty</h1>
  <br>
  <br>
  <p>Oto lista najnowszych, wiosennych wydarzeń na 2019 rok:</p>
  <p>- 28 marca o godz. 07:30 - Daniel udzielił wywiadu w programie Wstaje Nowy Dzień telewizji TVP Olsztyn. Relację z tego wydarzenia można obejrzeć <a href="https://www.facebook.com/TVP3Olsztyn/videos/vb.328790637250849/367365680476713/?type=2&theater" target="_blank">TUTAJ</a>.</p>
  <p>- 2 kwietnia o godz. 18:00 - koncert przed Olsztyńskim Ratuszem Miejskim z okazji obchodów Światowego Dnia Autyzmu</p>
  <p>- 4 kwietnia o godz. 08:00 - spotanie z Danielem w Zespole Placówek Edukacyjnych w Olsztynie.</p>
  <p>- 4 kwietnia o godz. 16:00 - koncert oraz spotkanie w miejscowości Ameryka, koło Olsztynka, relację z wydarzenia można obejrzeć <a href="https://youtu.be/JaDsp0vwESM" target="_blank">TUTAJ</a>.</p>
  <p>- 10 kwietnia o godz. 9:00 - koncert i spotkanie w Przedszkolu Bajkowy Dom w Olsztynie.</p>
  <p>- 24 kwietnia o godz. 20:00 - można będzie usłyszeć Daniela na lotnisku w Szymanach, gdzie zagra on hejnał Krakowa oraz hymn Warmii.</p>
  <p>- 5 maja o godz. 12:30 - tuż po hejnale na scenie Staromiejskiej promocja płyty w ramach akcji Caritas Biała Niedziela.</p>
  <p>- 8 maja o godz. 10:00 - spotkanie w ośrodku Laurentius na Redykajnach w ramach promocji płyty.</p>
  <br>
  <br>
  <i><p align=CENTER>Ubiegłoroczne wydarzenia:</p></i>
  <center><img src="~/assets/concert.jpg" alt="Koncert"></center>
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