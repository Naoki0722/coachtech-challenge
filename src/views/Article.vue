<template>
  <div class="article">
    <Header />
    <p class="top">トップ>記事</p>
    <div class="contents">
      <div class="main">
        <h1>ここにサンプルタイトルh1が入ります。ここにサンプルタイトルh1が入ります</h1>
        <div class="main-card-img">
          <img src="../assets/bridal_6.jpg" alt="アイキャッチ画像">
          <div>
            <p>カテゴリー</p>
          </div>
        </div>
        <HeadingAreaSub />
        <div class="main-contents">
          <h2>サンプルタイトルh2</h2>
          <p>本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。</p>
          <h3>サンプルタイトルh3</h3>
          <p>本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。</p>
          <div class="main-contents-h4">
            <div class="main-contents-h4-color">
            </div>
            <div class="main-contents-h4-contents">
              <h4>サンプルタイトルh4</h4>
            </div>
          </div>
          <p>本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。本文のテキストが入ります。</p>
        </div>
        <Table />
      </div>
      <SubContents />
    </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Header from '../components/Header.vue';
import ProfCard from '../components/ProfCard.vue';
import HeadingAreaSub from '../components/HeadingAreaSub.vue';
import Table from '../components/Table.vue';
import Footer from '../components/Footer.vue';
import SubContents from '../components/SubContents.vue';

@Component({
  components: {
    Header,
    ProfCard,
    HeadingAreaSub,
    Table,
    Footer,
    SubContents
  }
})
export default class Article extends Vue {
}
</script>

<style scoped>
.top {
  background-color: rgb(209, 209, 209);
  padding: 10px 20px;
}

.contents {
  margin-top: 100px;
  display: flex;
  justify-content: center;
}

.main {
  width: 100%;
}

.main h1 {
  width: 85%;
  margin: 0 auto;
  font-size: 2.5rem;
  font-weight: normal;
  line-height: 3rem;
}

.main-card-img {
  width: 80%;
  text-align: center;
  margin: 30px auto;
  position: relative;
}

.main-card-img p {
  position: absolute;
  bottom: 0.5%;
  background-color: rgb(70, 70, 70);
  color: white;
  padding: 5px 10px 5px 5px;
}

.main-card-img img {
  width: 100%;
  object-fit: cover;
  text-align: center;
}

.main-contents {
  width: 80%;
  margin: 0 auto;
}

.main-contents h2 {
  padding: 15px 0 15px 10px;
  border-top: 2px solid black;
  border-bottom: 2px solid black;
  font-size: 1.3rem;
}

.main-contents p {
  margin: 30px 0 70px;
  line-height: 35px;
}

.main-contents h3 {
  background-color: gray;
  padding: 15px 0 15px 10px;
  font-size: 1.3rem;
}

.main-contents-h4 {
  position: relative;
}

.main-contents-h4-color {
  position: absolute;
  top: 0;
  bottom: 0;
  background-color: gray;
  width: 30px;
}

.main-contents-h4-contents {
  position: relative;
  padding: 15px 0 15px 10px;
  font-size: 1.3rem;
}
</style>