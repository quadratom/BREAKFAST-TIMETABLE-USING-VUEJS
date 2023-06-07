<template>
  <header>
    <h1>{{ title }}</h1>
    <Button text="Add Record" color="green" />
    <!-- <Button text="Update Record" color="yellow" />
    <Button text="Delete Record" color="red" /> -->

  </header>
</template>

<script>
import Button from './Button.vue';

export default {
    name: 'Header',
    components: { Button },
    props: {
        title: String,
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