<template>
  <button @click="onClick()">
    {{buttonName}}
  </button>
</template>

<script>
  export default {
    name: "Button",
    props: {
      buttonName: String,
    },
    methods:{
      onClick(){
        console.log('clicked')
      }
    }
  }

</script>