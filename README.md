<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script>
        function reset() {
            document.getElementById("count").innerHTML = 0;
        }
        function decrement(){
            document.getElementById("count").innerHTML = document.getElementById("count").innerHTML - 1;
        }
        function increment(){
            document.getElementById("count").innerHTML = parseInt(document.getElementById("count").innerHTML) + 1;
        }
    </script>
    <link rel="stylesheet" href="BUTTONS.css">
</head>
<h1 style="text-align: center; font-size: 150; color: #fff;">COUNTER
</h1>
<body style="background-color: #000;">

<p style="text-align: center;">
</p>
<p style="text-align: center; font-size:200px; line-height: 1px;color: #fff;" id="count">0
</p>
<div class="yes">
<button onclick="decrement()">Decrement
</button>
<button onclick="reset()">reset
</button>
<button onclick="increment()">increment
</button>
</div>
</body>
</html>
