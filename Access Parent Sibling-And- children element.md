🔼 1. Parent Element kaise access karein
```JavaScript
element.parentElement
```
👉 Ye property kisi element ke direct parent ko dikhata hai.

Example:
```JavaScript
let child = document.getElementById("myElement");
let parent = child.parentElement;
console.log(parent);
```
🔹 Yahaan myElement ka parent element console mein dikh jaayega.

↔️ 2. Sibling Elements kaise access karein
Sibling ka matlab hota hai — bhai-behen jaise elements jo ek hi parent ke under hote hain.

.nextElementSibling – Agla bhai-behen (next element)

.previousElementSibling – Pichhla bhai-behen (previous element)

Example:
```JavaScript
let current = document.getElementById("myElement");
let next = current.nextElementSibling;
let prev = current.previousElementSibling;
console.log(next, prev);
```
🔹 Is code se aapko myElement ke next aur previous siblings mil jaayenge.