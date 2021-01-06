<template>
  <div class="main-heading">
    <div class="heading-area">
        <h2 class="title">目次<label for="label1">[非表示]</label></h2>
        <input type="checkbox" id="label1"/>
      <div class="hidden-area">
        <div class="heading-area-1">
          <h2>1 <span class="gray-area">サンプルタイトルh2</span></h2>
          <h3>1-1 <span class="gray-area">サンプルタイトルh3</span></h3>
          <div class="title-border-1"></div>
          <h4>1-1-1 <span class="gray-area">サンプルタイトルh3</span></h4>
          <div class="title-border-2"></div>
          <h4>1-1-2 <span class="gray-area">サンプルタイトルh3</span></h4>
          <div class="title-border-2"></div>
        </div>
        <div class="heading-area-2">
          <h2>2 <span class="gray-area">サンプルタイトルh2</span></h2>
          <h3>2-1 <span class="gray-area">サンプルタイトルh3</span></h3>
          <div class="title-border-1"></div>
          <h4>2-1-1 <span class="gray-area">サンプルタイトルh3</span></h4>
          <div class="title-border-2"></div>
          <h4>2-1-2 <span class="gray-area">サンプルタイトルh3</span></h4>
          <div class="title-border-2"></div>
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>

.main-heading {
  text-align: center;
  margin: 100px 0;
}
.heading-area {
  text-align: left;
  display: inline-block;
  background-color: white;
  width: 50%;
  padding: 20px 80px;
  border: 1px solid black;
  border-radius: 20px;
}

.heading-area input {
  display: none;
}

.hidden-area {
  visibility: collapse;
  opacity: 0;
  transition: 0.8s;
}


.heading-area label:hover {
  cursor: pointer;
}

.heading-area input:checked ~ .hidden-area {
  visibility: visible;
  opacity: 1;
}


.title {
  padding: 20px 0 10px 0;
}
.heading-area-1 {
  margin: 20px 0;
}

.heading-area-1 h2,
.heading-area-1 h3,
.heading-area-1 h4,
.heading-area-2 h2,
.heading-area-2 h3,
.heading-area-2 h4 {
  margin: 35px 0 0 0;
  padding: 5px 0;
}

.heading-area-2 {
  margin: 20px 0;
}

.heading-area-1 h2,
.heading-area-2 h2 {
  border-bottom: 2px solid black;
}

.heading-area-1 h3,
.heading-area-2 h3 {
  text-indent: 1em;
}

.heading-area-1 h4,
.heading-area-2 h4 {
  text-indent: 2em;
}

.gray-area {
  color: gray;
}

.title-border-1 {
  height: 1px;
  width: calc(100% - 1em);
  text-align: right;
  background-color: gray;
  margin: 0 0 0 auto;
}

.title-border-2 {
  height: 1px;
  width: calc(100% - 2em);
  text-align: right;
  background-color: gray;
  margin: 0 0 0 auto;
}


</style>