<template>
  <div class="table">
    <table>
      <tr>
        <th></th>
        <th class="plan-title-1">
          <p>プランタイトル</p>
          <button>コース詳細</button>
        </th>
        <th class="plan-title-2">
          <p>プランタイトル</p>
          <button>コース詳細</button>
        </th>
        <th class="plan-title-3">
          <p>プランタイトル</p>
          <button>コース詳細</button>
        </th>
      </tr>
      <tr>
        <td>コンテンツ</td>
        <td><span class="gray-circle"></span></td>
        <td><span class="dark-circle"></span></td>
        <td><span class="gray-circle"></span></td>
      </tr>
      <tr>
        <td>コンテンツ</td>
        <td><span class="gray-circle"></span></td>
        <td><span class="dark-circle"></span></td>
        <td><span class="gray-circle"></span></td>
      </tr>
      <tr>
        <td>コンテンツ</td>
         <td><span class="gray-circle"></span></td>
        <td><span class="dark-circle"></span></td>
        <td><span class="gray-circle"></span></td>
      </tr>
      <tr>
        <td>コンテンツ</td>
        <td></td>
        <td><span class="dark-circle"></span></td>
        <td><span class="gray-circle"></span></td>
      </tr>
      <tr>
        <td>コンテンツ</td>
        <td></td>
        <td></td>
        <td><span class="gray-circle"></span></td>
      </tr>
      <tr>
        <td>コンテンツ</td>
        <td></td>
        <td></td>
        <td><span class="gray-circle"></span></td>
      </tr>
    </table>
  </div>
</template>

<style scoped>

.table {
  margin: 100px 0;
}
table {
  margin: 0 auto;
  width: 80%;
}

button {
  box-shadow: 2px 2px 0px 0 rgba(0, 0, 0, 0.849);
}

table td {
  text-align: center;
  padding: 20px 10px;
  background-color: white;
}
table tr:nth-child(odd) td {
  background-color: rgb(211, 211, 211);

}

.plan-title-1 {
  padding: 8px 15px 10px;
  background-color: gray;
  /* margin: 0 100px; */
  border-right: solid 15px white;
}
.plan-title-2 {
  padding: 0 15px;
  background-color: rgb(90, 90, 90);
  border-right: solid 15px white;
  border-left: solid 15px white;
}
.plan-title-3 {
  padding: 0 15px;
  background-color: gray;
  border-left: solid 15px white;
}

.plan-title-1 p,
.plan-title-2 p,
.plan-title-3 p {
  padding-bottom: 10px;
}

.plan-title-2 p {
  color: white;
}

.gray-circle {
  display: inline-block;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: rgb(104, 104, 104);
  margin: 0 auto;
}
.dark-circle {
  display: inline-block;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: rgb(66, 66, 66);
  margin: 0 auto;
}

</style>