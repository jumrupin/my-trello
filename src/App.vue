<template>
  <div id="app">
    <board />
  </div>
</template>

<script>
// improt文を追加
import Board from './components/Board.vue'

export default {
  name: 'App',
  components: {
    // コンポーネントに登録
    Board
  }
}
</script>
