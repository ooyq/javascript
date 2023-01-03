```javascript
// useful string properties & methods

let userName = "Bro Code";
let phoneNumber = "123-456-7890";

console.log(userName.length); // 该属性返回字符串的长度
console.log(userName.charAt(0)); // 返回指定字符 字符串中的索引（位置）
console.log(userName.indexOf("o"));
console.log(userName.lastIndexOf("o"));

userName = userName.trim(); // 从字符串的两侧删除空格
console.log(userName);

userName = userName.toUpperCase(); // 字符串转换为大写
console.log(userName);

userName = userName.toLowerCase(); // 字符串转换为小写
console.log(userName);

phoneNumber = phoneNumber.replaceAll("-",""); // 字符串替换全部
console.log(phoneNumber);
```






