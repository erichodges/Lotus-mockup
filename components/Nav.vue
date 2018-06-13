<template>
  <vue-headroom>
      <ul class="ul-nav">
        <li class="li-logo">
          <img src="~/assets/images/lotus-logo.png" alt=" Logo" class="logo">
        </li>

        <a class="a" href="#" v-popover="{name:'ccc', event: 'hover', width:100}">
        <li class="li-user-nav" >Popover</li></a>
        <no-ssr>
          <popover name="ccc" event="hover" width=100>            
            <div>Evora</div>
            <div>3-Eleven</div>            
          </popover>
        </no-ssr>

        <a class="a" href="#" v-scroll-to="'#section-2'">
        <li class="li-user-nav">Models</li></a>
        <a class="a" href="#" v-scroll-to="'#section-3'">
        <li class="li-user-nav">About</li></a>
        <a class="a" href="#" v-scroll-to="'#section-4'">
        <li class="li-user-nav">Contact</li></a>        
        <li class="nav-spacer-right"> </li>
      </ul>
        

      </vue-headroom>

      
</template>

<script>

</script>

<style lang="scss">
 
</style>

