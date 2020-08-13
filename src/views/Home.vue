<template>
  <div class="home">
      <AppBar title="TODO" left="bars" right="search" />
      <Avatar />
      <Gradient />
      <TodoList />
      <TodoDetail />
  </div>
</template>

<script>
// @ is an alias to /src
import AppBar from '../components/AppBar'
import Avatar from '../components/Avatar'
import Gradient from '../components/Gradient'
import TodoList from '../components/TodoList'
import TodoDetail from '../components/TodoDetail'
export default {
  name: 'Home',
  components: {
    AppBar,
    Avatar,
    Gradient,
    TodoList,
    TodoDetail
  }
}
</script>

<style lang="scss">
.home {
    height: 100%;
    width: 100%;
    overflow: hidden;
    color: white;
}
</style>
