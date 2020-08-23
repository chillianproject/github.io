<template>
  <div class="apps">
    <h1>Apps</h1>
    <div>
      <Decision />
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Decision from "@/components/Decision.vue";

@Component
export default class Apps extends Vue {}
</script>
