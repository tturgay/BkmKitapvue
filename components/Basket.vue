<template>
  <body>
      <div>
          <div id="state">
              <a href="">
                  <div id="basket">
                    <p>SEPET</p>
                  </div>
              </a>
              <a href="">
                <div id="address">
                    <p>ADRES</p>
                </div>
              </a>
              <a href="">
                <div id="paying">
                    <p>ÖDEME</p>
                </div>
              </a>
              <a href="">
                <div id="confrim">
                    <p>ONAY</p>
                </div>
              </a>
          </div>
          <br><br><br><br><br><br><br>
          <div>
            <ul>
              <li><div class="line" id="line1"></div></li>
              <li><div class="line" id="line2"></div></li>
              <li><div class="line" id="line3"></div></li>
              <li><div class="line" id="line4"></div></li>
            </ul>
          </div>
            <div class="information-box">
              <ul>
                <li class="p-font-size" id="li-product">Ürün</li>
                <li class="p-font-size" id="li-product-name">Ürün Adı</li>
                <li class="p-font-size" id="li-amount">Miktar</li>
                <li class="p-font-size" id="li-cost">Toplam Tutar</li>
                <li class="p-font-size" id="li-del">Sil</li>
              </ul>
            </div>
            <div id="salebox">
                  <input type="text" placeholder="Kupon/Hediye Kartı Kodunuz" value="">
                  <a>Uygula</a>
            </div>
          <br>
            <div>
              <ul>
                <li id="li-img"><img src="https://cdn.bkmkitap.com/martin-eden-134847-8738952-13-K.jpg" alt=""></li>
                <li id="li-author"><p class="p-font-size">Martin Eden</p><br><br><p class="p-font-size color-red">İş Bankası Kültür Yayınları</p></li>
                <li id="li-button">
                  <ul class="ul-up-down">
                    <li><button id="down-button"> - </button></li>
                    <li class="p-font-size"><p>1</p></li>
                    <li><button id="up-button">+</button></li>
                  </ul>
                </li>
                <li id="li-price"><div id="div-price">12,50tl</div></li>
                <li id="li-remove" class="p-font-size"><p>kaldır  x</p></li>
              </ul>
            </div>
            <div id="div-basket">
              <p>Sepet Toplamı</p>
              <p>12,50</p>
            </div>
            <br>
            <br>
            <br>
            <div id="div-total">
              <p>Genel Toplam</p>
              <p>12,50</p>
            </div>
            <br>
            <div id="shopping-info">
              <p>Sepetinizde değişiklik yaptıysanız güncellemeyi unutmayın. Ödeme ve  onay sayfasına kadar satın alma işleminizi iptal edebilirsiniz.</p>
            </div>
            <button id="bttn-goto-payying">ÖDEMEYE GİT</button>
      </div>
  </body>
</template>
<style>
ul{
   list-style-type: none;
}
  #bttn-goto-payying{
    background-color: #e4002b;
    border-color: #e4002b;
    border-radius: 3px;
    color: antiquewhite;
    width: 250px;
    padding-top: 20px;
    padding-bottom: 20px;
    float: left;
    margin-left: 750px;
  }
  #div-basket p{
    float: left;
    margin-top: -10px;
    margin-left: 40px;
  }
  #div-total p{
    margin-top: -10px;
    float: left;
    margin-left: 40px;
  }
  #shopping-info p{
    margin-left: 550px;
    margin-right: 250px;
  }
  #div-price{
    background-color: #e4002b;
    border-color: #e4002b;
    border-radius: 10px;
    color: antiquewhite;
    line-height: 20px;
    width: 100px;
    height: auto;
    float: left;
    padding-top: 10px;
    padding-bottom: 10px;
    text-align: center;
  }
  #li-author{
    margin-top: 20px;
  }
  #li-remove{
    margin-top: 120px;
    margin-left: 30px;
    margin-right: 30px;
  }
  #li-price{
    float: left;
    margin-left: 70px;
    margin-top: 120px;
  }
  #li-button{
    margin-left: 170px;
    float: left;
  }
  .ul-up-down li #down-button{
    margin-left: -20px;
  }
  .ul-up-down li p{
    margin-left: -17px;
    margin-top: 5px;
  }
  .ul-up-down{
    float: left;
    margin-top: 100px;
  }
  .color-red{
    color: #e4002b;
  }
  .li-margin{
    margin-top: 70px;
  }
  #li-img{
    margin-left: 120px;
  }
  #li-product{
    margin-left: -30px;
  }
  #li-product-name{
    margin-left: 140px;
  }
  #li-amount{
    margin-left: 300px;
  }
  #li-cost{
    margin-left: 100px;
  }
  #li-del{
    margin-left: 90px;
  }
.information-box{
  border: solid;
  border-color: #e2e2e2;
  border-width: 1px;
  width: 850px;
  padding-bottom: 10px;
  margin-left: 160px;
}
#salebox{
  margin-top: -30px;
}
#salebox input{
  height: 30px;
  margin-left: -270px;
}
.p-font-size{
  font-size: 13px;
}
.information-box ul li{
  float: left;
}
#line1{
  margin-left: 70px;
}
#line2, #line4, #line3{
  margin-left: -15px;
}
.line{
  width: 300px;
  border-bottom: 4px solid #979797;
}
#state{
    margin-left: 100px;
}
#basket, #address, #paying, #confrim{
    border: solid;
    background-color: #f2f2f2;
    border-color: #f2f2f2;
    border-radius: 45px;
    color: #4a4a4a;
    float: left;
    text-align: center;
    font-size: 20px;
    font-weight: 700;
    width: 270px;
    height: 80px;
    margin: 20px;
}
</style>
