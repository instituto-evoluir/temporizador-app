<template>
    <aside>
        <Controls message="lorem ipsum." />
    </aside>
    <section>
        <div id="couter">Contador: <span id="counterValue">1</span></div>
    </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Controls from '@/components/Controls.vue'

export default defineComponent({
    name: 'MadCounter',
    components: {
        Controls
    }
});
</script>

<style scoped>
  p, span {
    font-family: 'Times', Tahoma, Verdana, sans-serif;
  }
  
  h1 { font-weight: bolder; }
  footer { font-size: 8px; }
  .xurupitas { color: red; }
</style>