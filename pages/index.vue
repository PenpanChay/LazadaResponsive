<template>
  <div>
    <div id="CarouselSlide" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#CarouselSlide" data-slide-to="0" class="active"></li>
        <li data-target="#CarouselSlide" data-slide-to="1"></li>
        <li data-target="#CarouselSlide" data-slide-to="2"></li>
        <li data-target="#CarouselSlide" data-slide-to="3"></li>
        <li data-target="#CarouselSlide" data-slide-to="4"></li>
        <li data-target="#CarouselSlide" data-slide-to="5"></li>
        <li data-target="#CarouselSlide" data-slide-to="6"></li>
        <li data-target="#CarouselSlide" data-slide-to="7"></li>
      </ol>
      <div class="carousel-inner">
        <div class="item active">
          <img
            src="@/static/images/banner_1.jpg"
            alt="Los Angeles"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_2.jpg"
            alt="Chicago"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_3.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_4.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_5.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_6.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_7.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
        <div class="item">
          <img
            src="@/static/images/banner_8.jpg"
            alt="New york"
            style="width: 100%"
          />
        </div>
      </div>
      <a class="left carousel-control" href="#CarouselSlide" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#CarouselSlide" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    <!-- add menu botton -->
    <div class="container">
      <div class="row row-cols-6 head-button pt-3 pb-3 justify-content-center">
        <div class="hb-location col">
          <img class="pt-1 pb-1" src="@/static/images/icon-1.png" />
          <p class="pt-1 pb-1">LazMall</p>
        </div>
        <div class="hb-location col">
          <img class="pt-1 pb-1" src="@/static/images/icon-2.png" />
          <p class="pt-1 pb-1">Vouchers</p>
        </div>
        <div class="hb-location col">
          <img class="pt-1 pb-1" src="@/static/images/icon-3.png" />
          <p class="pt-1 pb-1">Top-up, Bill&Food</p>
        </div>
        <div class="hb-location col">
          <img class="pt-1 pb-1" src="@/static/images/icon-4.png" />
          <p class="pt-1 pb-1">9 Baht</p>
        </div>
        <div class="hb-location col">
          <img class="pt-1 pb-1" src="@/static/images/icon-5.png" />
          <p class="pt-1 pb-1">LazPick</p>
        </div>
      </div>
    </div>
    <!-- add flash sale-->
    <div class="container">
      <p class="txt-first-size">Flash Sale</p>
    </div>
    <div class="container">
      <div class="border-sale pt-2 pb-2">
        <div class="container">
          <div class="row">
            <div class="col-lg-6 col-12">
              <div class="row">
                <div class="col-5">
                  <p class="txt-second-size">On Sale Now</p>
                </div>
                <div class="col-7">
                  <p class="txt-thrid-size">
                    Ending in <span class="numbg">15</span> :
                    <span class="numbg">00</span> :
                    <span class="numbg">45</span>
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-12">
              <div class="box-product">
                <p class="txt-second-size">SHOP All PRODUCTS</p>
              </div>
            </div>
          </div>
          <hr class="line-sale" />
          <div class="row row-cols-lg-6 row-cols-2 ml-1 mr-1">
            <div class="col img-box">
              <img src="@/static/images/flashsale/iphone.jpg" class="w-100" />
              <p class="txt-forth-size">
                iPhone 13 Pro [ONEDERFUL WALLET วันที่ 5 มิ.ย. 65] - 1
                สิทธิ์/ลูกค้า
              </p>
              <p class="txt-second-size">฿1.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿38900.00</span>
                -99%
              </p>
            </div>
            <div class="col img-box">
              <img src="@/static/images/flashsale/wallet.jpg" class="w-100" />
              <p class="txt-forth-size">
                เงินวอลเล็ต มูลค่า 6,666 บาท [ONEDERFUL WALLET วันที่ 5 มิ.ย.
                65] - 1 สิทธิ์/ลูกค้า
              </p>
              <p class="txt-second-size">฿1.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿6666.00</span> -99%
              </p>
            </div>
            <div class="col img-box">
              <img src="@/static/images/flashsale/kfc.jpg" class="w-100" />
              <p class="txt-forth-size">
                เฉพาะ Self Pick-Up รับหน้าร้าน เท่านั้น E voucher KFC Fried
                Chicken 1 pcs คูปอง เคเอฟซี ไก่ทอด 1 ชิ้น
              </p>
              <p class="txt-second-size">฿24.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿39.00</span> -38%
              </p>
            </div>
            <div class="col img-box">
              <img src="@/static/images/flashsale/true.jpg" class="w-100" />
              <p class="txt-forth-size">TrueMove 10</p>
              <p class="txt-second-size">฿5.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿10.00</span> -50%
              </p>
            </div>
            <div class="col img-box">
              <img src="@/static/images/flashsale/fashion.jpg" class="w-100" />
              <p class="txt-forth-size">
                iFashion 046 [S-5XL] กางเกงยีนส์ผู้หญิงแฟชั่น เอวสูง สกินนี่
                ยีนส์ยืด ขากว้าง ขาบาน รุ่ย xxl กางเกงผู้หญิง
              </p>
              <p class="txt-second-size">฿143.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿490.00</span> -71%
              </p>
            </div>
            <div class="col img-box">
              <img src="@/static/images/flashsale/watch.jpg" class="w-100" />
              <p class="txt-forth-size">
                Riches Mall นาฬิกาดิจิตอล นาฬิกาผู้ชายและผู้หญิง กีฬา กันน้ำ
                มีไฟ LED นาฬิกาปลุก ปฏิทิน นาฬิกา RW261
              </p>
              <p class="txt-second-size">฿51.00</p>
              <p class="txt-forth-size">
                <span style="text-decoration: line-through">฿259.00</span> -80%
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- add collections -->
    <div class="container">
      <div class="row row-cols-2 ml-1 mr-1">
        <div class="col">
          <p class="txt-first-size">Collections</p>
        </div>
        <div class="col">
          <div class="box-more mt-3">
            <p>Shop More ></p>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="border-sale pt-2 pb-2">
        <div class="container">
          <div class="row row-cols-lg-4 row-cols-1 ml-1 mr-1 pt-3 pb-3">
            <div class="col bord-r">
              <p class="txt-forth-size text-center">Show off your wallets ></p>
              <p class="txt-forth-size text-center">1,695 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/1.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/2.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/3.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col bord-r">
              <p class="txt-forth-size text-center">เล่นกีฬาไม่กลัวดำ ></p>
              <p class="txt-forth-size text-center">1,568 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/4.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/5.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/6.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col bord-r">
              <p class="txt-forth-size text-center">Healthy Beauty ></p>
              <p class="txt-forth-size text-center">464 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/7.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/8.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/9.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col">
              <p class="txt-forth-size text-center">Bathroom Idea ></p>
              <p class="txt-forth-size text-center">1,115 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/10.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/11.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/12.jpg" class="w-100" />
                </div>
              </div>
            </div>
          </div>
          <hr class="line-sale" />
          <div class="row row-cols-lg-4 row-cols-1 ml-1 mr-1 pt-3 pb-3">
            <div class="col bord-r">
              <p class="txt-forth-size text-center">
                Create Your Dream Kitchen >
              </p>
              <p class="txt-forth-size text-center">3,018 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/13.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/14.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/15.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col bord-r">
              <p class="txt-forth-size text-center">Top hit toys ></p>
              <p class="txt-forth-size text-center">9,113 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/16.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/17.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/18.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col bord-r">
              <p class="txt-forth-size text-center">Best Deal Mobile ></p>
              <p class="txt-forth-size text-center">1,104 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/19.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/20.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/21.jpg" class="w-100" />
                </div>
              </div>
            </div>
            <div class="col">
              <p class="txt-forth-size text-center">ลุกน้อยเล่นสนุก ></p>
              <p class="txt-forth-size text-center">19,952 products</p>
              <div class="row">
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/22.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/23.jpg" class="w-100" />
                </div>
                <div class="col-4 img-box">
                  <img src="@/static/images/collection/24.jpg" class="w-100" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- add LazMall -->
    <div class="container">
      <div class="row row-cols-2 ml-1 mr-1">
        <div class="col">
          <p class="txt-first-size">LazMall</p>
        </div>
        <div class="col">
          <div class="box-more mt-3">
            <p>Shop More ></p>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="pt-2 pb-2">
        <div class="container">
          <div
            class="row row-cols-lg-6 row-cols-2 ml-1 mr-1 pt-3 pb-3 text-center"
          >
            <div class="col img-box">
              <img src="@/static/images/LazMall/1.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo1.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">Watsons</p>
                <p class="txt-forth-size text-center">LOOK GOOD, FEEL GREAT</p>
              </div>
            </div>
            <div class="col img-box">
              <img src="@/static/images/LazMall/2.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo2.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">Villa Market</p>
                <p class="txt-forth-size text-center">Villa Market</p>
              </div>
            </div>
            <div class="col img-box">
              <img src="@/static/images/LazMall/3.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo3.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">ErgoTrend</p>
                <p class="txt-forth-size text-center">
                  Ergonomic for Betterlife
                </p>
              </div>
            </div>
            <div class="col img-box">
              <img src="@/static/images/LazMall/4.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo4.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">MUJI</p>
                <p class="txt-forth-size text-center">無印良品</p>
              </div>
            </div>
            <div class="col img-box">
              <img src="@/static/images/LazMall/5.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo5.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">
                  Apple Flagship Store
                </p>
                <p class="txt-forth-size text-center">
                  Apple Products You Love
                </p>
              </div>
            </div>
            <div class="col img-box">
              <img src="@/static/images/LazMall/6.jpg" class="border-img" />
              <div class="text-center marg-logo bg-white img-box">
                <img
                  src="@/static/images/LazMall/logo6.jpg"
                  class="text-center w-25"
                />
                <p class="txt-forth-size text-center pt-3">Vita</p>
                <p class="txt-forth-size text-center">Vita</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- add Categories -->
    <div class="container">
      <p class="txt-first-size">Categories</p>
    </div>
    <div class="container">
      <div class="border-sale pt-2 pb-2">
        <div class="container">
          <div class="row row-cols-lg-6 row-cols-3 ml-1 mr-1 pt-3 pb-3">
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/1.jpg" />
              <p class="txt-forth-size text-center pt-3">Mobiles</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/2.jpg" />
              <p class="txt-forth-size text-center pt-3">
                Electrical Circuitry & Parts
              </p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/3.jpg" />
              <p class="txt-forth-size text-center pt-3">Outdoor Lighting</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/4.jpg" />
              <p class="txt-forth-size text-center pt-3">
                Plant, Seeds and Bulbs
              </p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/5.jpg" />
              <p class="txt-forth-size text-center pt-3">Women's Dresses</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/6.jpg" />
              <p class="txt-forth-size text-center pt-3">Lawn Mowers</p>
            </div>
          </div>
          <hr class="line-sale" />
          <div class="row row-cols-lg-6 row-cols-3 ml-1 mr-1 pt-3 pb-3">
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/7.jpg" />
              <p class="txt-forth-size text-center pt-3">Wireless Earbuds</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/8.jpg" />
              <p class="txt-forth-size text-center pt-3">
                Phone Cables & Converters
              </p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/9.jpg" />
              <p class="txt-forth-size text-center pt-3">Drills & Drivers</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/10.jpg" />
              <p class="txt-forth-size text-center pt-3">en's T-Shirts</p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/11.jpg" />
              <p class="txt-forth-size text-center pt-3">
                Wireless and Bluetooth Speakers
              </p>
            </div>
            <div class="col text-center img-box">
              <img src="@/static/images/Categories/12.jpg" />
              <p class="txt-forth-size text-center pt-3">Health Accessories</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- add Just for You -->
    <div class="container">
      <p class="txt-first-size">Just for You</p>
    </div>
    <div class="container">
      <div class="pt-2 pb-2">
        <div class="container">
          <div class="row row-cols-lg-6 row-cols-2 ml-1 mr-1 pt-3 pb-3">
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/1.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  (ขวดใหญ่) RADA lady care ล้างหอยหอมหวาน ขนาด150ml.(1ชิ้น)
                </p>
                <p class="txt-second-size">฿78.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿149.00</span>
                  -48%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (930)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/2.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  Coco'Care น้ำมันมะพร้าวสกัดเย็น ออร์แกนิก 100% Organic Cold...
                </p>
                <p class="txt-second-size">฿165.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿350.00</span>
                  -53%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (2977)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/3.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  Lcd Display จอ+ทัช งานแท้ vivo Y11/vivo Y12/vivo Y15/vivo...
                </p>
                <p class="txt-second-size">฿479.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿1,000.00</span>
                  -52%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (1085)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/4.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  [ขายดีอันดับ 2] Olay Total Effects Day+Night Cream...
                </p>
                <p class="txt-second-size">฿569.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿998.00</span>
                  -43%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (15040)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/5.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  ✅💯 อะบา-หมูพระอาทิตย์ อะบาเมกติน ( 1 ลิตร ) น้ำใส
                  สูตรเย็น...
                </p>
                <p class="txt-second-size">฿148.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿149.00</span> -1%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (930)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/6.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  ถ่านชาร์จ 18650 3.7V 9900 mAh 2 ก้อน (สีแดง) + ที่ชาร์จแบต
                </p>
                <p class="txt-second-size">฿97.02</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿290.00</span>
                  -67%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (1664)</span>
                </p>
              </div>
            </div>
          </div>
          <div class="row row-cols-lg-6 row-cols-2 ml-1 mr-1 pt-3 pb-3">
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/7.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  igootech แผ่นรองเท้าสุขภาพ ลดอาการปวด...
                </p>
                <p class="txt-second-size">฿39.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿99.00</span> -61%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (3963)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/8.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  ตัวโหลด โช้ค สีเงิน+น็อตเลส อะไหล่รถมอเตอร์ไซค์
                </p>
                <p class="txt-second-size">฿160.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿550.00</span>
                  -71%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (462)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/9.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  2 ห่อ กาแฟ BLAZO COFFEE 2 ห่อ เบลโซ่ คอฟฟี่ เบลโซ...
                </p>
                <p class="txt-second-size">฿369.00</p>
                <p class="txt-forth-size"></p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (278)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/10.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  【M/L/XL/XXL】ผ้าคลุมรถมอไซ กันแดดกันน้ำได้...
                </p>
                <p class="txt-second-size">฿128.79</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿350.00</span>
                  -63%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (1293)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/11.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  adiรองเท้าลำลองเด็ก PVC รองเท้าแตะเด็ก หนังนุ่ม...
                </p>
                <p class="txt-second-size">฿29.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿100.00</span>
                  -71%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (202)</span>
                </p>
              </div>
            </div>
            <div class="col text-center pb-3 img-box">
              <img
                src="@/static/images/justforyou/12.jpg"
                class="border-img-just"
              />
              <div class="bg-white p-2">
                <p class="txt-forth-size pt-3">
                  Realme 5i/realme 5/realme 5S Lcd หน้าจอ...
                </p>
                <p class="txt-second-size">฿459.00</p>
                <p class="txt-forth-size">
                  <span style="text-decoration: line-through">฿800.00</span>
                  -43%
                </p>
                <p class="text-warning">
                  <i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i><i class="fas fa-star"></i
                  ><i class="fas fa-star"></i
                  ><span class="text-dark"> (472)</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container txt-cen pb-3">
      <div class="border-load">
        <p class="pt-3">LOAD MORE</p>
      </div>
    </div>
    <hr class="line-sale" />
  </div>
</template>

<script>
export default {
  layout: "default",
};
</script>
<style>
.carousel-indicators li {
  width: 10px !important;
  height: 10px !important;
  border-radius: 50%;
  border-left: 0px;
  border-right: 0px;
}
.head-button .hb-location {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background: #fff;
  border-radius: 2.5rem;
  margin-left: 0.5rem;
  margin-right: 0.5rem;
}
.head-button .hb-location p {
  font-size: 1.25rem;
  margin: auto;
}
@media screen and (max-width: 960px) {
  .head-button .hb-location p {
    font-size: 1rem;
    margin: auto;
  }
}
.head-button .hb-location img {
  width: 25%;
}
@media screen and (max-width: 960px) {
  .head-button .hb-location img {
    width: 50%;
  }
}

.border-img {
  box-shadow: 5px 5px 10px 10px rgba(50, 50, 50, 0.4);
  width: 150px;
  height: 150px;
}
@media screen and (max-width: 960px) {
  .border-img {
    box-shadow: 5px 5px 10px 10px rgba(50, 50, 50, 0.4);
    width: 130px;
    height: 130px;
  }
}

.border-img-just {
  width: 150px;
  height: 150px;
}

@media screen and (max-width: 960px) {
  .border-img-just {
    width: 130px;
    height: 130px;
  }
}
.numbg {
  background: red;
  padding: 2px;
  font-size: 1.25rem;
}
</style>
