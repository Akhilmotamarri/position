# position
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container{
            border:2px solid red;
            background-color: sandybrown;
            height: 3344px;
        }
        .box{
            border: 2px solid red;
            width: 150px;
            margin: 5px;
            padding: 2px;
            height: 150px;
            display: inline-block;
        }
        #box3{
            position: fixed;
            right: 4px;
            bottom: 5px;
        }
        #box1{
            /* position: absolute; */
            /* left: 40px; */
        }
        #box2{
            position: sticky;
            top:9px;
        }
        #box4{
            position: relative;
            top: 104px;
        }
    </style>
</head>
<body>
    <div class="container">

        <div class="box" id="box1">1</div>
        <div class="box" id="box2">2 sticky use</div>
        <div class="box" id="box3">chat with us</div>
        <div class="box" id="box4">4</div>
    </div>
    </body>
</html>
