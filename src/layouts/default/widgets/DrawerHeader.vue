<template>
  <v-list-item class="mb-0 justify-space-between pl-3">
    <v-img
      src="../../../../src/assets/logo.png"
      contain
      max-width="50"
    />

    <v-list-item-content class="pl-2">
      <v-list-item-title class="text-h3">
        <strong class="mr-1 font-weight-black">EasyCloud</strong>
      </v-list-item-title>
    </v-list-item-content>
  </v-list-item>
</template>

<script>
  // Utilities
  import { get } from 'vuex-pathify'

  export default {
    name: 'DefaultDrawerHeader',

    computed: { version: get('app/version') },
  }
</script>
