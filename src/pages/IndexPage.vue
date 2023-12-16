<template>
  <q-page class="flex column flex-center">
    <p>Patients</p>
    <div class="flex">
      <ExampleCard />
      <ExampleCard />
      <ExampleCard />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';
import ExampleCard from 'src/components/ExampleCard.vue';
export default defineComponent({
  name: 'IndexPage',
  components: { ExampleCard }
})
</script>
