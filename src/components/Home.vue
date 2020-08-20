<template>
  <v-container>
    <v-row class="text-center">
      <p>{{ msg }}</p>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Home",
  props: ['msg'],
  data: () => ({

  })
};
</script>
