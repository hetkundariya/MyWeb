<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compitable" content="IE-edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart</title>
    <style>
        body{
            margin:0;
            padding: 0;
            background: #0b1544;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            animation-name: HEART;
        }
        .heart{
            width: 200px;
            height: 200px;
            background: #f20044;
            position: relative;
            transform: rotate(-45deg);
            box-shadow: -20px 10px 90px #f20044;
            animation: pro 0.6s infinite liner;
        }
        .heart:before{
            content:'';
            width: 200px;
            height: 200px;
            position: absolute;
            background:#f20044;
            border-radius: 95px;
            box-sizing: -20px 10px 90px;
            top:-50%;
        }
        .heart:after {
            width: 200px;
            height: 200px;
            content:'';
            position: absolute;
            background:#f20044;
            border-radius:95px;
            right:-50%;
            box-sizing:-20px 10px 90px;
        }
        @keyframes HEART {
            0%
            {
                transform:rotate(-45deg)scale(1.07);
            }
        }
    </style>
</head>
<body>
    <div class="heart">

    </div>
</body>
</html>
