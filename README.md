<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROJECT.NEW1</title>
</head> 
<link rel="stylesheet" href="CSS/STYLE.CSS">
<STYle>
    *{margin: 0%;
    padding: 0%;}
     .backgroundimg{
        background: url(bg.jpg);
        width: 1265px;
        height: 570px;
        background-size: cover;
        background-repeat: no-repeat;

     }
     .left{
        display: inline-block;
        border: px solid;
        position: absolute;
        left: 1225px;
        top: 25px;

     }.right{
        display: inline-block;
        border: px solid;
        position: absolute;
        left: 10px;
        top: 12px;
     }
     .mid{
        display: inline-block;
        border: px solid;
        position: absolute;
        left: 400px;
        top: 7px;
        width: 500px;
       height: 34px;
       font-family:fantasy;
       font-size:20px;}
        

     .nevigation {
        display: inline-block;

     }
     .nevigation,li {
        display: inline-block;
        
     }
     .nevigation,li,a {
        text-decoration-line:none;
        padding: 16px;
        margin: -11px;
        color: black;
        font-weight: 500;
        color: #e60404;
    } 
    .right{
        background: url(logo.jpg);
        background-size:cover;
        background-repeat: no-repeat;
        position: absolute;
        padding: 25px;
        margin: 25px;
        width: 88px;
        height: 95px
    }   
     .left{
        position: absolute;
        display: inline-block;
        padding: 10px;
        margin: 20px;
        left: 1077px;
        top: -40px;
        font-size: 41px;
     }
    .left,button{
        color: brown;
        
     }
     form{
      border: 11px solid rgb(32, 211, 15);
      position: absolute;
      top: 217px;
      left: -317px;
      padding-top: 291px;
     padding-left: 336px;
      border-radius: 35px;
     }
     .name{
      top: 110px;
      right: 134px;
      position: absolute;
      width: 193px;
      height: 28px;
      border-radius:8px ;
     }
    h2{
      display: inline-block;
      top: 7px;
      right: 10px;
      position: absolute;
      width: 288px;
      height: 28px;
       
     }
     .Age{
      display: inline-block;
      position: absolute;
      top: 148px;
      right: 134px;
      width: 193px;
      height: 28px;
      border-radius:8px ;

     }
     .Gender{
      display: inline-block;
      position: absolute;
      top: 185px;
      right: 134px;
      width: 193px;
      height: 28px;
      border-radius:8px ;

     }
     .contact{
      display: inline-block;
      position: absolute;
      top: 223px;
      right: 134px;
      width: 193px;
      height: 28px;
      border-radius:8px ;

     }
     .submit{
      position: absolute;
      right: 39px;
      top: 250px;
      width: 64px;
    height: 23px;
    border-radius: 5px;
     }
     .new{
      top: 12px;
     }
    .nevigation,ul,li,a:hover, .nevigation,ul,li,a.active{
      color: black;
      text-decoration: underline;
    }
    .NAG{
      color: rgb(179, 0, 255);
      display: inline-block;
      top: 39px;
      right: -42px;
      position: absolute;
      width: 288px;
      height: 28px;
       
    }
    .abhhh{
      border: solid black;
    }
    .line1{
      position: relative;
      left: 1042px;
      top: 203px;
      padding: 0px;
      margin: 0px;
      border: solid 3px red;
      width: 211px ;
      animation-name: m;
      animation-duration: 9s;
      animation-iteration-count: 3999;
    }
    @keyframes m {
        0%{
            top:240px;
            left:900px;
        }
        25%{
            top: 250px;
            left: 950px;
        }
        75%{
            top: 300px;
            left: 1000px;
        }
        100%{
           outline-width: 300px;
            left: 1000px;
        }
        
                   }
    @keyframes m1{
        from {
           height:200px;
       }

        to {
            height:40px;
        }
      }

</STYle>
<body>
    <div><div class="backgroundimg"><div class="line1"
      >line</div></div></div>
    <div class="left"><button>Email</button>
                      <button>Contact US</button></div>
    <div class="right"></div>
    <div class="mid">
        <ul class="nevigation"  >
            <li><a href="" class="active">HOME</a></li>
             <li><a href="">ABOUNT US</a></li>
            <li><a href="">FITNESS CLCULATOR</a></li>
            <li><a href="">CONTACT US</a></li></ul>
            <form action="project.php" >
               <h2>Join The Best Gym Of </h2>
               <h1 class="NAG">NAGPUR</h1>
               <div >
               <input type="text" placeholder="Enter Your Name" class="name">
              </div>
              <div>
               <input type="number" placeholder="Enter Your Age" class="Age" >
              </div>
              <div>
               <input type="text" placeholder="Enter Your Gender" class="Gender">
              </div>
              <div>
               <input type="number" placeholder="Enter Your Contact" class="contact">
              </div>
              <div>
               <button class="submit">Submit</button>
              </div>
            </form>
         </div>
              <div></div>
</body>
<body>
   <h1 class="abhhh">hhh</h1>

</body>
</html>
