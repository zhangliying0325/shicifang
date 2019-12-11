<!-- 这是头条已登录的页面 -->
<template>
  <div id="headline-top">
    <nav class="navbar  navbar-fixed-top" role="navigation">
        <div class="container">
          <div class="navbar-header">
            <a href="#" class="navbar-brand"> 
                <img id="headlogo" src="../images/asset-logo-black.png" alt="十次方logo">
            </a>
          </div>
          <div id="navbar" class="collapse navbar-collapse">
            <ul class="nav navbar-nav" id="nav-barText">
              <li class="active" id="headlineText" style="color: red;"><a href="#">头条</a></li>
              <li><a href="#" id="headlineText">问答</a></li>
              <li><a href="#" id="headlineText">活动</a></li>
              <li><a href="#" id="headlineText">交友</a></li>
              <li><a href="#" id="headlineText">吐槽</a></li>
              <li><a href="#" id="headlineText">招聘</a></li>
            </ul>					
          </div>
          <form class="headlineSearch">
              <input style="border-radius: 50px;width: 260px; height: 40px;" type="text" placeholder="   请输入关键字...">
              <span id="search"class="glyphicon glyphicon-search"></span>
          </form>    
          <div id="headlinetop-right">
              <a href="#" id="advice">通知</a>
              <span style="position: relative;top: -25px; left: -30px;" class="glyphicon glyphicon-plus"></span>
              <img style="position: relative; top: -25px;" src="../images/widget-widget-photo.png" alt="个人">
          </div>      
        </div>			
      </nav>
    </div>
</template> 

<script>
  
</script>

<style>
     #headline-top{
      margin: 0px auto;
      background-color: whitesmoke;
      margin: 0px;
      height: 100%;
      font-family: "微软雅黑";
     }
     .navbar-fixed-top{
      background-color: whitesmoke;
     }
     #nav-barText li{
       position: relative;
       bottom: -13px;
       right: 5px;
       padding-right: 13px;
     }
     #headlineText{
       color: black;
       font-size: 20px;
     }
    .headlineSearch{
      float: right;
      position: relative;
      top: -30px;
      right: 190px; 
    }
    #search{
      position: relative;
      left: -30px;
    }
    #headlinetop-right{
      float: right;
      position: relative;
      right: -400px;
    }
    #advice{
      position: relative;
      right: 60px;
      top: -25px;
      font-size: 15px;
      color: black;
    }
    

   
</style>
