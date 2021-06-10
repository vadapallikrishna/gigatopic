<template>
    <div>
        <h1>New Post</h1>
        <textarea class="textarea"></textarea>
        <b-button type="is-primary is-light">Submit</b-button>
    </div>
</template>
<style lang="scss">
    .textarea {
        width: 400px;
        height:500px;
        margin: 10px;
    }
</style>
<script>
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class NewPost extends Vue {

}
</script>
