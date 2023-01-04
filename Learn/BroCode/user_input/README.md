```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Input</title>
</head>

<body>
    <label id="myLabel">Enter your name:</label><br>
    <input type="text" id="myText"><br>
    <button type="button" id="myButton">submit</button>
</body>

<script>
// How to accpet user input
// Easy way with a window prompt
// Difficult way html textbox

/*
 let username = window.prompt("What's your name?");
 console.log(username);
*/

let username;
document.getElementById("myButton").onclick = function () {
    username = document.getElementById("myText").value;
    console.log(username);
    document.getElementById("myLabel").innerHTML = "Hello " + username;
}
</script>
<script src="index.js"></script>
</html>
```
