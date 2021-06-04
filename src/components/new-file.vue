<template>

</template>

<script lang="ts">
import {defineComponent, PropType} from "vue";

interface ISampleProp {
  field1: number;
  field2: boolean;
}

export default defineComponent({
  props: {
    sample: Object as PropType<ISampleProp>
  },
  setup(props, ctx) {
    return {};
  },
});
</script>

<style lang="scss">

</style>
