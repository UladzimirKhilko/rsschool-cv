![Vladimir Khilko](./images/avatar.jpeg)
# **Vladimir Khilko**
***


## ** _My contacts_ **
----
* **Email:**   vladimirhilko@gmail.com
* **Phone:**   +375 44 7933766
* **Discord:** VladimirKhilko(@UladzimirKhilko)
***
***

## ** _About me_ **
***
At 53, I decided to try my hand at frontend development. I have been taking various online courses on Udemy for over a year. Since November 2021, I have been working on a small project as a developer. I really enjoy the application development process. I love getting new knowledge. I take the learning process very seriously. Taking these courses is a challenge to yourself...
***
***
## ** _Skills_**
***
* HTML
* CSS (SASS/SCSS, Bootstrap)
* JS (Fundamentals, OOP, ES6+, DOM, JSON)
* React JS, Redux (have development experience)
* Git/GitHub
* Figma, Photoshop (for web development)
* VSCode, Sublime
***
***
## ** _Code examples_ **
***
``` javascript
function filterArray(array, callback) {
  const newArray = [];
  
  for (let i = 0; i < array.length; i += 1) {
    if (callback(array[i])) newArray.push(array[i]);
  }
  return newArray;
}
const numbers = [1, 2, 3, 4, 5];

function isOdd(num) {
    return num % 2 !== 0; 
}
function isEven(num) {
   return num % 2 === 0;
}

filterArray(numbers, isOdd);
filterArray(numbers, isEven);

//Проверка
console.log(filterArray(numbers, isEven)); // [2, 4]
console.log(filterArray(numbers, isOdd)); //[1, 3, 5]
```
***
***