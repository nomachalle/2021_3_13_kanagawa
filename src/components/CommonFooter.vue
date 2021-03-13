<template>
  <footer class="top-footer">
    <div class="footer-bar">
      <div class="flex">
        <h1 class="header-logo">estra inc.</h1>
        <nav class="header-nav">
          <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">service</a></li>
            <li><a href="#">works</a></li>
            <li><a href="#">price</a></li>
            <li><a href="#">contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
    <small>Copyright 2019 estra inc. All Rights Reserved.</small>
  </footer>
</template>

<style scoped>
.footer-bar {
  height: 70px;
  line-height: 70px;
}

.top-footer {
  background: #000;
  text-align: center;
}

.top-footer small {
  text-align: center;
  color: #fff;
}

a {
  color: #333333;
  text-decoration: none;
}

img {
  width: 100%;
  height: 100%;
  display: block;
}

.flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

body {
  color: #333333;
  height: 100%;
}

.mgb-15 {
  margin-bottom: 15px;
}

.common-btn {
  display: block;
  width: 130px;
  height: 40px;
  line-height: 40px;
  background: #fff;
  padding: 0 20px;
  color: #000;
  text-align: center;
}

.section-title {
  font-size: 40px;
  line-height: 1;
}

.section-title span {
  font-size: 20px;
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #fff;
  line-height: 70px;
}

.header-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #fff;
}

@media screen and (max-width: 768px) {

  .top-footer .header-logo {
    margin: 0;
    width: 100%;
    text-align: center;
  }
}
</style>