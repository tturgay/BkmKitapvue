<template>
  <body>
      <div id="left-asside">
        <div id="subdiv">
          <ul>
            <li><img id="picexp" src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/vitrin/firat/v4/titleico.png"></li>
            <li><h4>ÜYE OL</h4></li>
            <li><img id="picexp" src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/vitrin/firat/v4/titleico1.png"></li>
          </ul>
        </div>
        <br><br><br><br><br>
        <form class="form1" name="kayit" target="_blank" method="Get"
            autocomplete="on">
              <table class="register">
                <tr class="row">
                    <td class="input"><input type="text" name="name" id="idName"
                        size="30" maxlength="30" required placeholder="Ad"></td>
                </tr>
                <tr class="row">
                    <td class="input"><input type="text" name="surname" id="idSurname"
                        size="30" maxlength="30" required placeholder="Soyad"></td>
                </tr>
                <tr class="row">
                  <td>
                    <ul>
                      <li id="liselectDay"><select id="selectDay" name="day">
                        <option selected>Gün</option>
                        <option>1</option>
                        <option>2</option>
                        <option>3</option>
                        <option>4</option>
                        <option>5</option>
                        <option>6</option>
                        <option>7</option>
                        <option>8</option>
                        <option>9</option>
                        <option>10</option>
                        <option>11</option>
                        <option>12</option>
                        <option>13</option>
                        <option>14</option>
                        <option>15</option>
                        <option>16</option>
                        <option>17</option>
                        <option>18</option>
                        <option>19</option>
                        <option>20</option>
                        <option>21</option>
                        <option>22</option>
                        <option>23</option>
                        <option>24</option>
                        <option>25</option>
                        <option>26</option>
                        <option>27</option>
                        <option>28</option>
                        <option>29</option>
                        <option>30</option>
                        <option>31</option>
                        </select>
                      </li>
                      <li id="liselectMonth"><select id="selectMonth" name="month">
                          <option selected>Ay</option>
                          <option>Ocak</option>
                          <option>Şubat </option>
                          <option>Mart </option>
                          <option>Nisan </option>
                          <option>Mayıs </option>
                          <option>Haziran </option>
                          <option>Temmuz </option>
                          <option>Ağustos </option>
                          <option>Eylül</option>
                          <option>EKim</option>
                          <option>Kasım</option>
                          <option>Aralık</option>
                      </select>
                      </li>
                      <li id="liYear"><input type="number" required placeholder="Yıl"
                        name="year" id="year" requiredsize="4"></li>
                    </ul>
                  </td>
                </tr>
                <tr class="row">
                  <td>
                      <select id="selectGender" name="gender">
                          <option selected>Cinsiyetinizi giriniz...</option>
                          <option>Kadın</option>
                          <option>Erkek</option>
                      </select>
                  </td>
                </tr>
                <tr class="row">
                   <td class="input"> <!--<img id="imgTurkBayragi" src="pictures/turk.png"><p id="pPhoneNum">Cep Telefonu</p> -->
                    <input id="inputPhoneNum" type="number" name="Number" placeholder="Telefon Numarası"
                      size="30" required requiredplaceholder=""></td>
                </tr>
                <tr class="row">
                  <td class="input"> <input type="email" required placeholder="E-Mail"
                      name="email" id="idemail" requiredsize="30"></td>
                </tr>
                <tr class="row">
                  <td class="input"> <input type="password" required placeholder="Şifre"
                      name="password" id="idemail" requiredsize="30"></td>
                </tr>
                <tr class="row">
                  <td class="input"> <input type="password" required placeholder="Şifre Tekrar"
                      name="passwordAgain" id="idemail" requiredsize="30"></td>
                </tr>
                <tr class="row">
                  <td colspan="2"><input class="check" type="checkbox">
                      Kampanyalardan haberdar olmak için elektronik ileti almak istiyorum.</td>
                </tr>
                <tr class="row">
                  <td colspan="2"><input class="check" type="checkbox">
                    KVKK Aydınlatma Metnini Okudum, Kabul Ediyorum.</td>
                </tr>
                <tr class="row">
                  <td><input id="RegisterButton" type="submit" value="Kaydet"></td>
                </tr>
              </table>
        </form>
      </div>
      
  </body>
</template>
<style scoped>
#subdiv ul li h4{
  margin-top: 0px;
}
.form1{
  margin-left: 150px;
}
.form1 .register .row td{
  padding: 10px;
}
.form1 .register .row td input{
  padding: 7px;
}
.picexp{
  margin-top: 60px;
}
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
#liselectDay{
    margin-top: -30px;
    padding-bottom: 10px ;
    margin-left: -110px;
}
#liselectMonth{
    margin-top: -30px;
    margin-left: -10px;
    padding-bottom: 10px ;
}
#selectMonth,#selectDay{
    height: 59px;
    width: 100px;
}
#liYear{
    margin-top: -31px;
}
#year{
    width: 175px;
    margin-left: -25px;
}
#selectGender{
    padding: 15px;
    width: 280px;
}
#inputPhoneNum{
    padding-top: 10px;
}
/*
#pPhoneNum{
    position: absolute;
    top: 330px;
    left: 20px;
}
#imgTurkBayragi{
    position: absolute;
    top: 350px;
    left: 17px;
    width: 10px;
    height: 5px;
}*/
#RegisterButton{
    background-color: hsl(34, 82%, 51%);
    width: 280px;
    height: 40px;
}
#reset{
    background-color: transparent;
    border: transparent;
}
p{
    margin-top: 13px;
}
#right-asside p{
    font-size: 10px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    text-align: center;
    color: lightslategrey;
}
.check{
    width: 10px;
    height: 10px;
}
input{
    width: 380px;
    height: 40px;
}
#selectGender{
  width: 400px;
  height: 60px;
}
table {
    padding-top: 10px;
}
#left-asside{
    width: 40%;
    float: left;
    margin: 10px;
    padding: 10px;
    position: relative;
    /*left: 20%;*/
}
#right-asside{
    width: 50%;
    margin: 10px;
    margin-top: 10%;
    padding: 10px;
    padding-right: 5%;
    float: right;
}
#right-asside img{
    width: 100%;
    height: auto;
}

/*
#pageContent{
    width:60%;
    min-height: 700px;
    margin: 10px;
    padding: 10px;
    float: left;
    position: relative;
    left: 4%;
    background: url("pictures/background.png");
    background-repeat: repeat-y;
    background-position: center;
}*/
</style>
