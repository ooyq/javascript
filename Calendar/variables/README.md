```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Variables</title>
</head>

<body>
    <p id="p1"></p>
    <p id="p2"></p>
    <p id="p3"></p>
</body>

<script>
// A variable is a container for storing date
// A variable behaves as if it was the value that it contains
// Two steps:
// 1. Declaration (var,let,const)
// 2. Assignment (= assignment operator)

let firstName = "Bro";
let age = 21;
let student = true;

console.log("Hello",firstName,"!");  //strings
console.log("You are",age,"years old");  //number
console.log("Enrolled:",student);  //booleans

document.getElementById("p1").innerHTML = "Hello " + firstName + " !";
document.getElementById("p2").innerHTML = "You are " + age + " years old.";
document.getElementById("p3").innerHTML = "Enrolled: " + student;

</script>

</html>
```
