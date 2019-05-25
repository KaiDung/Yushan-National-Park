
<html>
<style>
  
  body {
    background-image: url(https://i.imgur.com/THcKxtQ.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
    background-size: cover;
  }
  
  .blackborder{
    border:2px black solid;
  }
  
  p {
    font-family:"微軟正黑體";
    font-size: 18px;
  }
  
  h1{
    font-family:"微軟正黑體";
    font-weight:bold;
  }
  
  h2{
    font-family:"微軟正黑體";
    font-weight:bold;
  }
  
  td{
    font-family:"微軟正黑體";
    font-size:18px;
  }
  
  .button{
    background-color: #a0fdff;
    border: 2px solid black;
    color: #0645ad;
    padding: 8px 24px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
    display:block;
  }
  
  .button:hover {
    background-color: #A1D0FF;
  }
  
  #flip{
    background-color: #a0fdff;
    border: 2px solid black;
    color: black;
    padding: 8px 42px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
    display:block;
  }
  
  .button-bar {
    position:fixed;
    top: 5%;
    right: 5%;
  }
  * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,.dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }
    .tab {
        overflow: hidden;
         border: 1px solid #ccc;
         background-color: #f1f1f1;
    }
        /* Style the buttons inside the tab */
        
    .tab button {
        background-color: inherit;
         float: left;
         border: none;
         outline: none;
         cursor: pointer;
         padding: 14px 16px;
         transition: 0.3s;
         font-size: 17px;
     }
        /* Change background color of buttons on hover */
        
    .tab button:hover {
         background-color: #ddd;
    }
        /* Create an active/current tablink class */
        
     .tab button.active {
         background-color: #ccc;
     }
        /* Style the tab content */
        
    .tabcontent {
         display: none;
         padding: 6px 12px;
         border: 1px solid #ccc;
         border-top: none;
    }
  
</style>

<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script>
    $(document).ready(function() {
      $('#top').click(function () {
        $('html, body').animate({scrollTop: 0},1000);
      });
      $('#bottom').click(function () {
        $('html, body').animate({scrollTop:$(document).height()-$(window).height()}, 1000);
      });
      $('#a').click(function () {
        $('html, body').animate({scrollTop:$("#A").offset().top}, 1000);
      });
      $('#b').click(function () {
        $('html, body').animate({scrollTop:$("#B").offset().top}, 1000);
      });
      $('#c').click(function () {
        $('html, body').animate({scrollTop:$("#C").offset().top}, 1000);
      });
      $('#d').click(function () {
        $('html, body').animate({scrollTop:$("#D").offset().top}, 1000);
      });
      $('#e').click(function () {
        $('html, body').animate({scrollTop:$("#E").offset().top}, 1000);
      });
      $('#f').click(function () {
        $('html, body').animate({scrollTop:$("#F").offset().top}, 1000);
      });
      $("#flip").click(function(){
        $(".button").slideToggle("slow");
      });
    });
  </script>
</head>

<body>
  <div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'zh-tw', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

<h1 style="font-size:40px;text-align:center">玉山國家公園</h1>
<h1 id="A">基本資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
  
<p>玉山國家公園位居臺灣中央地帶，行政區域跨花蓮、高雄、南投、嘉義等四個縣市，地形可概分為<b>東埔山塊</b>、<b>玉山山塊</b>及<b>中央山塊</b>三大區，<b>亦為濁水溪、高屏溪及秀姑巒溪等溪流上游之重要集水區</b>。園區面積103,121.4公頃，擁有<b>東北亞第一高峰，海拔3,952公尺的玉山主峰</b>，植被隨海拔之變化而異，由亞熱帶、溫帶以至寒帶，園區面積約為臺灣面積的百分之三，卻有1923種被子植物、28種裸子植物、441種蕨類植物，177種苔蘚類植物，147種菌類；含括了臺灣半數以上的原生種植物。<br>
  
<br>玉山園區計有58種哺乳類動物，且大多數為行政院農業委員會公告之保育類野生動物，如臺灣野山羊、臺灣水鹿、台灣黑熊、台灣山羌、及台灣獼猴等，而園區內的鳥類種數亦有約196種之多，幾乎涵括臺灣森林性留鳥，其中包括黑長尾雉、藍腹鷳、臺灣噪鶥、藪鳥、冠羽畫眉等，臺灣特有種鳥類計有24種；園區內的高山溪流經查，計有12種淡水魚類。園區蝴蝶種數約285種，佔臺灣蝴蝶種數之一半以上；園區的爬蟲類計有18種，以阿里山龜殼花、梭德氏游蛇及斯文豪氏攀木蜥蜴等臺灣特有種較多；兩棲類計有13種，其中以一級保育類<b>阿里山山椒魚</b>及<b>楚南氏山椒魚</b>等百萬年前冰河孓遺生物，在地處亞熱帶的臺灣更屬難得珍貴，具有極高的學術研究價值。<br>

  <br>在人文史蹟方面，有<b>八通關古道</b>，為清領時期對臺灣經營，由消極抵制轉為積極開發的重要里程碑，另有日治時期所修築之八通關越道路、關山越道路等，為日治時期理蕃政策下的產物，且過去園區曾經是布農族人生活的領域，因此古道現今仍多處多分布農族舊社遺址，古道的遺址更訴說著許多布農族人奮勇抗日的感人事蹟。<br> </p>

<div class="tab">
        <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">西北園區</button>
        <button class="tablinks" onclick="openCity(event, 'Paris')">南部園區</button>
        <button class="tablinks" onclick="openCity(event, 'Tokyo')">東部園區</button>
        <button class="tablinks" onclick="openCity(event, 'one')">相關影音</button>
    </div>

    <div id="London" class="tabcontent">
        <h3><b>西北園區</b></h3>
        <p>本區位於玉山園區西北側，包括新中橫公路、塔塔加、東埔、觀高、八通關、玉山主峰、及楠溪林道等地區。玉山國家公園聯外道路 / 塔塔加遊憩路線圖 / 新中橫公路景點位置圖 。<br>
        <b>主要景觀資源：</b><br>東北亞第一高峰之玉山主峰、塔塔加分水嶺、楠梓仙溪、陳有蘭溪溪谷景觀、金門峒斷崖、父子斷崖、八通關分水嶺等地理地形景觀。 白木林景觀、冷杉、鐵杉、八通關草原等原始林景觀及高山寒原植物。另有陳有蘭溪、沙里仙溪等地區之原始針闊葉混含林帶，含有許多鳥類、蝴蝶、山羌、台灣獼猴等，為本區動植物資源豐饒地區。 人文景觀有玉山西峰山神廟、北峰頂的中央氣象局玉山氣象站、八通關古道及布農族原住民聚落。</p>
        <img src="https://i.imgur.com/pMkI6Hy.png">
    </div>

    <div id="Paris" class="tabcontent">
        <h3><b>南部園區</b></h3>
        <p>東沙島周邊海域有全國最大的海草床分布，面積約1,185公頃，是臺灣其他區域海草床加總起來的20倍之多。目前東沙紀錄有7種海草，包括單脈二藥草、圓葉水絲草、鋸齒葉水絲草、水韭菜、鐮葉叢草、泰來草和卵葉鹽草等，不僅提供多樣性海洋生物生活的空間，也是食物鏈中重要的基礎生產者，其年吸收碳量約為一萬公噸。東沙海域紀錄7種（世界海草種數約60種</p>
        <img src="https://i.imgur.com/m9G4CcN.jpg">
    </div>

    <div id="Tokyo" class="tabcontent">
        <h3><b>東部園區</b></h3>
        <p>東沙島的植物的分布類型可分為泛熱帶分布、熱帶舊世界分布及東南亞、西南太平洋諸島分布三種模式。東沙島是熱帶偏北的太平洋島嶼，面積小，氣候深受海洋影響，島上植被屬於熱帶海岸林，和鄰近的西沙群島、南沙群島或是海南島的種類多有相似之處，祇是某些植種的數量和分布有些許差異。主要分為沙灘植群，海岸灌叢與海岸林過度帶植物，海岸林植群，海岸灌叢植群</p>
        <img src="https://i.imgur.com/ec1mTiW.jpg">
    </div>


    <div id="one" class="tabcontent">
        <h3>相關影音</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/vy7UTgoQblQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <script>
        function openCity(evt, cityName) {
            var i, tabcontent, tablinks;
            tabcontent = document.getElementsByClassName("tabcontent");
            for (i = 0; i < tabcontent.length; i++) {
                tabcontent[i].style.display = "none";
            }
            tablinks = document.getElementsByClassName("tablinks");
            for (i = 0; i < tablinks.length; i++) {
                tablinks[i].className = tablinks[i].className.replace(" active", "");
            }
            document.getElementById(cityName).style.display = "block";
            evt.currentTarget.className += " active";
        }

        // Get the element with id="defaultOpen" and click on it
        document.getElementById("defaultOpen").click();
    </script>

<div class="slideshow-container">
  
   <div class="mySlides fade">
        <div class="numbertext">1 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_145847.76018.jpg">
        <div class="text"></div>
   </div>

   <div class="mySlides fade">
        <div class="numbertext">2 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_150432.67519.jpg" >
        <div class="text"></div>
    </div>

   <div class="mySlides fade">
        <div class="numbertext">3 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_145932.77331.jpg">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade">
        <div class="numbertext">4 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_152038.10492.JPG">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade">
        <div class="numbertext">5 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_151013.38455.jpg">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade">
        <div class="numbertext">6 / 6</div>
        <img style="width:100%;height:400px" src="https://www.ysnp.gov.tw/upload/images/20090722_145953.87867.jpg">
        <div class="text"></div>
    </div>
    
   <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
   <a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>

<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
    <span class="dot" onclick="currentSlide(6)"></span>
</div>


<script>
   var slideIndex = 1;
   showSlides(slideIndex);

   function plusSlides(n) {
        showSlides(slideIndex += n);
    }

   function currentSlide(n) {
        showSlides(slideIndex = n);
    }

   function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {
            slideIndex = 1
        }
        if (n < 1) {
            slideIndex = slides.length
        }
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
    }
</script>

</div>

<h1 id="B">國家公園標示意涵</h1>

<div style="background-color:#EEFFBB;border:2px black solid;padding:30px;">
<img style="width: 90px; height: 90px;" src="//i.imgur.com/1f6mKyq.png" align="left"><p>玉山國家公園管理處處徽呈現玉山國家公園範轄，有右邊的漢文化(圖騰)與左邊的原住民文化(圖騰)和諧共融，同時有靠人類的雙手及智慧共同維護這片好山好水下的動物植物等生物資源，讓大地生生不息。
</p>
</div>

<h1 id="C">公園特色介紹</h1>

<h2>一、玉山主峰標高3,952傲領群山</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<img class="blackborder" src="http://www.ysnp.gov.tw/resource/html/resource.ashx?path=images%252fsummary_pic_2.jpg" align="left"><p>玉山國家公園以玉山為名，此山系因歐亞、菲律賓板塊相擠撞而高隆，主稜脈略呈十字形，十字交點即為標高3,952公尺的主峰；園內超過3,000公尺且名列「臺灣百岳」的高山有30座，其中玉山東峰為陡立險峻的十峻之首、秀姑巒山是中央山脈第一高峰、關山是南臺首嶽、新康山為東臺一霸。
</p>
</div>

<h2>二、氣候垂直變化 園內育3大河</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<img class="blackborder" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Zhuoshui_River%2C_Nantou_County_%28Taiwan%29.jpg/220px-Zhuoshui_River%2C_Nantou_County_%28Taiwan%29.jpg" align="right"><p>玉山國家公園居臺灣中央地帶，海拔由拉庫拉庫溪谷之300公尺至玉山之3,952公尺主峰，差距高達3,600公尺，因此垂直變化出亞熱帶到亞寒帶，截然不同的氣候特性。海拔3,500公尺以上地區，年均溫為<b>5℃</b>，雪期由12月至翌年4月，而海拔2,500公尺以上地區，年均溫約<b>10℃</b>。</p>
<img class="blackborder" style="width:220px;height:146px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Old_Railway_Bridge_Across_Kao-Ping_River.jpg/300px-Old_Railway_Bridge_Across_Kao-Ping_River.jpg" align="left"><p>水文方面，玉山國家公園是一個良好而廣大的集水區，<b>是臺灣中、南、東部大河濁水溪、高屏溪、秀姑巒溪之發源地</b>。而園內登山者的良泉高山湖泊，則成因豐沛的雨水滲匯於凹地，若凹地下方為頁岩層等不透水岩層，即集匯成高山湖泊，如中央山脈的大水窟、嘉明湖，南橫的天池等都屬如此。
</p>
</div>

<h2>三、熱溫寒三帶植物分區生長</h2>

<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<img class="blackborder" style="width:180px;height:180px;" src="http://www.ysnp.gov.tw/resource/html/resource.ashx?path=images%252f01_5.jpg" align="left"><p>玉山園內山脈起伏劇烈，高聳入雲的山頭，被四周低地有效的孤立，代表著程度不一的隔離作用，因此物種多樣性低及特有種比例高，是高山生態的一大特色。再加上園區<b>垂直落差達3,600公尺</b>，各種亞熱帶到亞寒帶的典型林相交錯鑲嵌，可說是臺灣森林生態的縮影。植群帶涵蓋<b>熱帶雨林、暖溫帶雨林、暖溫帶山地針葉林、冷溫帶山地針葉林、亞高山針葉林及高山寒原</b>等，此區面積雖僅為臺灣的3%，但卻包含半數以上原生植物，不容小覷。
</p>
</div>

<h2>四、冰河時期山椒魚珍貴棲息</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<img style="width:220px;height:146px;" class="blackborder" src="https://www.ysnp.gov.tw/upload/images/20110815_095026.36308.JPG" align="left"><p>玉山垂直分布的氣候，使得林相豐富，不同植群帶內的植物長期競爭、消長、演替，提供了各種動物相異
的棲息空間和食物資源，使得本區生物有著不凡的多樣性。本區共約有50種哺乳動物，其中臺灣黑熊、長鬃
山羊、水鹿、山羌等是珍貴大型動物；鳥類約有151種，幾乎包括全臺灣森林中的留鳥，包括帝雉、藍腹鷴等
臺灣特有種。<br>
<br>而居於森林最底層的爬蟲類則有18種、兩生類13種，頭號珍貴的就屬曾是魚但卻長腳的<b>山椒魚</b>，這類動物和中國的娃娃魚是親戚，在145萬年前的侏羅紀地質年代時期即出現在地球上，是臺灣歷經冰河時期的活證據。
</p>
</div>

<h2>五、八通關古道是重要人文史蹟</h2>

<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<img style="width:220px;height:146px;" class="blackborder" src="http://www.ysnp.gov.tw/resource/html/resource.ashx?path=images%252fsummary_pic.jpg" align="left"><p>玉山地區由於山高地偏，但開發甚早，已在陳有蘭溪流域與拉庫拉庫溪流域瓦拉米、黃麻附近發現石器與陶器等史前遺址，證明本區至少在<b>1000年前已有人類活動</b>。近代定居族群幾乎都是布農族人，而人數不多的鄒族則世居在玉山西南側。秀姑巒山和玉山是臺灣的核心地區，歷史演進的軌跡，也在此發生流傳。1875年，清政府為屯墾及邊防需要，開闢一條穿越中央山脈的「中路」，這條約152公里的官道，就是目前<b>國定一級古蹟「八通關古道」</b>。而日治時期為鎮壓布農族人，另闢「八通關越橫斷道路」、「關山越警備道」，現今沿途「理蕃」的警備建設雖所存無幾，但已為殖民掠奪與原住民反抗下了一段歷史註腳。
</p>
</div>

<h1 id="D">交通資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<p>
  <table border="1" cellpadding="5" cellspacing="0" width="90%">
    <thead>
      <tr>
        <th width="100%">路線</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>新中橫公路：水里-玉山段（台21線</td>
      </tr>
      <tr>
        <td>南投水里─（30K）→和社─（43K）→塔塔加遊客中心</td>
      </tr>
      <tr>
        <td>和社-東埔線（投60）</td>
      </tr>
      <tr>
        <td>南投水里─（30K）→和社─（8K）→東埔</td>
      </tr>
      <tr>
        <td>新中橫公路：嘉義-玉山段（台18線）</td>
      </tr>
      <tr>
        <td>嘉義─（75K）→阿里山─（21K）→塔塔加遊客中心</td>
      </tr>
    </tbody>
  </table>
</p>
</div>

<h1 id="E">住宿資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
  <p><b>阿里山國家風景區</b></p>
  <p>
    <table border="1" cellpadding="5" cellspacing="0" width="90%">
      <thead>
        <tr>
          <th width="33%">飯店名稱</th>
          <th width="33%">飯店地址</th>
          <th width="33%">聯絡電話</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>阿里山旅客服務中心</td>
          <td>嘉義縣阿里山鄉中正村東阿里山59號</td>
          <td>(05)2679-917</td>
        </tr>
        <tr>
          <td>阿里山賓館</td>
          <td>嘉義縣阿里山鄉香林村16號</td>
          <td>(05)2679-811</td>
        </tr>
        <tr>
          <td>阿里山青年活動中心</td>
          <td>嘉義縣阿里山鄉香林村二萬坪106號</td>
          <td>(05)2679-561</td>
        </tr>
        <tr>
          <td>阿里山警光山莊</td>
          <td>嘉義縣阿里山鄉中正村東阿里山62號</td>
          <td>(05)2679-975</td>
        </tr>
        <tr>
          <td>大峰渡假山莊</td>
          <td>嘉義縣阿里山鄉中正村46號</td>
          <td>(05)2679-769</td>
        </tr>
        <tr>
          <td>文山賓館</td>
          <td>嘉義縣阿里山鄉中正村40號</td>
          <td>(05)2679-712</td>
        </tr>
      </tbody>
    </table>
  </p>
  
  <p><b>東埔溫泉風景區</b></p>
  <p>
    <table border="1" cellpadding="5" cellspacing="0" width="90%">
      <thead>
        <tr>
          <th width="33%">飯店名稱</th>
          <th width="33%">地址</th>
          <th width="33%">聯絡電話</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>東埔警光山莊</td>
          <td>南投縣信義鄉開高巷54號</td>
          <td>（049）270-1715</td>
        </tr>
        <tr>
          <td>東光大飯店</td>
          <td>南投縣信義鄉開高巷72之2號</td>
          <td>（049）270-1105</td>
        </tr>
        <tr>
          <td>帝綸溫泉大飯店</td>
          <td>南投縣信義鄉開高巷86號</td>
          <td>（049）2701-616~8</td>
        </tr>
        </tbody>
     </table>
  </p>
</div>

<h1 id="F">美食資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
  <p><b>下列是玉山國家公園-水里遊客中心附近的餐廳</b></p>
  <p>
    <table border="1" cellpadding="5" cellspacing="0" width="90%">
      <thead>
        <tr>
          <th width="33%">店名</th>
          <th width="33%">地址</th>
          <th width="33%">聯絡電話</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>野鴨谷餐廳</td>
          <td>水里鄉中山路一段265號</td>
          <td>(04)9277-5416</td>
        </tr>
        <tr>
          <td>水里羊肉王山產餐廳</td>
          <td>水里鄉中山路二段65號</td>
          <td>(04)9277-0618</td>
        </tr>
        <tr>
          <td>董家肉圓</td>
          <td>水里鄉民族街205號</td>
          <td>(04)9277-0355</td>
        </tr>
        <tr>
          <td>永記燒臘小吃</td>
          <td>水里鄉中正路187號</td>
          <td>(04)9277-1935</td>
        </tr>
        <tr>
          <td>水里豆花松</td>
          <td>水里鄉民族路230號</td>
          <td>(04)9277-1048</td>
        </tr>
      </tbody>
    </table>
  </p>
</div>

<h1>資料來源</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
  <a href="https://www.ysnp.gov.tw/default.aspx">玉山國家公園</a><br>
  <a href="https://zh.wikipedia.org/wiki/%E9%AB%98%E5%B1%8F%E6%BA%AA">維基百科-高屏溪</a><br>
  <a href="https://zh.wikipedia.org/wiki/%E6%BF%81%E6%B0%B4%E6%BA%AA">維基百科-濁水溪</a><br>
  <a href="https://npgis.cpami.gov.tw//public/detail/SpeciesDetail.aspx?SP_ID=M0047#">台灣國家公園生物多樣性資料庫與知識平台-台灣黑熊</a><br>
  <a href="https://npgis.cpami.gov.tw//public/detail/SpeciesDetail.aspx?SP_ID=B0152">台灣國家公園生物多樣性資料庫與知識平台-黑長尾雉</a><br>
  <a href="http://np.cpami.gov.tw/">台灣國家公園</a>
  <a href="https://www.tripadvisor.com.tw/RestaurantsNear-g13806888-d510033-Yushan_National_Park-Shuili_Nantou.html">Top 10 玉山國家公園附近最佳餐廳- TripAdvisor</a>
</div>

</body>

<div class="button-bar">
<a id ="flip">選單</a>
<a class="button" id="a" href="#">基本資訊</a>
<a class="button" id="b" href="#">標示意涵</a>
<a class="button" id="c" href="#">特色介紹</a>
<a class="button" id="d" href="#">交通資訊</a>
<a class="button" id="e" href="#">住宿資訊</a>
<a class="button" id="f" href="#">美食資訊</a>
<a class="button" id="top" href="#">網頁頂端</a>
<a class="button" id="bottom" href="#">網頁底部</a>
<a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>

</html>
