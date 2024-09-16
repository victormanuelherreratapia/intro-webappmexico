# intro-webappmexico
Voy a darte un ejemplo de cómo generar una interfaz web básica utilizando tres archivos por separado: HTML, CSS y JavaScript (JS).

1. Archivo HTML (index.html)
Este archivo define la estructura de la página web.

html

Copiar código

`

Bienvenido a la Interfaz Web
Hacer Click
<script src="script.js"></script> <!-- Enlace al archivo JS -->
`
2. Archivo CSS (styles.css)
Este archivo define el estilo de la página web.

css

Copiar código

`body {
font-family: Arial, sans-serif;
background-color: #f4f4f4;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
margin: 0;
}

#container {
text-align: center;
background-color: white;
padding: 20px;
border-radius: 10px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

button {
padding: 10px 20px;
background-color: #007BFF;
color: white;
border: none;
border-radius: 5px;
cursor: pointer;
}

button:hover {
background-color: #0056b3;
}`

3. Archivo JavaScript (script.js)
Este archivo define el comportamiento de la página web.

javascript

Copiar código

document.getElementById("actionBtn").addEventListener("click", function() { document.getElementById("message").textContent = "¡Has hecho click en el botón!"; });
