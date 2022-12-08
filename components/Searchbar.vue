<template>
  <div>
    <div>
      <div id="divpromotion">
        <img id="imgpromotion" src="@\assets\ustbanner.png">
      </div>
        <header id="banner">
            <nav>
                <ul>
                    <li id="li-logo"><a><img id="imglogo" src="https://cdn.bkmkitap.com/Data/EditorFiles/logonew23.png"></a></li>
                    <li id="li"><a href=""> <img id="imgbell" src="https://cdn.bkmkitap.com/Data/EditorFiles/bell_icon.png"></a></li>
                    <li id="li"><a href=""><img src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/ust/firat/v4/menu.png">Menü</a></li>
                    <li id="li-search"><input type="text" name="search" id="input-search" size="30" maxlength="30"
                       required placeholder="Aradığınız ürünün adını yazınız">
                      <a href=""><img src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/ust/firat/v4/search.png">ARA</a></li>
                    <li id="li"><a href=""> <img src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/ust/firat/v4/login.png">Üye Ol</a></li>
                    <li id="li"><a href=""><img src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/ust/firat/v4/login.png">Giriş Yap</a></li>
                    
                    <li id="li"><a href=""><img src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/ust/firat/v4/cart.png">Sepet</a></li>
                </ul>
            </nav>
        </header>
    </div>
  </div>
</template>
<style>
#help{
  width: 14px;
  height: auto;
}
#imgpromotion{
    width: 103%;
    margin-right: 2%;
    margin-left: -1%;margin-bottom: -1%;
    margin-top: -1%;
}
#banner{
    border-style: solid;
    padding-bottom: 15px;
    margin-top: -15px;
    border-width: 25px;
    margin-left: -1%;
    margin-right: -1%;
    border-color: rgb(243, 243, 243);
    background-color: rgb(243, 243, 243);
}
#banner a{
    text-decoration: none;
}
#banner ul #li,#banner ul #li-search{
    text-decoration: none;
    font-size: 11px;
    padding: 10px;
    color: rgb(184, 182, 182);
    border: solid;
    border-width: 1px;
    background-color: white;
}
#imgbell{
    width: 12px;
    height: auto;
}
#imglogo{
    width: 100px;
    height: 40px;
}
ul{
    list-style-type: none;
    font-size: 20px;
    position: relative;
    top: -10px;
    font-stretch: semi-expanded;
}
/* #li-search{
    width: 700px;
    border-style: none;
    height: 10px;
} */
#input-search{
    width: 700px;
    position: relative;
    height: 1px; 
}
ul li{
    float: left;
    margin-left: 1%;
}
p{
    text-indent: 20px;
}
</style>
