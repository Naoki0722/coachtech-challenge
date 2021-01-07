<template>
  <div class="card-section">
    <div class="main-card-sub">
      <div class="main-card-sub-img">
        <img src="../assets/bridal_3.jpg" alt="メインカード画像-1">
      </div>
      <div class="main-card-sub-text">
        <h2>タイトルが入ります。タイトルが入ります。タイトルが入ります。</h2>
        <div class="main-card-sub-text-sub">
          <p>2021/01/01</p>
        </div>
      </div>
    </div>
    <div class="main-card-sub">
      <div class="main-card-sub-img">
        <img src="../assets/3014.jpg" alt="メインカード画像-1">
      </div>
      <div class="main-card-sub-text">
        <h2>タイトルが入ります。タイトルが入ります。タイトルが入ります。</h2>
        <div class="main-card-sub-text-sub">
          <p>2021/01/01</p>
        </div>
      </div>
    </div>
    <div class="main-card-sub">
      <div class="main-card-sub-img">
        <img src="../assets/maincard3.jpg" alt="メインカード画像-1">
      </div>
      <div class="main-card-sub-text">
        <h2>タイトルが入ります。タイトルが入ります。タイトルが入ります。</h2>
        <div class="main-card-sub-text-sub">
          <p>2021/01/01</p>
        </div>
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
.card-section {
  display: flex;
  justify-content: center;
}
.main-card-sub {
  width: 100%;
  margin: 0 20px;
  background-color: white;
  border-radius: 20px;
  box-shadow: 0 1px 1px #ccc;
}

.main-card-sub-img {
  position: relative;
}

.main-card-sub-img img {
  border-radius: 20px;
  width: 100%;
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
  border-radius: 20px;
}

.main-card-sub-text h2,
.main-card-sub-text h3 {
  padding: 15px 10px 10px;
}

.main-card-sub-text h3 {
  color: gray;
}

.main-card-sub-text-sub {
  padding: 20px;
  text-align: right;
  color: gray;
}

.main-card-sub-text-sub p {
  font-size: 0.7rem;
}

.subtext-border { 
  border: 1px solid rgb(168, 167, 167);
  padding: 5px;
}
</style>