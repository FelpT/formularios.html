# formularios.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback do cliente</title>
</head>
<body>
<header>
    <h1>Feedback do Clite</h1>
</header>
<h2> Antes de responder as perguntas favor responder os formulários com suas informações pessoais</h2>
<form method="post">
<p>
    <label for="Seu nome">Nome completo</label>
    <input type="text" placeholder="Nome completo" id="Seu nome"/>
</p>

<p>
    <label for="email">email</label>
    <input type="text" placeholder="Seu email" id="email"/>
</p>
<p>
    <label for="Telefone">Telefone</label>
    <input type="text" placeholder="(xx)xxxxx-xxxx" id="Telefone"/>
</p>
<p>
    <h2>Agora nos dê o seu feedback</h2>
</p>
<p>
    Você está satisfeito com o produto?
    <input type="radio" id="não" name="1"/>
    <label for="não">Não</label>
    <input type="radio" id="sim" name="1"/>
    <label for="sim">sim</label>
</p>
<p>
    Você esta satisfeito com os serviços de entrega?
    <input type="radio" id="não" name="2"/>
    <label for="não">Não</label>
    <input type="radio" id="sim" name="2"/>
    <label for="sim">sim</label>
</p>
<p>
    Por onde conheceu a nossa loja?
    <select>
        <option>Instagram</option>
        <option>Familiares/amigos</option>
        <option>Facebook</option>
        <option>WhatsApp</option>
        <option>Anuncio local</option>
    </select>
</p>
</form>
</body>
<footer>
<form>
    <input type="checkbox" id="Autorização"/>
    <label for="Autorização">Autorizo o compartilhamento de dados com terceiros</label>
<p>    
    <input type="submit" value="Enviar"/>
</p>    
</form>    
</footer>
</html>

