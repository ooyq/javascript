```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hypotenuse_calc</title>
</head>

<body>
    <label id="aLabel">Side A:</label>
    <input type="text" id="aTextBox"><br>
    <label id="bLabel">Side B:</label>
    <input type="text" id="bTextBox"><br>
    <button type="button" id="submitButton">submit</button><br>
    <label id="cLabel"></label>
</body>

<script>

let a;
let b;
let c;

/*
a = window.prompt("Enter side A");
a Number(a);

b = window.prompt("Enter side B");
b Number(b);

c = Math.sqrt(Math.pow(a,2) + Math.pow(b,2));

console.log("Side c:",c);
*/

document.getElementById("submitButton").onclick = function(){
    a = document.getElementById("aTextBox").value;
    a = Number(a);

    b = document.getElementById("bTextBox").value;
    b = Number(b);

    c = Math.sqrt(Math.pow(a,2) + Math.pow(b,2));
    document.getElementById("cLabel").innerHTML = "Side C: " + c;
}
</script>

</html>
```