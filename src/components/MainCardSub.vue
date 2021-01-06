<template>
  <div class="main-card-sub">
    <div class="main-card-sub-img">
      <img src="../assets/3014.jpg">
      <div>
        <p>カテゴリー</p>
      </div>
    </div>
    <div class="main-card-sub-text">
      <h2>サンプルタイトルがここに入ります。</h2>
      <h3>サブタイトル</h3>
      <div class="main-card-sub-text-sub">
        <p>2021/01/01</p>
        <p class="subtext-border"><font-awesome-icon icon="tags" />タグデザイン</p>
      </div>
    </div>
  </div>
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
export default Vue.extend({
  
})
</script>


<style scoped>
.main-card-sub {
  width: 300px;
  height: 400px;
  margin: 0 40px 0 0 ;
  box-shadow: 0 5px 3px #ccc;
}

.main-card-sub-img {
  position: relative;
}

.main-card-sub-img img {
  width: 300px;
}

.main-card-sub-img p {
  position: absolute;
  bottom: 0;
  background-color: rgb(70, 70, 70);
  color: white;
  padding: 5px 10px 5px 5px;
}

.main-card-sub-text {
  background-color: white;
}

.main-card-sub-text h2,
.main-card-sub-text h3 {
  padding: 15px 10px 10px;
}

.main-card-sub-text h3 {
  color: gray;
}

.main-card-sub-text-sub {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  align-items: center;
}

.main-card-sub-text-sub p {
  font-size: 0.7rem;
}

.subtext-border { 
  border: 1px solid rgb(168, 167, 167);
  padding: 5px;
}
</style>