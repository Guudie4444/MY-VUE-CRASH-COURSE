<template>
    <header>
        <h1>{{ title }}</h1>
        <Button text="Add Task" Task color="green" />
    </header>
    <button>

    </button>
</template>

<script>

import Button from './Button'


export default {
  name: 'Header',
  props: {
    title: String,
    },

  components: {
    Button
  }
}
</script>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}
</style>