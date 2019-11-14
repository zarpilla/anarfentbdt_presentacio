<template>
  <div>    
    <full-page :options="options">      
      <div class="section">
        <div class="title">          
          QUè FEM
          <br>AMB EL NOSTRE
          <br>TEMPS?
          
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          FEm útil
          <br>El NOstrE
          <br>tEmps!
          
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          ANar FENt
          <br>
          BaNC dEL tEmps dEl RipOllès
          <br>
          <div class="small-font">
            www.aNarfENtbdt.Cat
            <br>
            HOla@aNarfENtbdt.Cat
          </div>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          QUe és UN BaNC dEL tEmps
          <ul class="ul">
            <li>Xarxa dE sUpOrt mUtU</li>
            <li>INtErCaNvi dE sErvEis, CONEixEmENts, tasqUEs</li>
            <li>SENsE diNErs</li>
          </ul>
          
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          MONEda = TEmps
        </div>        
        
      </div>
      <div class="section">
        <div class="title title2">
          ValOrs
          <ul class="ul">
            <li>iNtEgraCió sOCial</li>
            <li>rElaCiONs iNtErgENEraCiONals i iNtErCUltUrals</li>
            <li>rElaCiONs vEïNals</li>
            <li>aUtOEstima</li>
            <li>CONEixENça, igUaltat, CONfiaNça i COOpEraCIó</li>
            <li>CONCiliaCió dE la vida pErsONal, familiar i labOral</li>
          </ul>
          
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          COm NEix El baNC dEl tEmps dEl RipOllès
          <ul class="ul">
            <li>XES RipOllès</li>            
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          QUi pOt fOrmar part dEl BaNC
          <ul class="ul">
            <li>PErsONEs majOrs dE 18 aNys</li>
            <li>ENtitats</li>
            <li>COl·lECtiUs</li>
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          COm fOrmar part dEl BaNC
          <ul class="ul">
            <li>FORMULARI DE <a href="https://docs.google.com/forms/d/1kyGJJOlIzL1ftFsfc8FigTECDBRI2murhsnUDvfVk-E" target="_blank">PREINSCRIPCIó</a></li>
            <li>ENtrEvista pErsONal</li>
            <li>ApliCaCió wEb <a href="https://www.timeoverflow.org/" target="_blank">TIMEOVERFLOW</a></li>
          </ul>
        </div>        
      </div>
      <div class="section">
        <div class="title title">
          TIMEOVERFLOW
          <ul class="ul">
            <li>MEMBRES</li>
            <li><a href="https://www.timeoverflow.org/offers?org=266" target="_blank">OFERTES</a></li>
            <li><a href="https://www.timeoverflow.org/inquiries?org=266" target="_blank">DEMANDES</a></li>
            <li>CONTACTE DIRECTE ENTRE MEMBRES</li>
            <li>TRANSFERèNCIA DE TEMPS</li>
          </ul>
        </div>        
      </div>         
      <div class="section">
        <div class="title title2">
          COM HI PODEN PARTICIPAR LES ENTITATS
          <ul class="ul">
            <li>OFERTES I DEMANDES</li>
            <li>COMPTE SOLIDARI</li>            
          </ul>
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          TALLERS
          <ul class="ul">
            <li>OFERTA O DEMANDA GRUPAL</li>
            <li>PROMOGUTS DES DEL BANC DEL TEMPS</li>
            <li>PROMOGUTS DES DE LES PERSONES MEMBRES</li>
          </ul>
          
        </div>        
      </div>      
      <div class="section">
        <div class="title title">
          QUINS INTERCANVIS PUC FER
          <ul class="ul3">
          <li>ART I ARTESANIA</li>
          <li>ASSESSORAMENT I ORIENTACIó GENERAL</li>
          <li>COMPRES I COMERÇ</li>
          <li>CUINA</li>
          <li>CULTURA</li>
          <li>CURA D’ANIMALS</li>
          <li>ENSENYAMENT</li>
          <li>ESPORTS I ANIMACIó</li>
          <li>IDIOMES</li>
          <li>INFORMÀTICA I ALTRES TECNOLOGIES</li>
          <li>LLEURE I ENTRETENIMENT</li>
          <li>OBRA I CONSTRUCCIó</li>
          <li>SALUT I CURA DE PERSONES</li>
          <li>SERVEI TèCNIC</li>
          <li>SERVEIS A LA COMUNITAT</li>
          <li>TERÀPIES ALTERNATIVES</li>
          <li>TRANSPORT</li>
          <li>TREBALLS DE JARDINERIA</li>
          <li>TREBALLS DE LA LLAR</li>
          </ul>
          
        </div>        
      </div>
      <div class="section">
        <div class="title title2">
          NORMES DE CONDUCTA
          <ul class="ul">
            <li>RESPECTE</li>
            <li>PRIVACITAT DE DADES</li>            
          </ul>
        </div>        
      </div>      
      <div class="section">
        <div class="title title2">
          DUBTES?          
        </div>       
      </div>       
      <div class="section">
        <div class="title title">
          FINS AVIAT!!!
          <br>
          <br>
          <div class="small-font">
          ANar FENt, BaNC dEL tEmps dEl RipOllès
          <br><br>
          www.aNarfENtbdt.Cat
          <br>
          HOLA@aNarfENtbdt.Cat
          </div>
          
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
.fp-tableCell{
  /* display: block!important; */
}
.title {
  font-size: 100px;
  color:#111;  
}
.title2 {
  color:#fff;
}
.small-font{
  font-size: 46px;
}
a {
  color: #42b983;
}
ul{
font-size: 46px;
}
ul li{
  padding-bottom: 20px;
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
}
ul{
font-size: 20px;
}
  
}
</style>
