<template>
  <div class="container-fluid">
    <div class="row">
    <Theheader />
      <logo class="sitelogo">
        <img class="" src="https://cdn.siriushd.net/logo%20animeFM.png" width="50%" alt="AnimeFM">
      </logo>
      <main class="main-content">
          <nuxt />
       </main>
    </div>
  </div>
</template>

<script>
import Theheader from '@/components/Theheader/Theheader'
export default {
  components: {
    Theheader
  }  
}
</script>


<style>
* {
  box-sizing: border-box;
}
.main-content {
  margin-top: 4.5rem;
}
.sitelogo {
  margin-top: 1.8rem;
}
</style>