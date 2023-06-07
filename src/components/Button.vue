<template>
    <div>
    <button @click="onclick()" class="btn" :style="{backgroundColor:color}">{{ text }}</button>
  </div>
</template>
 
<script>
export default {
    name: 'Button',
    props: {
        text: String,
        color: String
    },
    methods: {
        onclick() {
            console.log('click');
        }
    } 
    

}
</script>

<style>

</style>