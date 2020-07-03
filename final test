<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>練習作業</title>
    <style type="text/css">
    * {
            /*消除網頁邊框*/
            margin: 0;
            padding: 0;
            list-style: none;
        }
        
        .header {
            height: 80px;
            background-color: black;
            position: relative;
        }
        
        .btn {
            width: 40px;
            height: 40px;
            background-color: rgb(41, 19, 59);
            display: block;
            /*規定元入以區塊方式呈現*/
            position: absolute;
            /*相對於他的父元素進行絕對定位*/
            top: 5px;
            right: 10px;
        }
        
        .btn span {
            opacity: 0;
            /*區塊內透明*/
            width: 1px;
            height: 1px;
            display: block;
            overflow: hidden;
            /*自動隱藏超出的文字或圖片*/
        }
    }
    nav {
        width: 30%;
        height: 100vh;
        /*view height是螢幕可是範圍高度的百分比*/
        
        background-color: #251323;
        position: absolute;
        top: 50px;
        left: -100%;
    }
    nav a {
        /*設置裡面的超連結*/
        
        display: block;
        /*link變直排*/
        
        text-decoration: none;
        color: #da0f0f;
        padding: 10px 20px;
        border-bottom: 1px solid #e4a9f0;
    }
    nav a:hover {
        color: rgb(75, 57, 33);
    }
    #menu {
        position: absolute;
        /*讓最上方的checkbox隱藏*/
    }
    #menu:checked~.header nav {
        left: 0;
    }
    img {
        vertical-align: bottom;
    }
    .item-group {
        width: 100%;
        max-width: 1400px;
        margin: auto;
    }
    .bg img {
        width: 100%;
    }
    .footer {
        background-color: rgb(52, 9, 58);
        color: #aaa;
        text-align: center;
        padding: 10px 0;
    }
    .title h2 {
        text-align: center;
        font-size: 36px;
        margin: 0 0px 10px;
    }
    .title {
        margin: 0 0px 10px;
        padding: 20px 10px;
        background-color: rgb(194, 207, 11);
    }
    .title p {
        font-size: 18px;
        text-align: center;
    }
    .item {
        margin: 0 10px 20px;
    }
    .item .text h1 {
        font-size: 30px;
        text-align: left;
    }
    .item .pic img {
        /*設置全圖片*/
        
        width: 80%;
    }
    .item .b {
        /*設置全圖片*/
        
        width: 30%;
    }
    .two {
        margin: 40px 0;
        background-color: blue;
    }
    @media screen and (min-width:768px) {
        /*設定桌電及平板顯示*/
        
        .item-group {
            display: flex;
            /*彈性盒子  又稱flexbox*/
        }
        
        .btn {
            display: none;
        }
        
        .header {
            display: flex;
            justify-content: space-between;
            /*分散對齊*/
            align-items: center;
        }
        
        nav {
            position: relative;
            left: 0;
            display: flex;
            width: auto;
            height: auto;
            top: 0;
            background-color: transparent;
            /*透明顏色*/
        }
        
        nav a {
            border-bottom: none;
        }
    }
    .two .item {
        display: flex;
        margin: 0;
    }
    .two .item .pic,
    .two .item .text {
        width: 150%;
        margin-left: 0;
        margin-right: 2cm;
        line-height: 2em;
        text-align: center;
    }
    .pic1 {
        width: 50%;
        margin-left: 20px;
    }
    .two .item .text {
        display: flex;
        padding: 0 10px;
        box-sizing: border-box;
        flex-direction: column;
        justify-content: center;
        text-align: left;
    }
    .a {
        margin: 0 0px 10px;
        padding: 20px 10px;
        background-color: rgb(12, 179, 221);
    }
    .a p {
        font-size: 18px;
        text-align: center;
    }
    .video-container {
        position: relative;
        padding-bottom: 56.25%;
        padding-top: 30px;
        height: 0;
        overflow: hidden;
    }
    .video-container iframe,
    .video-container object,
    .video-container embed {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    .p h3 {
        font-size: 24px;
        text-align: left;
        margin: 20px 0px 10px;
    }
    .p p {
        margin: 0px 0px 20px;
    }
    .p {
        background-color: rgb(191, 191, 235);
        color: rgb(35, 5, 63);
    }
    .left,
    .right {
        margin: 20px;
        float: none;
        width: 85%;
        height: auto;
    }
    .linehigh {
        line-height: 30px;
    }
    .member {
        font-size: 20px;
        line-height: 1em;
        font-family: Microsoft JhengHei;
    }
    </style>
</head>

<body>
    <input type="checkbox" name="" id="menu">

    <div class="header">

        <label for="menu" class="btn"> 
            <span>選單</span>
        </label>
        <nav>
            <a href="#1"><b style="font-family:Microsoft JhengHei;color: white;">關於小松菜奈</b></a>
            <a href="#2"><b style="font-family:Microsoft JhengHei;color: white;">推薦電影內劇照:明天，我要和昨天的妳約會</b></a>
            <a href="#3"><b style="font-family:Microsoft JhengHei;color: white;">預告片</b></a>
        </nav>
    </div>





    <div>
        <br>
    </div>
    <a name="1">
        <div class="title ">
            <h2>關於小松菜奈</h2>
            <p style="margin-left: 100px;margin-right: 100px;"><span style="font-family:Microsoft JhengHei;line-height: 2em; ">小松菜奈（Komatsu Nana，1996年2月16日-），出生於日本東京都，平面模特、演員。 她於2008年以模特身份出道，隨後相繼出演《肥 皂泡》《渴望》《近距離戀愛》《來了》等電影，曾獲第38屆日本電影學院獎最佳新演員獎、第38屆橫濱電影節最優秀新人獎等獎項。 身高168公分、血型O型、星座水瓶座。雙親分別是佐賀縣與沖繩縣人[2]。家中除了爸媽外還有兩位兄弟。日本本州山梨縣內的帝京第三高中畢業[3]，曾是啦啦隊[4]隊員。 與同是模特兒的emma感情很好，曾一起去韓國旅行，彼此的暱稱為「えまなな」(Emma
                Nana)。另一位感情很好的圈內好友為清野菜名，因菜名的日文音同菜奈，故彼此常稱對方為「こっちゃん」（小松）、「せっちゃん」（清野）。欣賞的女演員為蒼井優。
            </span></p>
        </div>
    </a>



    <div class="a">
        <a name="2">
            <p><b><span style="font-family:Microsoft JhengHei;"><font size="30px">推薦電影內劇照:明天，我要和昨天的妳約會</font></span></b></p>
    </div>
    </a>
    <a name="3">
        <div class="item-group ">


            <div class="item ">
                <div class="pic ">
                    <img src="data:image/jpeg;base64,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">
                </div>
                <div class="member">

                    <h4><span style="font-family:Microsoft JhengHei;"><font color="white"><br></font></span></h4>
                    <p>
                        <span style="font-family:Microsoft JhengHei;"><font color="white"><br></span></font>
                    </p>
                </div>
            </div>

            <div class="item ">
                <div class="pic ">
                    <img src="data:image/jpeg;base64,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">
                </div>
                <div class="member">

                    <h4><span style="font-family:Microsoft JhengHei;"><font color="white"><br></font></span></h4>
                    <p>
                        <span style="font-family:Microsoft JhengHei;"><font color="white"><br></span></font>
                    </p>
                </div>
            </div>
            <div class="item ">
                <div class="pic ">
                    <img src="data:image/jpeg;base64,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"
                        width=>
                </div>
                <div class="member">

                    <h4><span style="font-family:Microsoft JhengHei;"><font color="white"><br></font></span></h4>
                    <p>
                        <span style="font-family:Microsoft JhengHei;"><font color="white"><br></span></font>
                    </p>
                </div>
            </div>
            <div class="item ">
                <div class="pic ">
                    <img src="data:image/jpeg;base64,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">
                </div>
                <div class="member">

                    <h4><span style="font-family:Microsoft JhengHei;"><font color="white"><br> </font></span></h4>
                    <p>
                        <span style="font-family:Microsoft JhengHei;"><font color="white">​<br></span></font>
                    </p>
                </div>

            </div>
        </div>
        </div>

    </a>
    <a name="4">
        <a name="4"></a>
        <div class="a">
            <p><b><span style="font-family:Microsoft JhengHei;"><font size="30px">電影預告:明天，我要和昨天的妳約會</font></span></b></p>
        </div>

        <div class=video-container>
            <iframe width="1195" height="672" src="https://www.youtube.com/watch?v=2TKt5VEGZQQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="p ">
            <h3 style="text-align: center;font-family:Microsoft JhengHei;">明天，我要和昨天的妳約會</h3>
            <h4 style="text-align: center;font-family:Microsoft JhengHei;">電影是改編自七月隆文的同名小說

            </h4>
            <p style="margin-right: 100px;margin-left: 100px;line-height: 2em;font-family:Microsoft JhengHei;">故事在敘述就讀京都美術大學的南山高壽 在一次上學搭電車的途中 對一位女孩福壽愛美一見鐘情並主動上前搭訕 並詢問對方明天能否能再見面 但對方點頭答應的同時卻也淚流滿面 而之後高壽在好友上山的幫助之下 成功追到心儀的女人愛美並開始交往
            </p>
        </div>

        <div class="footer">
            &copy; B10856051。
        </div>

    </a>




</body>

</html>
