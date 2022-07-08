<script>
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import Card from "../components/Card.svelte";
</script>

<Header /> 
<div id="renewables_card-collection">
  <Card link="../../static/sun-fill.svg" 
        alt="Graphic for Solar" 
        title="Solar"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Hybrid energy."
        fontSize="27px"
  />
  <Card link="../../static/wind.svg" 
        alt="Graphic for Wind" 
        title="Wind"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Hybrid energy."
        fontSize="27px"
  />
  <Card link="../../static/lightning-charge-fill.svg" 
        alt="Graphic for Hybrid" 
        title="Hybrid"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Hybrid energy."
        fontSize="27px"
  />
  <Card link="../../static/battery-full.svg" 
        alt="Graphic for Storage" 
        title="Storage"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Storage devices."
        fontSize="27px"
  />
</div>
<Footer />

<style lang="scss">
  #renewables_card-collection { 
    padding: 10px 100px 0px;
    display: grid;
    grid-template-columns: 1fr;
    gap: 100px;

    #card_text { 
      font-size: 30px !important;
    }        
  }
</style>
