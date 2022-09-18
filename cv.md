#Yulia Shashkina Junior Front-end developer#
[Newdream175@gmail.com](Newdream175@gmail.com)
+7(929)541-84-83

##About myself##
Good afternoon! My name is Julia and I'm just starting to learn! I don’t set myself the goal of training and finding a job, I just like the process of learning something new. At school my favorite subject was math, I enjoyed solving problems. Unfortunately, life turned out in such a way that I did not have the opportunity to get a decent education. I built a career in management and achieved a lot, in this branch of development nothing motivates or attracts me anymore. Now I have challenged myself, I want to develop my intellectual skills in programming. I took a short course on Html and CSS and found the layout process very exciting and I want to move on.

###Books:###
Kirupa Chinnathambi "JavaScript Absolute Beginner's Guide"
david sawyer mcfarland "CSS: The Missing Manual"
Aditya Bhargava "Grokking Algorithms"

###Skills:###
HTML
css
SASS
Bootstrap
English Beginner

##Education:##
RMAT - Management (Bachelor)
Training center "Specialist" - Fundamentals of programming and databases

##Code examples##
###Html###
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--font-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+SC:wght@300;400;500&family=Fredericka+the+Great&family=Open+Sans:wght@300&family=Poiret+One&family=Roboto&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="Roboto-Regular.ttf">
     <!--style-->
    <link rel="stylesheet" href="style_3.css">
    <title>Личный сайт</title>
 
</head>
<body>
    <div class="conteiner row">
        <header class="header row">
            <h1 class="col title col-7 FrederickatheGreat-Regular">Personal site</h1>
            <nav class="col nav col-5">
                <ul>
                    <li class="button"><a href="index_1.html">О себе</a></li>
                    <li class="button"><a href="index_2.html">Мои увлечения</a></li>
                    <li class="button"><a href="index_3.html">Обратная связь</a></li>
                </ul>
            </nav>
        </header>
        <main class="content">
                <form class="form" action="/my-handling-form-page" method="post">
                    <ul>
                        <li>
                          <label for="name">Имя:</label>
                          <input type="text" id="name" name="user_name">
                        </li>
                        <li>
                          <label for="mail">E-mail:</label>
                          <input type="email" id="mail" name="user_mail">
                        </li>
                        <li>
                            <select>
                                <option value="">Что вам понравилось на сайте</option>
                                <option value="Оформление">Оформление</option>
                                <option value="Истории">Истории</option>
                                <option value="Реализайия">Реализайия</option>
                            </select>
                        </li>
                        </li>
                        <li>
                          <label for="msg">Пожелания:</label>
                          <textarea id="msg" name="user_message"></textarea>
                        </li>
                        <li class="button_form" >
                            <button id="button_form" type="submit">Отправить обратную связь</button>
                          </li>
                      </ul>
                </form>
        </main>
        <footer class="row">
            <div class="col col-4">
                <p id="text_footer">Phone number: 8(981)750-29-65</p>
            </div>
            <div class="col col-4">
                <a href="https://vk.com/idontknow"><img src="img\vk-gray.png" onmouseover="this.src='img/vk-white.png';" onmouseout="this.src='img/vk-gray.png'"width="40px" alt="" id="img_footer"></a>
                <a href="https://instagram.com/shashkin_dima?utm_medium=copy_link"><img src="img\inst-gray.png" onmouseover="this.src='img/inst-white.png';" onmouseout="this.src='img/inst-gray.png'" width="40px" alt="" id="img_footer"></a>
                <a href="#"><img src="img\tw-gray.png" onmouseover="this.src='img/tw-white.png';" onmouseout="this.src='img/tw-gray.png'" width="40px" alt="" id="img_footer"></a>
                <a href="#">    <img src="img\fb-gray.png" onmouseover="this.src='img/fb-white.png';" onmouseout="this.src='img/fb-gray.png'" width="40px" alt="" id="img_footer"></a>             
             </div>
            <div class="col col-4">
                <p id="text_footer">reallyrofl@gmail.com</p>               
            </div>
            
        </footer>
    </div>
</body>
</html>```
###CSS###
```* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
body{
    background-color: #E0D0B9;
}
.conteiner{
    width: 1200px;
    margin: auto; 
    display: block;
}

/*Header*/
.header{
    height: 110px ;
    margin-top: 30px;
    display: flex;
    flex-flow: row wrap;
    padding: 20px 0;
    border-top: 3px solid #533632;
    border-bottom: 3px solid #533632;
}
.header h1{
    font-size: 55px;
    font-family: 'Fredericka the Great'; 
    color: #533632;
}
.nav{
    margin-top: 25px;
}
.nav ul li{
    list-style-type: none;
    display: inline;
    padding: 10px;
    margin: 5px ;
    font-family: 'Poiret One';
    font-weight: bold;
}
.nav ul li a{
text-decoration: none;
color: #e7dcd1; 
}
/*button_animation*/
.button{
    border: 4px solid #533632;
    border-radius: 5px;
    background-color: #533632;
    transition: 1s;   
    }
    .button:hover {
    background-color: #895351;
    border: 2px solid #895351;
    border-radius: 8px;
    }
    
/*Content*/
.content{
    display: block;
    position: relative;
    width: 100%;
    height: 1100px;
    background-image: url(img/cuba.png);

 
}
.form{
    position: absolute;
    height: 400px;
    width: 400px;
    top: 50%;
    left: 50%;
    margin: -200px 0 0 -200px;
}
.form{
    border: 8px solid #533632;
    border-radius: 10px;
    background-color: #5f4e4c;
    font-family: 'Poiret One';
    color: bisque;
    font-size: 1em;
}

main>.form>ul>li{
    list-style-type: none;
    margin-top: 10px;
    padding: 15px;
    
}
main>.form>ul>li>.button_form>button{
height: 50px;
}
label {
    width: 90px;
    text-align: right;
  }
  input,
textarea {
  font: 1em sans-serif;
  width: 250px;
  box-sizing: border-box;
  width: 100%;
  /* Стилизуем границы полей */
  border: 2px solid #533632;
  background-color: #E0D0B9;
}


/*footer*/
footer{
    height: 110px ;
    border-top: 3px solid #533632;
    border-bottom: 3px solid #533632;
    text-align: center;
    padding-top: 30px;
    background-color: #533632;
    color: #e7dcd1 !important;  
}
.sidebar{
    background-color: #533632;
}

footer p{
    color: #e7dcd1 !important;  
}
#img_footer{
    margin: auto 10px;
}
#text_footer{
    font-size: 20px;
    font-family: 'Fredericka the Great'; 
    color: #533632;
    
}















/*Grid*/
.row:after {
    content: " ";
    display: table;
    clear: both;
}

.col {
    float: left;
    padding-left: 15px;
    padding-right: 15px;
    
}  


.col-12 {
    width: 100%;
}
.col-11 {
    width: 91.66666667%;
}
.col-10 {
    width: 83.33333333%;
}
.col-9 {
    width: 75%;
}
.col-8 {
    width: 66.66666667%;
}
.col-7 {
    width: 58.33333333%;
}
.col-6 {
    width: 50%;
}
.col-5 {
    width: 41.66666667%;
}
.col-4 {
    width: 33.33333333%;
}
.col-3 {
    width: 25%;
}
.col-2 {
    width: 16.66666667%;
}
.col-1 {
    width: 8.33333333%;
}


@media (min-width: 768px) {
.container {
    width: 750px;
}
.col-sm-12 {
    width: 100%;
}
.col-sm-11 {
    width: 91.66666667%;
}
.col-sm-10 {
    width: 83.33333333%;
}
.col-sm-9 {
    width: 75%;
}
.col-sm-8 {
    width: 66.66666667%;
}
.col-sm-7 {
    width: 58.33333333%;
}
.col-sm-6 {
    width: 50%;
}
.col-sm-5 {
    width: 41.66666667%;
}
.col-sm-4 {
    width: 33.33333333%;
}
.col-sm-3 {
    width: 25%;
}
.col-sm-2 {
    width: 16.66666667%;
}
.col-sm-1 {
    width: 8.33333333%;
}
}
@media (min-width: 768px) {
.container {
    width: 750px;
}
.col-sm-12 {
    width: 100%;
}
.col-sm-11 {
    width: 91.66666667%;
}
.col-sm-10 {
    width: 83.33333333%;
}
.col-sm-9 {
    width: 75%;
}
.col-sm-8 {
    width: 66.66666667%;
}
.col-sm-7 {
    width: 58.33333333%;
}
.col-sm-6 {
    width: 50%;
}
.col-sm-5 {
    width: 41.66666667%;
}
.col-sm-4 {
    width: 33.33333333%;
}
.col-sm-3 {
    width: 25%;
}
.col-sm-2 {
    width: 16.66666667%;
}
.col-sm-1 {
    width: 8.33333333%;
}
}@media (min-width: 992px) {
  .container {
    width: 970px;
}
.col-md-12 {
    width: 100%;
}
.col-md-11 {
    width: 91.66666667%;
}
.col-md-10 {
    width: 83.33333333%;
}
.col-md-9 {
    width: 75%;
}
.col-md-8 {
    width: 66.66666667%;
}
.col-md-7 {
    width: 58.33333333%;
}
.col-md-6 {
    width: 50%;
}
.col-md-5 {
    width: 41.66666667%;
}
.col-md-4 {
    width: 33.33333333%;
}
.col-md-3 {
    width: 25%;
}
.col-md-2 {
    width: 16.66666667%;
}
.col-md-1 {
    width: 8.33333333%;
}
}
@media (min-width: 1200px) {
  .container {
    width: 1170px;
}
.col-lg-12 {
    width: 100%;
}
.col-lg-11 {
    width: 91.66666667%;
}
.col-lg-10 {
    width: 83.33333333%;
}
.col-lg-9 {
    width: 75%;
}
.col-lg-8 {
    width: 66.66666667%;
}
.col-lg-7 {
    width: 58.33333333%;
}
.col-lg-6 {
    width: 50%;
}
.col-lg-5 {
    width: 41.66666667%;
}
.col-lg-4 {
    width: 33.33333333%;
}
.col-lg-3 {
    width: 25%;
}
.col-lg-2 {
    width: 16.66666667%;
}
.col-lg-1 {
    width: 8.33333333%;
}
}```