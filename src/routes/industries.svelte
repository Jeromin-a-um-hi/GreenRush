 <script>
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import Card from "../components/Card.svelte";
</script>

<Header /> 
<div id="industries_card-collection">
  <Card link="../../static/pencil-fill.svg" 
        alt="Graphic for 3D CAD" 
        title="3D CAD"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="3D CAD."
        fontSize="27px"
  />
  <Card link="../../static/patch-question-fill.svg" 
        alt="Graphic for Consulting" 
        title="Consulting"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Consulting."
        fontSize="27px"
  />
  <Card link="../../static/caret-up-square-fill.svg" 
        alt="Graphic for Hybrid" 
        title="Start-Ups"
        redirect="false"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum iaculis eu non diam phasellus vestibulum lorem. Iaculis urna id volutpat lacus laoreet non curabitur gravida. Magna sit amet purus gravida quis blandit turpis. Maecenas accumsan lacus vel facilisis. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Ut venenatis tellus in metus vulputate eu scelerisque felis. Aliquam eleifend mi in nulla posuere sollicitudin aliquam. Id faucibus nisl tincidunt eget nullam non nisi est sit. Donec ac odio tempor orci. Elementum tempus egestas sed sed risus pretium. "
        img="../../static/placeholder.jpeg"
        imgAlt="Start-ups."
        fontSize="27px"
  />
</div>
<Footer />

<style lang="scss">
  #industries_card-collection { 
    padding: 10px 100px 0px;
    display: grid;
    grid-template-columns: 1fr;
    gap: 100px;

    #card_text { 
      font-size: 30px !important;
    }        
  }
</style>
