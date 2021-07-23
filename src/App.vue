<template>
  <div id="app">
    <header>
      <div class="container .col-12 .col-md-8">
        <nav>
          <div class="select-menu">
            <select>
              <option value="Thai">Thai</option>
              <option value="English">English</option>
              <option value="United States">United States</option>
            </select>

            <select>
              <option value="Thai">THB</option>
              <option value="English">EUR</option>
              <option value="United States">USD</option>
            </select>
            <p>ติดต่อสอบถาม +66 2534 6732</p>
          </div>

          <div class="nav-btn">
            <li><a href="#">Top Deals</a></li>
            <li><a href="#">Compare Items</a></li>
            <li><a href="#">Add your links</a></li>
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-twitter"></i>
          </div>
        </nav>

        <div class="logo">
          <img class="img1" src=".\assets\logo-istu.png" alt="logo istudio" />
        </div>

        <!-- -->
      </div>
    </header>
    <br />

    <section class="content">
      <div class="container">
        <p style="font-size:31px;color:#3575B6;">
          ระบบสั่งจองสินค้า iStudio by SPVi
        </p>
        <br />
        <strong style="font-size:49px;">ยินดีต้อนรับ</strong>
        <br /><br /><br /><br />

        <div class="img-ipad">
          <img class="img2" src=".\assets\iPad.png" alt="iPads" />
        </div>
        <div class="box">
          <div class="info">
            <strong style="font-size:24px;"
              >กรุณาใส่อีเมลล์ที่ท่านได้ลงทะเบียนไว้ หรือใส่อีเมลล์ของท่าน
              เพื่อดำเนินการต่อ</strong
            ><br /><br />

            <input type="email" placeholder="อีเมลล์ของท่าน" /> <br /><br />

            <p class="รายละเอียด" style="font-size:19px;color:#3575B6;">
              รายละเอียดข้อกำหนดและเงื่อนไข >
            </p>

            <button type="button" class="btn">สั่งจองสินค้า</button>
          </div>
        </div>

        <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
        <div class="logos">
          <img class="logo-img" src=".\assets\istu.png" alt="istudio" />
          <img class="logo-img" src=".\assets\iBeat.png" alt="istudio" />
          <img class="logo-img" src=".\assets\iCare.png" alt="istudio" />
          <img class="logo-img" src=".\assets\UStore.png" alt="istudio" />
          <img class="logo-img" src=".\assets\iSolution.png" alt="istudio" />
          <img class="logo-img" src=".\assets\Mobi.png" alt="istudio" />
        </div>
        <footer>
          <div class="container">
            <div class="footer-box">
              <div class="item">
                <strong>PRODUCT</strong>
                <p>
                  Mac <br /><br />
                  iPad <br /><br />
                  iPhone <br /><br />
                  Apple Watch <br /><br />
                  Accessories
                </p>
              </div>

              <div class="item">
                <strong>PROMOTION</strong>
                <p>
                  Promotion AIS hot deal <br /><br />
                  Promotion บัตรเครดิต (Store) <br /><br />
                  Promotion ประจำเดือน <br /><br />
                  Promotion ใน Shopee Price List <br /><br />
                  ราคาสินค้า Apple
                </p>
              </div>

              <div class="item">
                <strong>SERVICE SUPPORT</strong>
                <p>
                  iCenter<br /><br />
                  iMember <br /><br />
                  เผยเคล็ดลับธุรกิจ SMB Insider<br /><br />
                  Yes I Can Workshop Online<br /><br />
                  Online Schedule Support<br /><br />
                </p>
              </div>

              <div class="item">
                <strong>ONLINE SHOP SUPPORT</strong>
                <p>
                  Online Refund Policy <br /><br />
                  Online Shopping Guide <br /><br />
                  Online Shopping Policy <br /><br />
                  Online Warranty <br /><br />
                </p>
              </div>
            </div>

            <div class="item2">
              <div class="container">
                <img class="img1" src=".\assets\icon.png" alt="icon" />
                <p>
                  iStudio by SPVi | Copyright © 2021 <br />
                  S P V I Public Company Limited All Rights Reserved.
                </p>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </section>

    <!-- -->
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  background-color: white;
  font-family: "Kanit", sans-serif;
}

@media only screen and (max-width: 720px) {
  .container {
    max-width: 720px;
    margin: 0 auto;
    text-align: center;
  }
  nav {
    visibility: hidden;
  }

  .nav-btn {
    visibility: hidden;
  }
  .logo {
    display: flex;
    width: 100%;
    height: 64;
    background: white;
    text-align: center;
  }

  footer {
  width: 100%;
  height: 504 auto;
  color: white;
  background: #191919;
  text-align: center;
}

.footer-box {
  display: inline-block;
 
}
.item {
  margin-top: 76px;
  width: 17.36%;
}
footer strong {
  font-size: 17px;
}
footer p {
  visibility: hidden;
}

}

.container {
  max-width: 1440px;
  margin: 0 auto;
  text-align: center;
}

nav {
  width: 100%;
  height: 24px;
  background: #1d1e1f;
  color: #ececec;
  display: flex;
  justify-content: space-between;
  border: 1px solid #ececec;
}

.select-menu {
  display: flex;
  width: 50%;
  height: 22px;
  margin-left: 50px;
}

nav select {
  background: #191919;
  color: #ececec;
  border: none;
  align-items: center;
  text-align: center;
  margin-right: 20px;
}

.nav-btn {
  display: flex;
  list-style: none;
  align-items: center;
  width: 480px;
  height: 24px;
}

.nav-btn li {
  color: #ececec;
  margin-right: 25px;
}
.nav-btn a {
  color: #ececec;
}
.nav-btn i {
  color: #cbcbcb;
  margin-right: 25px;
}

.logo {
  display: flex;
  width: 100%;
  height: 64;
  border: 1px solid #ececec;
}
.logo img {
  max-width: 1440px;
  margin: 0 auto;
  text-align: center;
}

.ipad {
  width: 49.48%;
}
.logos {
  display: flex;
  width: 100%;
  text-align: center;
}
.logo-img {
  margin-left: 9.38%;
  text-align: center;
}

.box {
  display: flex;
  position: absolute;
  width: 70%;
  height: 290px;
  margin-left: 7%;
  margin-right: auto;
  top: 1009.04px;
  align-items: center;
  background: #f5f5f7;
  text-align: center;
}
.info {
  margin: 0 auto;
  text-align: center;
  background: #f5f5f7;
}
input {
  width: 75%;
  height: 40 auto;
  background: #ffffff;
  border: 1px solid #c4c4c4;
  box-sizing: border-box;
  text-align: center;
}

button {
  width: 50%;
  height: auto;
  background-color: #3575b6;
  color: white;
  text-align: center;
  font-size: 19px;
}

footer {
  width: 100%;
  height: 504 auto;
  color: white;
  background: #191919;
  text-align: center;
}

.footer-box {
  display: flex;
  justify-content: space-between;
}
.item {
  margin-top: 76px;
  width: 17.36%;
}
.item2 {
  text-align: center;
  width: 100%;
}
footer strong {
  font-size: 17px;
}
footer p {
  margin-top: 20px;
  font-size: 15px;
  color: #626262;
}

.footer-icon {
  display: flex;
  justify-content: space-between;
  margin-right: 50;
}
</style>
