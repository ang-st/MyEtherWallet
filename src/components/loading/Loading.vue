<template>
  <div class="mew-component--loading">
    <v-dialog v-model="dialog" hide-overlay persistent width="300">
      <v-card color="primary" dark>
        <v-card-text>
          Please stand by
          <v-progress-linear
            indeterminate
            color="white"
            class="mb-0"
          ></v-progress-linear>
        </v-card-text>
      </v-card>
    </v-dialog>
  </div>
</template>

<script>
export default {
  name: 'Loading',
  components: {},
  data: function () {
    return {
      dialog: true
    };
  }
};
</script>

<style lang="scss" scoped></style>
