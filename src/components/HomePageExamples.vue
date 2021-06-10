<template>
    <b-tabs v-model="activeTab">
        <b-tab-item label="Limits">
            <InfoCard/>
            <InfoCard/>
            <InfoCard/>
        </b-tab-item>

        <b-tab-item label="Derivates">
            <InfoCard/>
            <InfoCard/>
            <InfoCard/>
        </b-tab-item>
        <b-tab-item label="Trignometry">
            <InfoCard/>
            <InfoCard/>
            <InfoCard/>
        </b-tab-item>

        <b-tab-item label="Videos" disabled>

        </b-tab-item>
    </b-tabs>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';
import InfoCard from './InfoCard.vue';

@Component({
  components: {
    InfoCard,
  },
})
export default class HomePageExamples extends Vue {

}
</script>
