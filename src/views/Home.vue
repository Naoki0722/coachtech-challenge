<template>
  <div class="home">
    <Header />
    <FirstView />
    <div class="second-contents">
      <div class="main">
        <div class="card-area">
          <div class="heading-main">
            <p>New Article</p>
          </div>
          <MainCardSub />
          <MainCardSub />
          <MainCardSub />
        </div>
        <div class="third-contents">
          <div class="card-area-2">
            <MainCardRed />
            <div class="heading-main2">
              <p>Programing</p>
            </div>
          </div>
          <div class="card-area-2">
            <div class="heading-main2">
              <p>Design</p>
            </div>
            <MainCardRed />
          </div>
          <div class="card-area-2">
            <MainCardRed />
            <div class="heading-main2">
              <p>Marketing</p>
            </div>
          </div>
        </div>
      </div>
      <SubContents />
    </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Header from '../components/Header.vue';
import MainCard from '../components/MainCard.vue';
import MainCardSub from '../components/MainCardSub.vue';
import HeadingArea from '../components/HeadingArea.vue';
import HeadingAreaSub from '../components/HeadingAreaSub.vue';
import BottonTag from '../components/BottonTag.vue';
import MainCardRed from '../components/MainCardRed.vue';
import ProfCard from '../components/ProfCard.vue';
import Table from '../components/Table.vue';
import FirstView from '../components/FirstView.vue';
import Footer from '../components/Footer.vue';
import SubContents from '../components/SubContents.vue';


@Component({
  components: {
    Header,
    MainCard,
    MainCardSub,
    HeadingArea,
    HeadingAreaSub,
    BottonTag,
    MainCardRed,
    ProfCard,
    Table,
    FirstView,
    Footer,
    SubContents
  }
})
export default class Home extends Vue {
  icon = '🔍キーワードを検索してください';
}
</script>


<style scoped>

.second-contents {
  display: flex;
  justify-content: center;
  margin: 40px 0;
}

.main {
  width: 100%;
}
.card-area {
  display: flex;
  justify-content: space-around;
}

.heading-main {
  writing-mode: vertical-rl;
  font-size: 2.5rem;
  font-weight: bold;
}

.third-contents {
  background-color: rgb(218, 218, 218);
  padding: 30px 0;
  margin-top: 40px;
  width: 100%;
}

.card-area-2 {
  display: flex;
  /* justify-content: center; */
  margin-top: 50px;
}

.heading-main2 {
  writing-mode: vertical-rl;
  font-size: 2.5rem;
  font-weight: bold;
  display: inline;
}
</style>