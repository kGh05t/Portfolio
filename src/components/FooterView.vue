<template>
  <v-footer>
      <v-card
        elevation="16"
        rounded="0"
        width="100%"
        class="bg-green-400 text-center"
      >
        <v-card-text>
          <v-btn
            class="mx-4"
            icon="fas fa-comment"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-university"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-wifi"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-podcast"
            variant="plain"
            color="white"
          ></v-btn>
        </v-card-text>

        <v-card-text class="text-red">
          @ {{ new Date().getFullYear() }} —
          <strong>ninjahattodi</strong>
        </v-card-text>
      </v-card>
    </v-footer>
</template>

<script>
export default {

}
</script>

<style>
.v-footer {
  padding: 8px 0 !important;
}
</style>