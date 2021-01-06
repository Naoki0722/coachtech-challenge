<template>
  <div class="main-card">
    <div class="main-card-img">
      <img src="../assets/3014.jpg">
      <div>
        <p>カテゴリー</p>
      </div>
    </div>
    <div class="main-card-text">
      <h2>サンプルタイトルがここに入ります。</h2>
      <div class="main-card-text-sub">
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
.main-card {
  width: 550px;
  margin: 30px auto;
  display: flex;
  
}

.main-card-img {
  position: relative;
}

.main-card-img img {
  height: 150px;
}

.main-card-img p {
  position: absolute;
  bottom: 0;
  background-color: rgb(70, 70, 70);
  color: white;
  padding: 5px 10px 5px 5px;
}

.main-card-text {
  background-color: white;
  height: 150px;
  width: 300px;
}

.main-card-text h2 {
  padding: 30px 20px ;
  font-size: 1.2rem;
}


.main-card-text-sub {
  display: flex;
  justify-content: space-between;
  align-items: end;
  padding: 20px;
  align-items: center;
}

.main-card-text-sub p {
  font-size: 0.7rem;
}

.subtext-border { 
  border: 1px solid rgb(168, 167, 167);
  padding: 5px;
}
</style>