<template>
    <aside>
        <Controls />
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
  body {
    font-family: 'Times', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  footer { font-size: 8px; }
  .xurupitas { color: red; }
</style>