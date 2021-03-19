<template>
  <h1>this is home component</h1>
  {{a}}
  <button @click="handleClick">Click me</button>
</template>

<script>
export default {
  name: 'Home',
  setup(){
    const a="salman";
    const handleClick=()=>{
      console.log("clicked");
    }
    return{a, handleClick}
  }
}
</script>
