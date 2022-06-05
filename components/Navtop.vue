<template>
  <div class="head">
    <div class="head-tab">
      <div class="container">
        <div>
          <a class="auth txt-blue" href="#">SAVE MORE ON APP</a>
          <a class="auth txt-blue" href="#">SELL ON LAZADA</a>
          <a class="auth txt-muted" href="#">CUSTOMER CARE</a>
          <a class="auth txt-muted" href="#">TRACK MY ORDER</a>
          <a class="auth txt-muted" href="#">LOGIN</a>
          <a class="auth txt-muted" href="#">SIGNUP</a>
          <a class="auth txt-muted" href="#">เปลี่ยนภาษา</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.head-tab {
  background: #e5e7e9;
  height: 32px;
}
.head-tab .container {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  float: right;
}
.head-tab .auth {
  color: white;
  display: inline-block;
  text-decoration: none;
  box-sizing: border-box;
  font-size: 1.2rem;
  padding: 10px;
  padding-top: 5px;
}
@media screen and (max-width: 800px) {
  .head-tab {
    background: #e5e7e9;
    height: 70px;
    text-align: -webkit-center;
  }
  .head-tab .auth {
    color: white;
    display: inline-block;
    text-decoration: none;
    box-sizing: border-box;
    font-size: 1rem;
    padding: 10px;
    padding-top: 5px;
  }
}
.head-tab .txt-blue {
  color: #0f1568;
}
.head-tab .txt-muted {
  color: #9e9e9e;
}
.head-tab .txt-muted:hover,
.head-tab .txt-blue:hover {
  color: #f36d00;
}
</style>
