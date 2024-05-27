# Ph-Flag-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Philippine Flag</title>
    <style>
        h1 {
            text-align: center;
        }
        .flag {
            position: relative;
            border: 5px solid black;
            height: 600px;
            width: 900px;
        }

        .blue {
            height: 300px;
            width: 900px;
            background-color: blue;
            position: relative;
        }

        .red {
            height: 300px;
            width: 900px;
            background-color: red;
            position: relative;
        }

        .white {
            height: 0;
            width: 0;
            border-left: 400px solid white;
            border-top: 300px solid transparent;
            border-bottom: 300px solid transparent;
            position: absolute;
            top: 0px;
            z-index: 2;
        }

        .sun {
            height: 100px;
            width: 100px;
            background-color: gold;
            border-radius: 50%;
            position: absolute;
            top: 250px;
            left: 80px;
            z-index: 2;
        }

        .ray1 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-bottom: 25px solid gold;
            position: absolute;
            top: 220.2px;
            left: 122px;
            z-index: 2;
        }

        .ray2 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-bottom: 25px solid gold;
            position: absolute;
            top: 239px;
            left: 169px;
            z-index: 2;
            rotate: 45deg;
        }

        .ray3 {
            height: 0;
            width: 0;
            border-left: 25px solid gold;
            border-top: 8px solid transparent;
            border-bottom: 8px solid transparent;
            position: absolute;
            top: 292px;
            left: 185px;
            z-index: 2;
        }

        .ray4 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-bottom: 25px solid gold;
            position: absolute;
            top: 335px;
            left: 169px;
            z-index: 2;
            rotate: 135deg;
        }

        .ray5 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-top: 25px solid gold;
            position: absolute;
            top: 355px;
            left: 122px;
            z-index: 2;
        }

        .ray6 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-bottom: 25px solid gold;
            position: absolute;
            top: 335px;
            left: 74px;
            z-index: 2;
            rotate: -135deg;
        }

        .ray7 {
            height: 0;
            width: 0;
            border-right: 25px solid gold;
            border-top: 8px solid transparent;
            border-bottom: 8px solid transparent;
            position: absolute;
            top: 292px;
            left: 50.2px;
            z-index: 2;
        }  
        
        .ray8 {
            height: 0;
            width: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-bottom: 25px solid gold;
            position: absolute;
            top: 239px;
            left: 74px;
            z-index: 2;
            rotate: -45deg;
        }

        .star1 {
            position: absolute;
            top: 58px;
            left: 7px;
            z-index: 2;
            rotate: -30deg;            
        }

        .star2 {
            position: absolute;
            top: 280px;
            left: 350px;
            z-index: 2;
            rotate: 90deg;
        }

        .star3 {
            position: absolute;
            top: 560px;
            left: 40px;
            z-index: 2;
            rotate: -150deg;
        }

        .star {
            position: absolute;
            border-left: 20px solid transparent;
            border-right: 20px solid transparent;
            border-bottom: 14px solid gold;
            transform: rotate(35deg);
            z-index: 3;
        }

        .star::before {
            position: absolute;
            content: '';
            top: -9px;
            left: -11px;
            border-left: 6px solid transparent;
            border-right: 6px solid transparent;
            border-bottom: 16px solid gold;
            transform: rotate(-35deg);
            z-index: 3;
        }

        .star::after {
            position: absolute;
            content: '';
            top: 1px;
            left: -20px;
            border-left: 20px solid transparent;
            border-right: 20px solid transparent;
            border-bottom: 14px solid gold;
            transform: rotate(-70deg);
            z-index: 3;
        }

    </style>
</head>
<body>
    <h1>Flag of the Philippines</h1>
    <div class="flag">
        <div class="blue"></div>
        <div class="red"></div>
        <div class="white"></div>
        <div class="sun"></div>
        <div class="sun-ray">
            <div class="ray1"></div>
            <div class="ray2"></div>
            <div class="ray3"></div>
            <div class="ray4"></div>
            <div class="ray5"></div>
            <div class="ray6"></div>
            <div class="ray7"></div>
            <div class="ray8"></div>
        </div>
        <div class="star1">
            <div class="star"></div>
        </div>
        <div class="star2">
            <div class="star"></div>
        </div>
        <div class="star3">
            <div class="star"></div>
        </div>
        <div class="ruler"></div>
    </div>
</body>
</html>
