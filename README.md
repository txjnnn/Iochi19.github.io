
<html lang="en">
   
    <html>
<head>
      <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="/jquery/jquery-1.11.1.min.js"></script>
    <script type="text/javascript"> 
        $(document).ready(function(){
             $(this).css({
                "color": "red",      
                "font-size": "24px" 
        });
    </script>
    <style type="text/css"> 
        body {
            font-family: Arial, sans-serif;
            background-color: #F0F8FF;
            margin: 0;
            padding: 0;
        }

        header#myHeader {
            background-color: #7FFFD4;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        /* 默认显示标题 */
        header#myHeader {
            display: block;
        }

        .container {
            /* 其他样式规则 */
        }

       
        .left-image, .right-content {
            flex: 1;
            padding: 10px;
        }

        .left-image img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
        }

        .right-content p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>

</head>
<body>
         
<header id="myHeader">
      <h1>歡迎來到我的自我介紹</h1>
    </header>
    
    <div class="container">
        <div class="left-image">
            <img src="https://i01piccdn.sogoucdn.com/361638c1196687e4" alt="左側圖片">
        </div>
        <div class="right-content">
            <h2>關於我</h2>
            <p>資工二甲 陳宥旭 <br>程式練習生<br>練習時長兩年半<br>喜歡唱、跳、RAP、籃球</p>

            <h2>我的經歷</h2>
            <p>CSO有龍炮<br>國二數學考過100分<br>從第七階樓梯跳下來撞到頭縫五針</p>

            <h2>聯絡我</h2>
            <p>如果你想與我聯絡，請使用以下方式：</p>
            <ul>
                <li>Email: danielz88920@gmail.com</li>
                <li>IG: <a href="https://www.instagram.com/anthonyz889/">LinkedIn Profile</a></li>
                
            </ul>
              
     
    </div>
</body>
</html>
