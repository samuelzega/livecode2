<template>
  <b-card :img-src="data.poster" img-alt="Card image" img-left class="mb-3">
    <h1>{{ data.title }}</h1>
    <h4>{{ data.year }}</h4>
    <b-card-text>Type: {{ data.type }}</b-card-text>
    <router-link :to="`/details/${data.id}`">Details</router-link>
  </b-card>
</template>

<script>
export default {
  name: 'ItemCard',
  props: ['data']
}
</script>

<style></style>
