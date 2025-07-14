<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Pessoal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff; /* Cor de fundo suave */
            margin: 20px;
            padding: 20px;
        }
        
        h1 {
            color: #2e8b57; /* Cor diferente para o título */
            text-align: center; /* Centralizado */
        }
        
        p {
            font-size: 18px; /* Tamanho de fonte maior */
            text-align: justify; /* Texto justificado */
            line-height: 1.6;
        }
        
        ul {
            line-height: 2; /* Espaçamento maior entre itens */
        }
        
        img {
            border-radius: 15px; /* Bordas arredondadas */
            width: 300px; /* Tamanho adequado */
            display: block;
            margin: 20px auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        table {
            width: 80%;
            margin: 30px auto;
            border-collapse: collapse;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        th, td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        
        th {
            background-color: #2e8b57;
            color: white;
        }
        
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        
        tr:hover {
            background-color: #e6f7e6;
        }
        
        a {
            color: #2e8b57;
            text-decoration: none;
            font-weight: bold;
        }
        
        a:hover {
            color: #1e5c3a; /* Mudança de cor ao passar o mouse */
        }
        
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #2e8b57;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        
        button:hover {
            background-color: #1e5c3a;
        }
        
        #mensagem {
            text-align: center;
            font-style: italic;
            margin: 20px;
            padding: 15px;
            background-color: #e6f7e6;
            border-radius: 5px;
            display: none;
        }
    </style>
</head>
<body>
    <h1>João da Silva</h1>
    
    <p>
        Olá! Meu nome é João da Silva, tenho 25 anos e moro na cidade de São Paulo. 
        Sou formado em Análise e Desenvolvimento de Sistemas e atualmente trabalho 
        como desenvolvedor front-end. Tenho grande interesse por tecnologia, 
        viagens e fotografia. Adoro aprender coisas novas e compartilhar 
        conhecimentos com outras pessoas.
    </p>
    
    <button onclick="mostrarMensagem()">Clique para ver uma mensagem!</button>
    <div id="mensagem"></div>
    
    <h2>Meus Hobbies Favoritos</h2>
    <ul>
        <li>Fotografia de paisagens</li>
        <li>Programação de jogos simples</li>
        <li>Ciclismo aos finais de semana</li>
    </ul>
    
    <img src="https://images.unsplash.com/photo-1507035895480-2b3156c31fc8?ixlib=rb-1.2.1&auto=format&fit=crop&w=300&q=80" alt="Fotografia de paisagem">
    
    <h2>Países que gostaria de visitar</h2>
    <table>
        <tr>
            <th>País</th>
            <th>Imagem</th>
        </tr>
        <tr>
            <td>Japão</td>
            <td><img src="https://images.unsplash.com/photo-1492571350019-22de08371fd3?ixlib=rb-1.2.1&auto=format&fit=crop&w=100&q=80" alt="Japão" style="width: 100px;"></td>
        </tr>
        <tr>
            <td>Itália</td>
            <td><img src="https://images.unsplash.com/photo-1533676802871-eca1ae998cd5?ixlib=rb-1.2.1&auto=format&fit=crop&w=100&q=80" alt="Itália" style="width: 100px;"></td>
        </tr>
        <tr>
            <td>Canadá</td>
            <td><img src="https://images.unsplash.com/photo-1501594907352-04cda38ebc29?ixlib=rb-1.2.1&auto=format&fit=crop&w=100&q=80" alt="Canadá" style="width: 100px;"></td>
        </tr>
    </table>
    
    <p>Visite meu site de tecnologia favorito: <a href="https://www.tecmundo.com.br" target="_blank">TecMundo</a></p>
    
    <script>
        function mostrarMensagem() {
            const mensagem = document.getElementById('mensagem');
            mensagem.innerHTML = "A jornada de mil milhas começa com um único passo. Continue progredindo!";
            mensagem.style.display = 'block';
        }
    </script>
</body>
</html>
