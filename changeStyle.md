🔸 1. Direct Style Change (Inline Style)
Agar tere HTML mein koi element hai:
```javascript
<div id="box">Hello bhai!</div>
```
To JavaScript se uska style change aise karega:
```javaScript
let box = document.getElementById("box");
box.style.color = "blue";               // text ka color blue kar diya
box.style.backgroundColor = "lightgray"; // background color light gray
box.style.fontSize = "24px";            // font size badha diya
```

🔁 CSS ke naam camelCase mein likhte hain JavaScript mein: background-color ➡️ backgroundColor
font-size ➡️ fontSize


🔸 2. Ek Saath Style Lagana (cssText)
Agar tum multiple styles ek baar mein lagana chahta hai:
```javaScript
box.style.cssText = "color: white; background-color: black; padding: 10px;";
```

🔸 3. CSS Class Change Karna (Best Practice 👍)
Ismein tum ek class bana lete ho CSS mein, aur fir JS se laga/hatate ho.

✅ CSS:
```javascript
.active {
  color: white;
  background-color: green;
  font-weight: bold;
}
```
✅ HTML:
```javascript
<div id="box">Hello bhai!</div>
```
✅ JavaScript:
```javascript
box.classList.add("active");      // style lag gaya
box.classList.remove("active");   // style hata diya
box.classList.toggle("active");   // agar lagi hai to hata dega, nahi lagi to laga dega
```