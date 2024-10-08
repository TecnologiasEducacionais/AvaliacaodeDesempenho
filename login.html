<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Avaliação de Desempenho</title>
    <link rel="icon" href="https://i.imgur.com/z7B218w.png" type="image/png">
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@400&display=swap');
        body {
            font-family: 'Ubuntu', sans-serif;
            background-color: #f5f5f5;
            color: #202124;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        body.dark-mode {
            background-color: #1e1e1e;
            color: #ffffff;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            max-width: 400px;
            margin-top: 150px;
            padding: 20px;
            box-sizing: border-box;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        body.dark-mode .container {
            background-color: #333333;
            color: #ffffff;
        }
        header {
            background-color: #004070;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            width: 100%;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 10;
            box-sizing: border-box;
        }
        header img {
            max-height: 40px;
        }
        .toggle-dark-mode {
            font-size: 24px;
            cursor: pointer;
            margin-right: 20px;
        }
        h1 {
            text-align: center;
            color: #004070;
            margin-bottom: 20px;
        }
        body.dark-mode h1 {
            color: #f5c200;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-sizing: border-box;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #004070;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #00305a;
        }
        body.dark-mode button {
            background-color: #ea5a33;
        }
        body.dark-mode button:hover {
            background-color: #d94d2b;
        }
    </style>
</head>
<body>
    <div class="container">
        <header id="header">
            <img src="https://i.imgur.com/22pxWZ6.png" alt="Logotipo">
            <span class="toggle-dark-mode" id="darkModeToggle">🌙</span>
        </header>

        <h1>Login</h1>
        <input type="email" id="email" placeholder="Digite seu e-mail" required>
        <input type="password" id="password" placeholder="Digite sua senha" required>
        <button onclick="login()">Entrar</button>
    </div>

    <!-- Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/10.14.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/10.14.0/firebase-auth.js"></script>

    <script>
        // Configuração do Firebase
        const firebaseConfig = {
            apiKey: "AIzaSyDYVLQlZ0koUMD8A44if7epI_KwuXlqgMw",
            authDomain: "avaliacaoodedesempenho.firebaseapp.com",
            projectId: "avaliacaoodedesempenho",
            storageBucket: "avaliacaoodedesempenho.appspot.com",
            messagingSenderId: "771572537347",
            appId: "1:771572537347:web:a48e377811de1caa2b5636",
            measurementId: "G-WQTCS7G2LN"
        };

        // Inicializa o Firebase
        firebase.initializeApp(firebaseConfig);
        const auth = firebase.auth();

        // Função de login
        function login() {
            const email = document.getElementById("email").value;
            const password = document.getElementById("password").value;

            if (email === "" || password === "") {
                Swal.fire({
                    icon: 'warning',
                    title: 'Campos vazios',
                    text: 'Por favor, preencha todos os campos.',
                });
                return;
            }

            auth.signInWithEmailAndPassword(email, password)
                .then((userCredential) => {
                    const user = userCredential.user;
                    Swal.fire({
                        icon: 'success',
                        title: 'Login bem-sucedido!',
                        showConfirmButton: false,
                        timer: 1500
                    }).then(() => {
                        // Aqui redirecionamos para a página do Google Apps Script
                        window.location.href = "https://script.google.com/macros/s/AKfycbzCJXaqjUM8bQBV-PtfnuIrnxHfabPdY52YHH4aC2yLRt_kdZ4Fjvq6D7GqgUbpLFWn/exec?userEmail=" + encodeURIComponent(user.email);
                    });
                })
                .catch((error) => {
                    Swal.fire({
                        icon: 'error',
                        title: 'Erro no login',
                        text: error.message,
                    });
                });
        }
    </script>

    <!-- Modo noturno -->
    <script>
        const toggleDarkMode = document.getElementById('darkModeToggle');
        const body = document.body;

        function toggleMode() {
            const isDarkMode = body.classList.toggle('dark-mode');
            toggleDarkMode.textContent = isDarkMode ? '☀️' : '🌙';
            localStorage.setItem('darkMode', isDarkMode ? 'enabled' : 'disabled');  // Salvar no localStorage
        }

        function loadDarkModePreference() {
            const darkModePreference = localStorage.getItem('darkMode');
            if (darkModePreference === 'enabled') {
                body.classList.add('dark-mode');
                toggleDarkMode.textContent = '☀️';  // Mostrar o ícone de sol
            }
        }

        window.onload = function() {
            loadDarkModePreference();
            toggleDarkMode.addEventListener('click', toggleMode);  // Ativar a alternância de modo escuro
        };
    </script>
</body>
</html>
