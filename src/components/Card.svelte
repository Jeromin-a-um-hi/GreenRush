<script>
  export let link;
  export let alt;
  export let title;
  export let redirect;
  export let text;
  export let img;
  export let imgAlt;
  export let fontSize = "24px";
</script>

<div style="--font-size: {fontSize}">
  <h1 id="{title}"><img id="card_graphic" width="32" src={link} alt={alt} /> {title} </h1>
  <span id="card_body">
    <span>
      <p id="card_text"> {text} </p>
      {#if redirect === "true"}
        <button><a href="/{title.toLowerCase()}"> Show More </a></button>
      {/if}
    </span>
    {#if img && imgAlt}
    <img src="{img}" alt="{imgAlt}" width="400px"/>
    {/if}
  </span>
</div>

<style lang="scss">

  div {
    width: auto;
    background-color: $lime;
    padding: 20px;

    #card_body {
      display: flex;
      flex-direction: right;
      
      img { 
        padding-left: 50px;
        padding-right: 30px;
        padding-bottom: 30px
      }
    }

    #card_graphic {
      color: $white;
      filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(136deg) brightness(105%) contrast(103%);
    }

    #card_text {
      font-size: var(--font-size);
    }

    a { 
      font-size: var(--font-size);
      font-family: Catamaran;
      color: $white;
      text-decoration: none;
    }
  }

</style>
