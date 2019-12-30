<template>
  <div class="l-wrapper">
    <header class="l-header">
      <h1>サイト名</h1>
    </header>
    <div class="l-content">
      <Ranking></Ranking>
    </div>
    <footer class="l-footer">
      <p>© コピーライト</p>
    </footer>
  </div>
</template>

<script>
  import Ranking from './components/Ranking.vue'
export default {
  name: 'app',
  components:{
    Ranking
  }
}
</script>

<style>
.l-wrapper {
  padding:0;
}
</style>
