<template>
  <div class="container">
    <Top todayDate="Oct 8th, 2021"/>
    <Bookings v-bind:bookings="bookings"/>
  </div>
</template>

<script>
  import Top from "./components/Top";
  import bookingsList from './bookings.json'
  import Bookings from './components/Bookings'


  export default {
    name: "App",
    components: {
      Top,
      Bookings
    },
    data() {
      return {
        bookings: [bookingsList]
      }
    },
    // posted() {
    //   this.bookings = bookingsList
    // }
  }
</script>