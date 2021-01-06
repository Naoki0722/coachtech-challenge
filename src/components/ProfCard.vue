<template>
  <div class="prof-card">
    <h2>Profile</h2>
    <img src="../assets/proficon.jpg">
    <h3>Taro Yamada</h3>
    <p>自己紹介が入ります。自己紹介が入ります。自己紹介が入ります。</p>
    <botton class="prof-botton">View more</botton>
  </div>
</template>

<style scoped>
.prof-card {
  position: relative;
  width: 80%;
  margin: 0 auto 40px;
  background-color: white;
  text-align: center;
  box-shadow: 0 2px 5px #ccc;
}

.prof-card h2 {
  position: absolute;
  margin: auto;
  left: 0;
  right: 0;
  top: -2%;
}

.prof-card h3 {
  margin: 20px 0;
}

.prof-card p {
  padding: 20px;
  color: gray;
}

.prof-card img {
  margin: 20px 0 0;
  height: 150px;
  width: 150px;
  border-radius: 50%;
}

.prof-botton {
  display: inline-block;
  box-shadow: 0 10px 25px 0 rgba(0, 0, 0, .5);
  padding: 15px 30px;
  margin: 10px 0 50px 0;
  border: 1px solid black;
  border-radius: 30px;
  background-color: white;
}
</style>