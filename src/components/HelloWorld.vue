<template>
  <h2>
    {{ msg }}
    <EventCard />
  </h2>
</template>

<script>
import EventCard from "./EventCard";
export default {
  name: "HelloWorld",
  components: EventCard,
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
