<script lang="ts">
import { useRouter } from 'vue-router';
import { defineComponent } from 'vue';

export default defineComponent({
  props: {
    name: String,
  },

  setup() {
    const router = useRouter();
    const back = () => router.push('/');

    return { back };
  },
});
</script>

<template>
  <p>hi {{ name }}</p>
  <button @click="back">go back</button>
</template>
