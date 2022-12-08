<template>
<div>
<div class="top-asside">
        <div id="subdiv">
            <ul>
                <li><img id="picexp" src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/vitrin/firat/v4/titleico.png"></li>
                <li id="subdiv2">
                    <h4>ÇOK SATAN KİTAPLAR</h4>
                </li>
                <li><img id="picexp" src="https://cdn.bkmkitap.com/theme/v4-bkmkitap-yeni/sub_theme/vitrin/firat/v4/titleico1.png"></li>
            </ul>
        </div>
    </div>
    <br><br><br>
    <div id="books">
      <Bookview pic='https://cdn.bkmkitap.com/yildizlarin-laneti-ciltli-8977253-57-K.jpg' bookName='Yıldızların Laneti Ciltli' author='Sena Nur Işık' publisher='İndigo Kitap' price='19.99₺'/>
      <Bookview pic='https://cdn.bkmkitap.com/karamazov-kardesler-142772-8828402-14-B.jpg' bookName='Sefiller 2 Cilt Takım' author='Victor Hugo' publisher='İş Bankası Kültür Yayınları' price='27,00'/>
      <Bookview pic='https://cdn.bkmkitap.com/sefiller-2-cilt-takim-152098-8741888-15-B.jpg' bookName='Karamazov Kardeşler' author='Dostoyevski' publisher='İş Bankası Kültür Yayınları' price='16,00'/>
      <Bookview pic='https://cdn.bkmkitap.com/toprak-ana-8632305-82-B.jpg' bookName='Toprak Ana' author='Cengiz Aytmatov' publisher='Ötüken Neşriyat' price='6,60'/>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
import Bookview from '@/components/Bookview.vue'

export default {
  name: 'Home',
  components: {
    Bookview
  }
}
</script>
<style scoped>
    #subdiv {
        margin-left: 700px;
        margin-top: 100px;
        padding: 10px;
    }
    #subdiv ul{
      list-style-type: none;
      margin-left: -200px;
    }
    #subdiv ul li{
      float: left;
      padding: 5px;
    }
    #subdiv ul li h4{
      margin-top: 0px;
    }
    #subdiv ul li img{
      margin-top: 5px;
    }
    #books{
      margin-left: 20%;
    }
</style>
