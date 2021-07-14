<template>
  <div v-frag>
    <slot></slot>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";
import frag from 'vue-frag';

@Component({
  name: "vue-remark-root",
  directives: {
        frag
    },
})
export default class VueRemarkRoot extends Vue {}
</script>
