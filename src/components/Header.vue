<template>
  <header class="header">
    <h1>{{title}}</h1>
    <ul>
      <li class="list__item">1</li>
      <li class="list__item">2</li>
    </ul>
  </header>
</template>

<script>
export default {
  data(){
    return{
      title:'Header'
    }
  }

}

</script>

<style lang="scss">
@import '../assets/scss/_mixins.scss';

.list{
  list-style: none;
  padding: 0;
  margin: 0;

    @include e('item'){
      background: skyblue;
      color: #222;
      padding: 10px 20px;
      display: inline-block;
   }
}

</style>
