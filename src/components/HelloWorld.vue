<template>
  <div>
    <full-page :options="options">      
      <div class="section">
        <div class="title">          
          QUè fEm 
          <br>amb El NOstrE
          <br>tEmps?
          <br><br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          FEm util
          <br>El NOstrE
          <br>tEmps!
          <br><br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          ANar FENt
          <br><br>
          BaNC dEL tEmps dEl RipOllès
          <br><br>
          www.aNarfENtbdt.Cat
          <br><br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          QUe és UN BaNC dEL tEmps
          <ul class="ul">
            <li>Xarxa de sUpOrt mUtú</li>
            <li>Intercanvi serveis, coneixements, tasques</li>
            <li>Sense diners</li>
          </ul>
          <br><br><br><br><br>
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          MONEda = TEmps
        </div>        
        <br><br><br><br>
      </div>
      <div class="section">
        <div class="title title2">
          Valors
          <ul class="ul">
            <li>integració social</li>
            <li>relacions intergeneracionals i interculturals</li>
            <li>relacions veïnals</li>
            <li>autoestima</li>
            <li>coneixença, igualtat, confiança i cooperació</li>
            <li>conciliació de la vida personal, familiar i laboral</li>
          </ul>
          <br><br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          Com neix el banc del temps del Ripollès
          <ul class="ul">
            <li>XES RipollEs</li>            
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          Qui pot formar part del Banc
          <ul class="ul">
            <li>Persones majors de 18 anys</li>
            <li>Entitats</li>
            <li>Col·lectius</li>
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          Com formar part del Banc
          <ul class="ul">
            <li>Formulari de <a href="https://docs.google.com/forms/d/1kyGJJOlIzL1ftFsfc8FigTECDBRI2murhsnUDvfVk-E" target="_blank">preinscripció</a></li>
            <li>Entrevista personal</li>
            <li>Aplicació web <a href="https://www.timeoverflow.org/" target="_blank">TimeOverflow</a></li>
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          TIMEOVERFLOW
          <ul class="ul">
            <li>Membres</li>            
            <li>Ofertes</li>
            <li>demandes</li>            
          </ul>
        </div>        
      </div>         
      <div class="section">
        <div class="title title2">
          Com hi poden participar les entitats
          <ul class="ul">
            <li>Ofertes i demandes</li>
            <li>Compte solidari</li>            
          </ul>
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          Tallers
          <ul class="ul">
            <li>Oferta o demanda Grupal</li>
            <li>Promoguts des del banc</li>
            <li>Promoguts des de les persones membres</li>
          </ul>
          <br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          Com realitzar intercanvis
          <ul class="ul">
            <li>Aplicació web <a href="https://www.timeoverflow.org/" target="_blank">TimeOverflow</a></li>
            <li>Membres, Ofertes i demandes</li>
            <li>Contacte directe entre membres</li>
            <li>Transferència de Temps</li>
          </ul>
          <br><br><br><br>
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          Quins intercanvis puc fer
          <ul class="ul3">
          <li>art i artesania</li>
          <li>assessorament i orientació general</li>
          <li>compres i comerç</li>
          <li>cuina</li>
          <li>cultura</li>
          <li>cura d’animals</li>
          <li>ensenyament</li>
          <li>esports i animació</li>
          <li>idiomes</li>
          <li>informàtica i altres tecnologies</li>
          <li>lleure i entreteniment</li>
          <li>obra i construcció</li>
          <li>salut i cura de persones</li>
          <li>servei tècnic</li>
          <li>serveis a la comunitat</li>
          <li>teràpies alternatives</li>
          <li>transport</li>
          <li>treballs de jardineria</li>
          <li>treballs de la llar</li>
          </ul>
          <br><br><br><br>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          Conducta
          <ul class="ul">
            <li>Respecte</li>
            <li>Privacitat de dades</li>            
          </ul>
        </div>        
      </div>      
      <div class="section">
        <div class="title title">
          MOltEs GräCiEs!!!
          <br><br>
          ANar FENt
          <br>
          BaNC dEL tEmps dEl RipOllès
          <br>
          www.aNarfENtbdt.Cat
          <br><br><br><br>
        </div>        
      </div>      
    </full-page>    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data () {  
    return {
      options: {
        scrollOverflow: false,
        licenseKey: 'z',
        navigation: true,
        menu: '#menu',
        sectionsColor: ['#ffffff', '#2C3E5D', '#2492AB','#ffffff', '#2C3E5D', '#2492AB','#ffffff', '#2C3E5D', '#2492AB','#ffffff', '#2C3E5D', '#2492AB','#ffffff', '#2C3E5D', '#2492AB','#ffffff', '#2C3E5D', '#2492AB'],
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title {
  font-size: 100px;
  color:#111;
  padding-top:200px
}
.title2 {
  color:#fff;
}
a {
  color: #42b983;
}
ul{
font-size: 50px;
}
ul li{
  padding-bottom: 30px;
}
ul.ul2{
  columns: 2;
  -webkit-columns: 2;
  -moz-columns: 2;
}
ul.ul3{
  columns: 3;
  -webkit-columns: 3;
  -moz-columns: 3;
}
@media only screen and (max-width: 600px) {
.title {
  font-size: 40px;
  padding-top:50px
}
ul{
font-size: 20px;
}
  
}
</style>
