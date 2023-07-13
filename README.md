- 👋 Hi, I’m @deniskranga
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
deniskranga/deniskranga is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Програма для перевірки, чи є рядок паліндромом на мові JavaScript:
javascript
Copy code
function isPalindrome(str) {
    var reversedStr = str.split('').reverse().join('');
    return str === reversedStr;
}

var input = "radar";
var result = isPalindrome(input);

console.log("Is '" + input + "' a palindrome? " + result);
