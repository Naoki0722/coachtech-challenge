<template>
  <div class="botton-section">
    <div class="botton-area-section-1">
      <botton class="botton-area-1"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-1 shadow">Button</botton>
      <botton class="botton-area-1 shadow2">Button</botton>
    </div>
    <div class="botton-area-section-2">
      <botton class="botton-area-2 shadow5"><img src="../assets/tag1.svg">タグデザイン</botton>
      <botton class="botton-area-2 shadow3">Button</botton>
      <botton class="botton-area-2 shadow4">Button</botton>
    </div>
  </div>
</template>

<style scoped>
.botton-section {
  text-align: center;
}

.botton-area-section-1,
.botton-area-section-2 {
  margin: 40px auto;
}

.botton-area-1 {
  background-color: white;
  padding: 10px;
  margin: 20px;
  text-align: center;
  border: 1px solid black;
}

.botton-area-1:hover {
  cursor: pointer;
}

.botton-area-1 img {
  width: 15px;
}

.shadow {
  box-shadow: 0 10px 25px 0 rgba(0, 0, 0, .5);
  padding: 10px 30px;
}

.shadow2 {
  box-shadow: 5px 5px 0px 0 rgba(0, 0, 0, 0.849);
  padding: 10px 30px;
}

.botton-area-2 {
  background-color: white;
  padding: 10px;
  margin: 20px;
  text-align: center;
  border: 1px solid black;
}

.shadow5 {
  box-shadow: 5px 5px 0px 0 rgb(255, 255, 255) ,5px 5px 0px 1px #070707;
}

.botton-area-2 img {
  width: 15px;
}


.shadow3 {
  box-shadow: 0 10px 25px 0 rgba(0, 0, 0, .5);
  padding: 10px 30px;
  border-radius: 20px;
}

.shadow4 {
  border: none;
  position: relative;
  border-top: 1px solid black;
  border-bottom: 1px solid black;
}

.shadow4:before, .shadow4:after {
	content: '';
	position: absolute;
  top: 5px;
	width: 1px;
	height: calc(100% - 10px);
	background-color: #000;
}
.shadow4:before {
	left: 0;
}
.shadow4:after {
	right: 0;
}
</style>