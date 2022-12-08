<template>
  <body>
      <div id="left-asside">
          <div id="left-asside-in">
            <img src="https://cdn.bkmkitap.com/anna-karenina-ciltli-8730720-30-O.jpg">
          </div>
      </div>
      <div id="div-midd">
        <div>
          <h2>Anna Karerina</h2>
          <p>İş Bankası Kültür Yayınları</p>
          <p id="author">Lev Nikolayeviç Tolstoy</p>
          <img class="pic" src="https://www.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/urundetay/firat/user_27082019/starFill.png">
            <img class="pic" src="https://www.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/urundetay/firat/user_27082019/starFill.png">
            <img class="pic" src="https://www.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/urundetay/firat/user_27082019/starFill.png">
            <img class="pic" src="https://www.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/urundetay/firat/user_27082019/starFill.png">
            <img class="pic" src="https://www.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/urundetay/firat/user_27082019/starFill.png">
            <p>Yorum Ekle</p>
        </div>
        <div class="centerBlock">
          <div>Anna Karenina Hakkında Bilgiler<hr/></div>
          <div>
            <div>
              <span>Türü:</span>
              <span>Rus Edebiyatı</span>
            </div>
            <div>
              <span>Sayfa Sayısı:</span>
              <span>1062</span>
            </div>
            <div>
              <span>ISBN:</span>
              <span>9786053604099</span>
            </div>
            <div>
              <span>Kapak:</span>
              <span>Ciltsiz</span>
            </div>
          </div>
        </div>
      </div>
      <div id="right-asside">
        <div>
          <p>19,00 TL</p>
          <button>SEPETE EKLE</button>
        </div>
        <br>
        <br>
        <br>
        <br>
        <div id="div-author">
          <img>
          <p>Lev Nikolayeviç Tolstoy</p>
        </div>
      </div>
  </body>
</template>
<style>
ul{
    list-style-type: none;
    font-size: 20px;
    position: relative;
    top: 10px;
    left: 17%;
    font-stretch: semi-expanded;
}
ul li{
    float: left;
    margin-left: 35px;
}
p{
    text-indent: 20px;
}

.check{
    width: 10px;
    height: 10px;
}
#left-asside{
    width: 340px;
    float: left;
    padding: 5px;
    position: relative;
    left: 10%;
    border: solid;
    border-color: #efefef;
    background-color: #efefef;
}
#left-asside-in{
    padding: 40px;
    border: solid;
    border-width: 1px;
    border-color: rgb(194, 205, 216);
    background-color: #efefef;
}
#div-midd{
    width: 600px;
    min-height: 700px;
    padding: 10px;
    float: left;
    position: relative;
    left: 12%;
    background: url("");
    background-position: center;
}
#div-midd-in{
    border: solid;
    border-width: 1px;
    border-color: rgb(240, 240, 240);
    background-color: rgb(240, 240, 240);
}
#div-midd p{
    margin-left: -20px;
    color: rgb(155, 155, 155);
}
#div-midd #author{
    font-size: 25px;
    color: rgb(199, 17, 17);
}
.pic{
    width: 20px;
    height: 20px;
}
.centerBlock {
    background: #efefef;
    margin-top: 47px;
    margin-right: 20px;
    width: calc(50% - 20px);
    padding: 10px;
}
#right-asside{
    width: 25%;
    padding: 10px;
    padding-right: 5%;
    float: left;
}
#right-asside div {
    border: solid;
    border-width: 1px;
    padding: 10px;
}
#right-asside div p{
    font-size: 25px;
    color: rgb(199, 17, 17);
}
#right-asside div button{
    background-color: rgb(199, 17, 17);
    color: white;
    padding:15px;
    margin-left: 200px;
}
#right-asside #div-author{
    border-color: brown;
    border-width: 5px;
}
</style>
