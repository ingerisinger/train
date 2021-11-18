<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>奕璋的申請表</title>
    <script src="https://kit.fontawesome.com/a1daf5a8db.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500&display=swap" rel="stylesheet">
    <style type="text/css">
         *{
        padding:0;
        margin:0;
        list-style:none;
        box-sizing: border-box;
        font-family: 'Noto Sans TC', sans-serif;
    }
        body{
            background-color:white ;
            margin-top: 20px;
            
        }
        .wrap{
            width:1200px;
            display:flex;
            flex-wrap: wrap;
            margin:auto;
            
        }
        .item{
            background-image: linear-gradient(30deg,LightSteelBlue,transparent);
            width:50%;
            height:250px;
            border:2px solid white;
            padding:5px 10px;
            margin:10px 0px;
            border-radius:20px;
        }
        .header{
            background-image: linear-gradient(30deg,RoyalBlue,transparent) ;
            width:1200px;
            height:400px;
            margin:auto;
            border-radius: 10px;
        }
        .header .text{
            display:flex;
            align-items: center;

        }
        .header .text i{
            font-size: 30px;
            position:relative;
            top:25px;
            left:20px;
        }
        .header .text h2{
            position:relative;
            left:40px;
            top:25px;
            border-bottom: 2px solid black;;
        }
        .wrap .item h2{
            padding:5px 10px 5px 5px;
            background-color:Lavender ;
            border-radius: 10px;
        }
        .wrap .item p{
            padding:10px 5px;
            line-height: 2em;
        }
        .wrap .item h2:hover{
            background-color:CornflowerBlue;
            color:white;
        }
        .header .text2{
            background-color:white ;
            width:1100px;
            height:300px;
            border-radius: 20px;
            position:relative;
            left:50px;
            top:50px;
        }
       
       
        .header .text2 p{
            line-height: 3em;
            font-size: 18px;
            padding:20px;
            text-indent: 3em;
        }
        .wrap .item i{
            padding:5px;
        }
        .header .text h2:hover{
            color:RoyalBlue;
        }
        .header .text i:hover{
            color:RoyalBlue;
        }
        .footer{
            width:100%;
            padding:10px 5px ;
        }
        .footer ul{
            display: flex;
            justify-content: space-evenly;
        }
        .footer li{
            padding:10px 15px;
            background-color:Gainsboro ;
            border-radius: 10px;
            opacity:0;
            transition:0.8s;
            font-size: 26px;
        }
        .footer li:hover{
            opacity:1;
        }
      @keyframes ss{
          0%{transform:rotate(-10deg) ;}
          100%{transform:rotate(10deg) ;}
      }
      .item:hover .fas,.far,fab{
          animation: ss 0.5s linear infinite alternate ;
      }
    </style>
</head>
<body>
    <div class="header">
        <div class="text">
           <h3><i class="fas fa-user-circle"></i></h3> 
            <h2>個人簡介</h2> 
        </div>
        <div class="text2">
            <p> 我是陳奕璋，今年26歲，畢業於台灣師範大學人類發展與家庭學系。
                我畢業後在淡水的精英教育機構做夏令營的招生與網站的經營，做了近三年，覺得自己需要改變現在的生活狀態，所以辭職了，並且參加郵局的考試，結果是備取第一名，在等候的同時，覺得需要學習一技之長，剛剛弟弟的工作有接觸後端的資料庫處理，在他的邀請之下，接觸了html跟css等，學習的同時在youtube上看到彭彭大大的教學影片，覺得受益良多。
                    自己本身的興趣是看電影、打籃球、戶外踏青，希望可以多跟其他人交流，已精進自己網頁前端的能力，並順利找到相關類型的工作，給自己新的挑戰。
                </p>
        </div>

    </div>
    <div class="wrap">
        <div class="item">
            <h2><i class="far fa-lightbulb"></i>為什麼想成為前端、後端、或全端工程師？</h2>
            <p>之前有在網站後台編輯的經驗，想學習更多網站的架構，喜歡看到自己做出來的成品(視覺效果或動畫)，所以想成為前端的工程師，但同時也要了解後端的邏輯，在工作上才能更得心應手

            </p>
        </div>
        <div class="item">
            <h2><i class="fas fa-chalkboard-teacher"></i>
            </i>為了成為軟體工程師，曾經做過什麼努力？</h2>
            <p>1.為了考取相關證照，買書來研究 <br/>
              2.上網找尋程式相關資源做學習<br/>
              3.	會找些喜歡的網站(ex:cama/uniqlo/lativ)，並試著做做看</p>
               
        </div>
        <div class="item">
            <h2><i class="fas fa-search"></i>
            </i>如果參與這個計畫，會怎麼安排學習時間？</h2>
            <p>早上、下午、晚上各安排兩小時的時間進行學習</p>
        </div>
        <div class="item">
            <h2><i class="fab fa-leanpub"></i>
            </i>如果參與這個計畫，預期會碰到什麼困難？你打算怎麼解決它？</h2>
            <p>1.	因為非相關科系，對於資訊較底層的知識不甚熟悉，勢必會遇到一些沒聽過的專有名詞，遇到問題的時候，會先以google為主，如果真的不會，會主動請教助教或老師
                2.	如遇到臨時較緊急的事項影響學習的時間，會先以排開為原則，除非真的排不開
                </p>
        </div>
        <div class="item">
            <h2><i class="fas fa-building"></i></i>是否有想要加入的軟體公司？為什麼想加入該公司？</h2>
            <p>沒有特別想走軟體業，之後會想走偏程式教育的工作</p>
        </div>
        <div class="item">
            <h2><i class="far fa-meh-blank"></i>想要對我們說的事情？</h2>
            <p>期待跟你們一起學習、成長</p>
        </div>
        <div class="footer">
            <ul>
                <li>姓名:陳奕璋</li>
                <li>電子郵件:nba.com30@gmail.com</li>
                <li>手機:0971617386</li>
            </ul>
        </div>
    </div>
</body>
</html>
