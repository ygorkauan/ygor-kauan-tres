<main>
    <form>
        <label for="nomesobrenome">Nome e sobrenome</label>
        <input type="text" id="nomesobrenome">

        <label for="email">Email</label>
        <input type="text" id="email">

        <label for="telefone">Telefone</label>
        <input type="text" id="telefone">

        <input type="submit" value="Enviar formulário">
    </form>
</main>
main {
    width: 940px;
    margin: 0 auto;
}

form {
    margin: 40px 0;
}

form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}

form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
<label for="mensagem">Mensagem</label>
<textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>
<div>
    <p>Como prefere o nosso contato?</p>
    <label for="radio-email">
        <input type="radio" name="contato" value="email" id="radio-email">
        Email
    </label>
    
    <label for="radio-telefone">
        <input type="radio" name="contato" value="telefone" id="radio-telefone"> 
        Telefone
    </label>
    
    <label for="radio-whatsapp">
        <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp">
        WhatsApp
    </label>
</div>
<div>
    <p>Qual horário prefere ser atendido?</p>
    <select>
        <option>Manhã</option>
        <option>Tarde</option>
        <option>Noite</option>
    </select>
</div>
<label class="checkbox">
    <input type="checkbox">
    Gostaria de receber nossas novidades por email?
</label>
form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
form label, form p {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.input-padrao {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.checkbox {
    margin: 20px 0;
}
<img src="logo.png" alt="Logo da Barbearia Alura">
<img src="logo-branco.png" alt="Logo da Barbearia Alura">
<label for="email">Email</label>
<input type="email" id="email" class="input-padrao" required placeholder="seuemail@dominio.com">

<label for="telefone">Telefone</label>
<input type="tel" id="telefone" class="input-padrao" required placeholder="(XX) XXXXX-XXXX">
<label for="radio-whatsapp">
    <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>
    WhatsApp
</label>
<label class="checkbox">
    <input type="checkbox" checked>
    Gostaria de receber nossas novidades por email?
</label>
form label, form legend {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
.enviar {
    width:40%;
    padding: 15px 0;
    background: orange;
    color: white;
    font-weight: bold;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    transition: 1s all;
    cursor: pointer;
}
.enviar:hover {
    background: darkorange;
    transform: scale(1.2);
}
<tr>
    <td colspan="5">Rio de Janeiro</td> 
</tr>
<table>
    <thead>
        <tr>
            <th>Dia</th>
            <th>Horário</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Segunda</td>
            <td>8h ~ 20h</td>
        </tr>
        <tr>
            <td>Quarta</td>
            <td>8h ~ 20h</td>
        </tr>
        <tr>
            <td>Sexta</td>
            <td>8h ~ 20h</td>
        </tr>
    </tbody>
</table>
table {
    margin: 20px 0 40px;
}

thead {
    background: #555555;
    color: white;
    font-weight: bold;
}

td, th {
    border: 1px solid #000000;
    padding: 8px 15px;
}
table {
    margin: 20px 0 40px;
}

thead {
    background: #555555;
    color: white;
    font-weight: bold;
}

td, th {
    border: 1px solid #000000;
    padding: 8px 15px;
}
