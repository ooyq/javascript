```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>counter_program</title>
    <style>
        .container{
            position:absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%,-50%);
        }
        #countLabel{
            display: block;
            text-align: center;
            font-size: 50px;
        }
    </style>
</head>

<body>
    <div class="container">
        <label id="countLabel">0</label><br>
        <button id="decreaseBtn">decrease</button>
        <button id="resetBtn">reset</button>
        <button id="increaseBtn">increase</button>
    </div>
</body>

<script>
let count = 0;
document.getElementById("decreaseBtn").onclick = function(){
    count -= 1;
    document.getElementById("countLabel").innerHTML = count;
}

document.getElementById("resetBtn").onclick = function(){
    count = 0;
    document.getElementById("countLabel").innerHTML = count;
}

document.getElementById("increaseBtn").onclick = function(){
    count += 1;
    document.getElementById("countLabel").innerHTML = count;
}
</script>

</html>
```