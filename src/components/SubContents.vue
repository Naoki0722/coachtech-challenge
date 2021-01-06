<template>
  <div class="sub-contents">
    <ProfCard />
    <h2>タグ</h2>
    <div class="tag-area-1">
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
    </div>
    <div class="tag-area-1">
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
    </div>
    <div class="tag-area-1">
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
    </div>
    <h2>人気ランキング</h2>
    <SideCard />
    <SideCard />
    <SideCard />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import ProfCard from '../components/ProfCard.vue';
import SideCard from '../components/SideCard.vue';

@Component({
  components: {
    ProfCard,
    SideCard
  }
})
export default class Article extends Vue {
}
</script>


<style scoped>
.botton-area-1 {
  background-color: white;
  padding: 5px;
  margin: 10px;
  font-size: 0.5rem;
  text-align: center;
  border: 1px solid black;
}

.botton-area-1 img {
  width: 15px;
}

.tag-area-1 {
  display: flex;
  justify-content: center;
}

.sub-contents h2 {
  padding-left: 40px;
  margin-top: 20px;
}
</style>