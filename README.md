<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    
    <!--jQuery-->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>

     <!-- Latest compiled and minified JavaScript -->
     <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    <title>О нас</title>
</head>
<body>
    <style>
        body{
            background-color:orange;
        }
    </style>
    <div  class="panel-group" id="collapse-group">
        <div class="panel-panel-warning">
            <div class="panel-heading"> 
                <a data-toggle="collapse" data-parent="collapse-group" href="#el1">Создание компании #Aservice#</a>
            </div>
            <div id="el1" class="collapse in">
                <div class="panel-body">КТУ Aservice это молодая которая создалась недавно,в этой компании в любое время могут починить ваши
                    <br/> ручные гаджеты, пк, ноутбук и т.п. Наша компания работает даже в воскресенье в удаленном стиле
                </div>
            </div>
        </div>
    </div>
    <h2>Наши соц.сети:</h2>
    <ul>
        <li class="bg-success text-info">WhatsApp</li>
        <li class="bg-info text-warning">telegram</li>
        <li class="bg-warning text-success">Viber</li>
    </ul>
    <div class="container">
        <form role="form">
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" class="form-control" id="email"placeholder="Введите email">
            </div>
        </form >
    </div>
    <div class="container">
        <form role="form">
            <div class="form-group">
                <label for="name">Ваше имя</label>
                <input type="name" class="form-control" id="name"placeholder="Введите ваше имя">
            </div>
        </form >
    </div>
    <button class="btn btn-success"><a a data-toggle="email" data-parent="name" href="index4.html"><span class="user">Вход в данные создателя</span></a></button>
    <div class="container">
        <form role="form">
            <div class="form-group">
                <label for="name">Календарь</label>
                <input type="date" class="form-control" id="date"placeholder="Введите ваше имя">
            </div>
        </form>
    </div>
    <a class="btn btn-success" type="button" href="indexl.html"><span class="glyphicon glyphicon-list" >Главное меню</span></a>
    <a class="btn btn-success" type="button" href="index2.html"><span class="glyphicon glyphicon-wrench">Нашиуслуги</span></a>
    <a class="btn btn-success" type="button" href="index3.html"><span class="glyphicon glyphicon-phone">Контакты</span></a>
    
     
     
     
</body>
</html>
