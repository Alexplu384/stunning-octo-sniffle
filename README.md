/* Estilos para Juguetelandia Mágica */

body {
  font-family: 'Comic Sans MS', cursive, sans-serif;
  background-color: #fff9f0;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background-color: #f06292;
  color: white;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 10px 0 0;
  display: flex;
  justify-content: center;
  gap: 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 20px;
}

h2 {
  color: #f06292;
  border-bottom: 2px solid #f06292;
  padding-bottom: 5px;
}

.producto {
  border: 2px dashed #ffcc80;
  border-radius: 10px;
  padding: 10px;
  margin: 10px 0;
  display: inline-block;
  text-align: center;
  width: 200px;
  background-color: #fff3e0;
}

.producto img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.producto button {
  background-color: #ffb74d;
  border: none;
  padding: 10px;
  color: white;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 400px;
}

input, textarea {
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

button[type="submit"] {
  background-color: #f06292;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  background-color: #f06292;
  color: white;
  text-align: center;
  padding: 10px;
  position: relative;
  bottom: 0;
  width: 100%;
}

iframe {
  border-radius: 10px;
  width: 100%;
  max-width: 500px;
  height: 250px;
}
