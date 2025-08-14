@import url('https://fonts.googleapis.com/css2?family=Cabin:ital,wght@0,400..700;1,400..700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #ffeaf4; /* Rosa bebê suave */
    color: #5f4b56; /* Marrom rosado para contraste */
    font-family: "Cabin", sans-serif;
    background-size: 150px;
    background-repeat: repeat;
}

header {
    padding: 2rem;
    background-color: #f7c6d6; /* Rosa pastel */
    text-align: center;
    color: #5f4b56;
    border-bottom: 4px solid #e3a6b2;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.05);
}

header h1, header h2 {
    font-weight: 700;
    font-size: 2rem;
}

nav a {
    color: #5f4b56;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s ease, background-color 0.3s ease;
    padding: 5px 10px;
    border-radius: 10px;
}

nav a:hover {
    background-color: #f9d4df;
    color: #a84e68;
}

main {
    padding: 2rem;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

section {
    background-color: #fff0f6;
    border-radius: 20px;
    padding: 1.5rem;
    box-shadow: 0px 4px 15px rgba(0,0,0,0.05);
}

section img {
    max-width: 200px;
    border-radius: 50%;
    display: block;
    margin: 0 auto 1rem;
    border: 4px solid #f7c6d6;
}

h2 {
    color: #a84e68;
    text-align: center;
    margin-bottom: 1rem;
}

p {
    line-height: 1.6;
    margin-bottom: 1rem;
    text-align: center;
}

a.btn-saiba-mais {
    display: inline-block;
    padding: 10px 20px;
    background-color: #f7c6d6;
    color: #5f4b56;
    border-radius: 20px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s ease;
}

a.btn-saiba-mais:hover {
    background-color: #f9d4df;
    color: #a84e68;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #f7c6d6;
    margin-top: 2rem;
    color: #5f4b56;
    border-top: 4px solid #e3a6b2;
}

/* ====================
   Estilo do Formulário
   ==================== */
form {
    max-width: 500px; /* largura máxima */
    margin: 0 auto; /* centraliza */
    display: flex;
    flex-direction: column;
    gap: 15px;
}

fieldset {
    border: 2px solid #f7c6d6;
    border-radius: 10px;
    padding: 20px;
    background-color: #fff0f6;
}

legend {
    font-weight: bold;
    color: #a84e68;
    padding: 0 10px;
}

input, textarea, button {
    width: 100%;
    padding: 10px;
    border-radius: 8px;
    border: 1px solid #ccc;
    font-family: inherit;
    font-size: 1rem;
}

textarea {
    resize: vertical;
}

button {
    background-color: #f7c6d6;
    color: #5f4b56;
    font-weight: bold;
    border: none;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background-color: #f9d4df;
    color: #a84e68;
}
