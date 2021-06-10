<template>
  <div class="home">
    <h1>Topics for today</h1>
    <Topics/>
    <h2>Examples</h2>
    <HomePageExamples/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Topics from '../components/Topics.vue';
import HomePageExamples from '../components/HomePageExamples.vue';

@Component({
  components: {
    Topics,
    HomePageExamples,
  },
})
export default class Home extends Vue {}
</script>
