<!DOCTYPE html>
<html lang="en">
    <style>
        #box{
            width: 500px;
            height: 500px;
            margin: auto;
            background-color: yellow;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap
            
        }
        #box>div{
            width: 250px;
            height: 200px;
            background-color: orangered;
            border: 1px;
            display: flex;
            justify-content: center;
            align-items: center;

        }
    </style>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div id = "box">
    <div> child 1</div>
    <div> child 2</div>
    <div> child 3</div>
    <div> child 4</div>
    </div>
    
</body>
</html>
