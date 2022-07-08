<footer>
  <div id="footer_main">
    <div id="footer_renewables-items">
      <h2><a href="/renewables"> Renewables  </a></h2>
      <ul>
        <li><a href="/renewables#Solar"> Solar </a></li>
        <li><a href="/renewables#Wind"> Wind </a></li>
        <li><a href="/renewables#Hybrid"> Hybrid </a></li>
        <li><a href="/renewables#Storage"> Storage </a></li>
      </ul>
    </div>
    <div id="footer_industries-items">
      <h2><a href="/industries"> Industries </a></h2>
      <ul>
        <li><a href="/industries#3D-CAD"> 3D CAD </a></li>
        <li><a href="/industries#consulting"> Consulting </a></li>
        <li><a href="/industries#start-ups"> Start-Ups </a></li>
      </ul>
    </div>
    <div id="footer_HR-items">
      <h2><a href="/hr"> HR </a></h2>
      <ul>
        <li><a href="/hr#scout"> Scout </a></li>
        <li><a href="/hr#select"> Select </a></li>
      </ul>
    </div>
    <div>
      <h2><a href="/contact"> Contact </a></h2>
    </div>
  </div>
  <br>
  <p> Green Rush © 2022 </p>
</footer>

<style lang="scss">
  footer {
    background-color: $dark-green;
    text-align: center;

    hr { 
      width: 40%;
    }

    div { 
      padding-left: 50px;
      padding-right: 50px
    }
  }

  #footer_main {
    margin-top: 100px;
    display: flex;
    flex-direction: right;
    justify-content: center;

    h2 { 
      text-decoration: none;
      font-family: FiraMedium;
    }
    
    ul {
      list-style: none;
      padding-inline-start: 0px;

      li {  
        text-align: center;
        font-family: Catamaran;
      }
    }

    a {
      text-decoration: none;
      color: $white;
    }

  }
  

</style>
