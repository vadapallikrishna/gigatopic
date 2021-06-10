<template>
    <div class="card">
  <div class="card-content">
    <p class="title">
      “There are two hard things in computer science: cache invalidation,
      naming things, and off-by-one errors.”
    </p>
    <p class="subtitle">
      Jeff Atwood
    </p>
  </div>
  <footer class="card-footer">
    <p class="card-footer-item">
      <span>
        Expand
      </span>
    </p>
    <p class="card-footer-item">
      <span>
        Share on <a href="#">Facebook</a>
      </span>
    </p>
  </footer>
</div>
</template>
<script>
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class InfoCard extends Vue {

}
</script>
