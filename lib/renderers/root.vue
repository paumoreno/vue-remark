<template>
  <fragment>
    <slot></slot>
  </fragment>
</template>

<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";
import { Fragment } from 'vue-fragment'

@Component({
  name: "vue-remark-root",
  components: {Fragment}
})
export default class VueRemarkRoot extends Vue {}
</script>
