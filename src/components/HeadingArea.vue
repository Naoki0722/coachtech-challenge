<template>
  <div class="heading">
    <div class="heading-main">
      <p>Programing</p>
    </div>
    <div class="heading-area">
      <div class="heading-area-2">
        <div class="heading-area-2-color">
        </div>
        <div class="heading-area-2-contents">
          <p>見出しサンプル2</p>
        </div>
      </div>
      <div class="heading-area-3">
        <div class="heading-area-3-color">
        </div>
        <div class="heading-area-3-contents">
          <p>見出しサンプル3</p>
        </div>
      </div>
      <div class="heading-area-4">
          <p>見出しサンプル4</p>
      </div>
      <div class="heading-area-1">
        <p>見出しサンプル1</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.heading {
  display: flex;
  justify-content: center;
  margin: 30px 0;
  align-items: center;
}

.heading-main {
  writing-mode: vertical-rl;
  font-size: 1.3rem;
  font-weight: bold;
}

.heading-area-2,
.heading-area-3,
.heading-area-4,
.heading-area-1 {
  position: relative;
  margin: 10px 0;
  width: 400px;
}

.heading-area-2-color {
  position: absolute;
  top: 0;
  bottom: 0;
  background-color: gray;
  width: 5px;
}


.heading-area-2-contents,
.heading-area-3-contents {
  position: relative;
  padding: 5px 0 5px 10px;

}

.heading-area-3-color {
  position: absolute;
  top: 0;
  bottom: 0;
  background-color: gray;
  width: 20px;
}

.heading-area-4 {
  background-color: gray;
  padding: 5px 0 5px 10px;
}

.heading-area-1 {
  padding: 5px 0 5px 10px;
  border-top: 1px solid black;
  border-bottom: 1px solid black;
}
</style>