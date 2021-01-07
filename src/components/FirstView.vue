<template>
  <div class="first-view">
    <div class="main-area">
      <img src="../assets/bridal_1.jpg" alt="ファーストビュー画像">
      <div class="main-contents">
        <h2>記事タイトルが入ります。記事タイトルが入ります。</h2>
        <div class="tag-area">
          <p>20201/01/01</p>
          <p class="tag-icon"><font-awesome-icon icon="tags" />タグデザイン</p>
        </div>
      </div>
    </div>
    <div class="sub">
      <div class="sub-area">
        <div class="filter">
          <img src="../assets/bridal_4.jpg" class="filter-img" alt="ファーストビュー２枚目">
        </div>
        <div class="sub-contents">
          <h2>記事タイトルが入ります。記事タイトルが入ります。</h2>
          <div class="tag-area">
            <p>20201/01/01</p>
            <p class="tag-icon"><font-awesome-icon icon="tags" />タグデザイン</p>
          </div>
        </div>
      </div>
      <div class="sub-area">
        <div class="filter">
          <img src="../assets/bridal_5.jpeg" class="filter-img" alt="ファーストビュー3枚目">
        </div>
        <div class="sub-contents">
          <h2>記事タイトルが入ります。記事タイトルが入ります。</h2>
          <div class="tag-area">
            <p>20201/01/01</p>
            <p class="tag-icon"><font-awesome-icon icon="tags" />タグデザイン</p>
          </div>
        </div>
      </div>
      <div class="sub-area">
        <div class="filter">
          <img src="../assets/bridal_6.jpg" class="filter-img" alt="ファーストビュー4枚目">
        </div>
        <div class="sub-contents">
          <h2>記事タイトルが入ります。記事タイトルが入ります。</h2>
          <div class="tag-area">
            <p>20201/01/01</p>
            <p class="tag-icon"><font-awesome-icon icon="tags" />タグデザイン</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.first-view {
  display: flex;
  justify-content: center;
  margin: 30px 0;
  height: 600px;
}

.main-area {
  position: relative;
  height: 100%;
  width: 65%;
}

.main-area img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}


.main-contents {
  position: absolute;
  bottom: 10%;
  left: 6%;
  color: white;
  width: 80%;
  display: block;
  margin: 0 auto;

}

.main-contents h2 {
  margin-bottom: 50px;
  font-size: 2.1rem;
}

.tag-area {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.tag-area p {
  font-size: 0.7rem;
}

.sub {
  width: 35%;
}

.sub-area {
  position: relative;
  height: 200px;
}

.sub-area img {
  height: 200px;
  width: 100%;
  object-fit: cover;
  opacity: .6;
}


.sub-contents {
  position: absolute;
  bottom: 10%;
  left: 5%;
  color: white;
  width: 90%;
  display: block;
  margin: 0 auto;

}

.sub-contents h2 {
  margin-bottom: 20px;
  font-size: 1.2rem;
}

.tag-icon { 
  border: 1px solid rgb(168, 167, 167);
  padding: 5px;
  background-color: white;
  color: black;
}

.filter {
  background-color: #000;
}

.filter-img {
 display: block;
 opacity: .6;
}
</style>