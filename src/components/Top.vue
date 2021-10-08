<template>
  <h1>{{todayDate}}</h1>
  <Button buttonName="Add To Schedule"/>

</template>

<script>

import Button from "./Button"

  export default {
    name: "Top",
    props: {
      todayDate: String, //int or long
    },
    components: {
      Button
    }
  }

</script>