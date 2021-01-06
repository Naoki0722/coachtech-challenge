<template>
  <div class="home">
    <header>
      <div class="header-title">
        <h1>Growth<span class="header-title-sub">Challenge</span></h1>
        <h2>駆け出しエンジニア向けメディア</h2>
      </div>
      <nav>
        <div class="nav-area flex">
          <div class="nav-area-card">
            <h2>ナビリストのテキスト</h2>
            <p>NavListText</p>
            <p class="font-icon"><font-awesome-icon icon="angle-down" /></p>
          </div>
          <div class="nav-area-card">
            <h2>ナビリストのテキスト</h2>
            <p>NavListText</p>
            <p><font-awesome-icon icon="angle-down" /></p>
          </div>
          <div class="nav-area-card">
            <h2>ナビリストのテキスト</h2>
            <p>NavListText</p>
            <p><font-awesome-icon icon="angle-down" /></p>
          </div>
        </div>
      </nav>
      <div class="side-menu">
        <input type="text" class="font-awesome" :placeholder="icon">
        <div class="side-menu-button">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

    </header>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';



@Component
export default class Home extends Vue {
  icon = '🔍キーワードを検索してください';
}
</script>


<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 0;
  background-color: white;
}

.header-title {
  text-align: center;
  padding-left: 2%;
}



.header-title h2 {
  font-weight: normal;
}

.header-title h1 {
  font-size: 40px;
  font-family: serif;
}

.header-title-sub {
  display: block;
  font-size: 30px;
}


.header-title h2 {
  margin-top: 3%;
  font-size: 10px;
}

.flex {
  display: flex;
  
}

nav {
  width: 55%;
}

.nav-area {
  justify-content: center;
}

.nav-area-card {
  text-align: center;
  margin: 0 3%;
}
.nav-area-card h2 {
  font-weight: normal;
  padding: 0 0 10px;
  font-size: 17px;
}



.side-menu {
  padding-right: 2%;
}

.font-awesome {
  position: relative;
  width: 15vw;
}


.side-menu-button {
  margin-top: 10px;
  height: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.side-menu-button span {
  background-color: gray;
  display: block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  
}
</style>