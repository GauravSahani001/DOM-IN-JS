`javaScript`

createElement ka use tab kiya jata hai jab hum kisi HTML element ko dynamically (program se) create karna chahte hain.

Syntax:
```
document.createElement('tagName');
```
Yahaan 'tagName' ki jagah aap jo HTML element banana chahte ho, uska naam dete ho — jaise `'div'`, `'p'`, `'button'`, etc.

Example 1: Ek simple div banana aur usme text daalna
```
// 1. Naya div element create karo
let newDiv = document.createElement('div');

// 2. Usme text daalo
newDiv.textContent = "Yeh ek naya div hai!";

// 3. Us div ko body me add karo
document.body.appendChild(newDiv);
```

Example 2: Button create karna aur usme event lagana
```
let btn = document.createElement('button'); // Button banao
btn.textContent = "Click Me";               // Text daalo
btn.onclick = function() {                  // Click hone par kya ho
    alert("Button clicked!");
};
document.body.appendChild(btn);            // Body me daal do
```
Aap `createElement` ke baad us element ke attributes bhi set kar sakte ho, jaise `id`, `class`, `style`, etc.

```
let p = document.createElement('p');
p.textContent = "Hello, Gaurav!";
p.id = "myPara";
p.style.color = "blue";
document.body.appendChild(p);
```