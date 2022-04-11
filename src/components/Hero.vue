<template>
  <div class="jumbotron">
    <img src="https://ftw.usatoday.com/wp-content/uploads/sites/90/2020/01/usp-nba_-charlotte-hornets-at-portland-trail-blaze-e1579881454694.jpg?w=1000&h=600&crop=1">
    <h2>il mio primo jumbotron con CLI!</h2>
  </div>
</template>



<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>



<style scoped>

.jumbotron {
    width: 100%;
    height: 500px;
    background-color: aqua;
}

img {
    width: 500px;
}

</style>