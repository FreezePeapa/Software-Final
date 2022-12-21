<template>
  <body>
  <div id = "top">
    <div id = "red">
      <img id = "img1" src="@/assets/fcul_logo.png" />
    </div>  
  </div>
  <div id="header-inner">
    <img id = "img2" src="@/assets/bg_header.png" />
  </div>

  <div id = "main-wrapper">
    
    <h3>薦購服務說明</h3>   
    <ul style="list-style-type:disc">
      <li>教師每學期以薦購60種(件)或新台幣60,000元為原則。</li>
      <li>講座教授、特聘教授可薦購數量/金額為本校教師的2倍。</li>
      <li>學生每月以薦購5種(件)或新台幣5,000元為原則。</li>
      <li>本系統將自動追蹤您的薦購資料處理狀態，定期email通知。</li>
      <li>薦購期刊、電子資源請填寫薦購表(請參見公布欄)。</li>
    </ul>
    <h3>公布欄</h3>  
    <div id = "blue">
      <h1>推薦者登入 Login</h1>
      <input id="btn" type="button" value="NID登入" onclick="
              javascript:window.open('http://opendata.fcu.edu.tw/fcuOauth/Auth.aspx?client_id=637102957247.e9976f5b722a47a6af9beddfeadb70e4.recommend.lib.fcu.edu.tw&client_url=http://recommend.lib.fcu.edu.tw/weblink/scripts/weblink/oauth.aspx', '_top'
              , 'copyhistory=0' );">

      <h4>如何登錄系統</h4>
      <p>帳號：請輸入教職員/學生證號。 <br>
      密碼：請輸入NID密碼。(忘記密碼<br>
      請聯絡資訊處分機2712) <br>
      薦購服務相關問題請洽圖書館讀者 <br>
      服務組2682。
      </p>      
    </div>
  </div>
<div id = "bottom">
  <img id = "img3" src="@/assets/fcu_logos.png" />
</div>
</body>
</template>

<style type="text/css">
  *{
    padding: 0;
    margin: 0;
  }
    h1 {
        font-size: 22.5px;
        color: rgb(255, 255, 255);
        position: relative;
        top: 20px;
        left: 15px;
    }
    h3 {
      width: 150px;
      font-size: 22.5px;
      color: rgb(0, 0, 0);
      margin:30px;
      padding:0px;

    }
    ul li{
      font-size: 15px;
      width: 400px;
      position: relative;
      left: 65px;  
      margin-bottom: 20px;
    }
    #btn {
        width: 87px;
        height: 34px;
        font-size: 20px;
        position: relative;
        top: 50px;
        left: 100px;
    }
    h4 {
        font-size: 18px;
        color: white;
        position: relative;
        top: 70px;
        left: 15px;
    }
    p {
        font-size: 15px;
        color: white;
        position: relative;
        top: 85px;
        left: 40px;
    }

  body {
    background-color: #e9e9e9;
  }
    #top {
      width: 100%;
      height: 65px;
      background-color: #ffffff;
      border-bottom-style: solid;
      border-bottom-width: 0.2px;
      border-bottom-color: #A00000;
    }
   
    #header-inner{
      width: 100%;
      height: 70px;
      background-color: #e9e9e9;
      position: relative;
      z-index: 1;  
    } 
    #red {
      width: 56px;
      height: 64px;  
      background-color: #A00000; 
      position:relative;
      top: 0px;
      left: 300px;
    }
    #blue {    
      width: 284px;
      height: 352px;
      background-color: #00b9cf;
      border-radius: 15px;
      position: absolute;
      top: 35px;
      left: 630px;
   
    }
    #img1{
        width: auto;
        height: auto;
        position: relative;
        top: 8px;
        left: 12px;
    }   
    #img2{
        width: auto;
        height: auto;
        position: relative;
        top: 18px;
        left: 300px; 
    }
    #img3{
        width: auto;
        height: auto;
        position: relative;
        top: 18px;
        left: 280px; 
    }
    #main-wrapper {
        width: 950px;
        height: 570px;
        background-color: #ffffff;
        margin:0 auto;
        border-radius: 15px;
        border-style: solid;
        border-width: 0.2px;
        border-color: #D0D0D0;
        position: relative;
        z-index: 1; 
    }

    #bottom{
      width: 100%;
      height: 100px;
      background-color: #e9e9e9;
    }
</style>