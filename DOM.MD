##DOM
```DOM IN JS

📚 What is the Document Object Model (DOM)?

DOM ek tree-like structure hoti hai jo HTML page ko JavaScript ke through access aur modify karne deti hai.

Socho DOM ek bridge hai HTML aur JavaScript ke beech — isse JavaScript ko page ke elements ko "dekhna", "badalna", aur "control karna" aata hai.

🏗️ Structure Example:

<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello DOM!</h1>
  </body>
</html>

Yeh ban jaata hai DOM Tree mein aise:

Document
 └── html
     ├── head
     │   └── title
     └── body
         └── h1

🔧 Basic Example:

<h1 id="heading">Hello</h1>

<script>
  const h = document.getElementById("heading");
  h.innerText = "Hello Gaurav!"; // Change text
  h.style.color = "blue";        // Change color
</script>

🔥 DOM se Tum Kar Sakte Ho:
✅ Text change
✅ Image change
✅ Button click ka response
✅ Real-time content update
✅ Form validation
✅ Animation + Effects



```

