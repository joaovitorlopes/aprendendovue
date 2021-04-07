<template>
  <b-container>
    <b-row align-v="center">
      <Card></Card>
    </b-row>
  </b-container>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue';

export default {
  name: 'Home',
  components: {
    Card
  }
}
</script>
