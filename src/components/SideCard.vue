<template>
  <div class="main-card">
    <div class="main-card-img">
      <img src="../assets/3014.jpg">
      <div>
        <p class="number">1</p>
        <p class="category">カテゴリー</p>
      </div>
    </div>
    <div class="main-card-text">
      <h2>サンプルタイトルがここに入ります。</h2>
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
  width: 80%;
  margin: 30px auto;
  display: flex;
  
}

.main-card-img {
  position: relative;
}

.main-card-img img {
  height: 100px;
  object-fit: cover;
}


.number {
  position: absolute;
  left: 0;
  top: 0;
  text-align: center;
  background-color: rgb(187, 162, 21);
  color: black;
  padding: 5px 10px 5px 5px;
  font-size: 1rem;
}

.category {
  position: absolute;
  right: 0;
  bottom: 3%;
  background-color: rgb(70, 70, 70);
  color: white;
  padding: 5px 10px 5px 5px;
  font-size: 0.7rem;
}

.main-card-text {
  background-color: white;
  height: 100px;
  border: 1px solid rgb(201, 201, 201);
}

.main-card-text h2 {
  line-height: 30px;
  padding: 20px 10px 30px;
  font-size: 0.9rem;
}
</style>