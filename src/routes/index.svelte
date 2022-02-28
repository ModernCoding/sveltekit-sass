<div class="box">
  <h1 class="title">
    Hello World
  </h1>
</div>


<style type="text/css" lang="sass">

  @use "sass:math"

  :global(body)
    margin: 0
    display: flex
    align-items: center
    justify-content: center
    min-height: 100vh

  :global(h1)
    margin: 0

  $phi: (2 * math.sin(54deg))
  
  .box
    background: red
    height: calc(100vh / $phi)
    width: calc(100% / $phi)
    display: flex
    align-items: center
    justify-content: center

    > h1
      color: white

</style>