##SelectingElement
```JavaScript

 1. getElementById()
 -Agar kisi element ka ID diya gaya hai, to usko select karne ke liye use    hota hai.

 let heading = document.getElementById("myHeading");

 Yeh id="myHeading" wale element ko select karega.


2. getElementsByClassName()
Ye method ek class name se elements ko dhoondta hai. Lekin yaad rakhna, ye ek array-like list deta hai (HTMLCollection).

let items = document.getElementsByClassName("menu-item");

Agar 5 elements hain jinki class menu-item hai, to ye un sabko select karega


 3. getElementsByTagName()
Tag name se elements ko select karta hai.

let paragraphs = document.getElementsByTagName("p");

Sabhi <p> (paragraph) elements milenge.


 4. querySelector()
Yeh CSS selector jaisa kaam karta hai. Sirf pehla matching element deta hai.

let firstItem = document.querySelector(".menu-item");

Pehli menu-item class wali cheez milti hai

 5. querySelectorAll()
Ye bhi CSS selector ki tarah hota hai, lekin ye saare matching elements ko deta hai (NodeList form me).

let allItems = document.querySelectorAll(".menu-item");

Sabhi menu-item class wale elements milte hain.

Examples:-

HTML-
<h1 id="myHeading">Hello</h1>
<p class="text">Para 1</p>
<p class="text">Para 2</p>

JavaScript-
let heading = document.getElementById("myHeading"); // h1 milega
let paras = document.getElementsByClassName("text"); // dono p milenge
let firstPara = document.querySelector(".text"); // pehla p milega
let allParas = document.querySelectorAll(".text"); // dono p milenge

```

