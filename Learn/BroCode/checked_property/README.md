```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>checked property</title>
</head>
<body>
    <label for="myCheckBox">subscribe</label>
    <input type="checkbox" id="myCheckBox"><br>

    <label for="visaBtn">Visa</label>
    <input type="radio" name="card" id="visaBtn">
    <label for="mastercardBtn">MasterCard</label>
    <input type="radio" name="card" id="mastercardBtn">
    <label for="paypalBtn">PayPal</label>
    <input type="radio" name="card" id="paypalBtn"><br>

    <button id="myButton">submit</button>
</body>
<script>
document.getElementById("myButton").onclick = function(){
    const myCheckBox = document.getElementById("myCheckBox");
    const visaBtn = document.getElementById("visaBtn");
    const mastercardBtn = document.getElementById("mastercardBtn");
    const paypalBtn = document.getElementById("paypalBtn");

    if(myCheckBox.checked){
        console.log("You are subscribed!")
    }else{
        console.log("You are NOT subscribed!")
    }

    if(visaBtn.checked){
        console.log("You are paying with Visa!")
    }else if(mastercardBtn.checked){
        console.log("You are paying with MasterCard!")
    }else if(paypalBtn.checked){
        console.log("You are paying with PayPal!")
    }else{
        console.log("You mast select a payment type!")
    }
}
</script>
</html>

```