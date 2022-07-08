<script>
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import Card from "../components/Card.svelte";
</script>

<Header />

<div id="index_introduction">
  <h1> Why Green Rush? </h1>
  <div id="index_introduction-content">
    <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. </p>
    <img src="../static/panels.svg" height="400px" alt="Solar Panel Graphic"/>
  </div>
</div>

<div id="index_card-collection">
  <Card link="../../static/recycle.svg" 
        alt="Graphic for Renewables" 
        title="Renewables"
        redirect="true"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        />
  <Card link="../../static/tools.svg" 
        alt="Graphic for Industries" 
        title="Industries"
        redirect="true"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. " 
        />
  <Card link="../../static/person.svg" 
        alt="Graphic for HR" 
        title="HR"
        redirect="true"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium." 
        />
</div>

<div id="index_reference">
  <blockquote><img src="../../static/quote.svg" width="64" /><br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida.
    <br>
    <cite> - Mr. XYZ </cite>
  </blockquote>
  <a href="/references"> More? </a>
</div>

<div id="index_partners">
  <h2> Our Partners </h2>
  <p> Logos of partners will go here. </p>
</div>

<Footer />

<style lang="scss">
  #index_introduction {
    padding: 10px 100px 0px;
    background-color: $lime;
    color: $white;
    margin-bottom: 100px;

    h1 { 
      font-family: FiraMedium;
      font-weight: normal;
      font-size: 40px;
    }

    p {
      font-size: 26px;
      margin-right: 50px;
    }

    #index_introduction-content {
      display: flex;
      justify-content: space-between;
    }
  }

  #index_card-collection {
    padding: 10px 100px 0px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 7%;
  }

  #index_reference {
    margin: 100px 150px 0px;
    font-size: 30px;
    text-align: center;
    font-family: FiraMedium;
    color: $dark-green;

    cite { 
      font-style: normal;
    }

    a { 
      font-size: 30px;
      font-family: Catamaran;
      color: $dark-green;
      text-decoration: $lime wavy underline;
    }
  }

  #index_partners { 
    margin-top: 100px;
    padding-left: 50px;
    padding-right: 50px;
    padding: 5px; 
    font-size: 30px;
    text-align: center;
    background-color: $lime;
    color: $white;
    font-family: FiraMedium;
  }

</style>
