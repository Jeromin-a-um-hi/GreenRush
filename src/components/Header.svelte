<header>
  <a href="/">
    <img src="../../static/Greenrush-with-text.svg" alt="Logo" width="128" height="92" />
  </a>

  <!-- Left Aligned -->

  <ul id="header_left-aligned">
    <li><a href="/renewables"> Renewables </a></li>
    <li><a href="/industries"> Industries </a></li>
    <li><a href="/hr"> HR </a></li>
  </ul>

  <!-- Right Aligned -->

  <ul id="header_right-aligned">
    <li><a href="/about"> About </a></li>
    <li><a href="/references"> References </a></li>
    <li><button><a href="/contact" id="header_contact-text"> Contact </a></button></li>
  </ul>

</header>

<style lang="scss">
  
header {
  margin: 10px 100px 10px;
  display: flex;
  width: auto;
  font-family: Catamaran, Cambria;

  ul { 
    list-style: none;
    padding-inline-start: 0px;
  }

  a { 
    text-decoration: none;
    color: $dark-green;
    font-size: 24px;
  }

  #header_contact-text { 
    color: $white;
  }

  #header_left-aligned {
    display: flex;
    margin-right: auto;

    li {
      margin-left: 40px;
      transform: translateY(30%);
    }
  }
    
  #header_right-aligned {
    display: flex;
      
    li {
      margin-left: 40px;
      transform: translateY(30%);
    }
  }
}

</style>
