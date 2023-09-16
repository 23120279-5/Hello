# Hello, world
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><link rel="shortcut icon" href="Icone Freecodecamp.png" type="image/x-icon">
    <title>Freecodecamp</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
  
</style>
<body>
           <!--Título da página e explicação sobre o formulário-->
         
        <div class="divisao">
            <h1 id="title" class="container">Praticando Esportes</h1>
            <p id="description">Gostaria de nos ajudar respondendo um breve questionário?</p><br>
        </div>
            
           <!--Preenchimento de Formulário primeira parte-->
   <form action="" id="survey-form">
        <fieldset>
            <label for="name"id="name-label" class="fontes" value="name">Nome
                <input id="name" type="text" required placeholder="Coloque seu nome" class="alinhar"></label><br><br>
            <label for="email" id="email-label" class="fontes">E-mail
                <input id="email" type="email" required placeholder="Coloque seu e-mail" class="alinhar" value="email"></label><br><br>
            <label for="number" id="number-label" class="fontes">Idade
                <input id="number" type="number" required min="16" max="65" placeholder="Coloque sua idade" class="alinhar"></label><br><br>
            <label class="fontes">Qual a sua formação acadêmica
                <select name="referrer" id="dropdown" class="alinhar">
                    <option value="#">(selecione um)</option>
                    <option value="1">Cursando ensino médio</option>
                    <option value="2">Ensino médio completo</option>
                    <option value="3">Cursando ensino superior</option>
                    <option value="4">Ensino superior completo</option>
                </select>
            </label>
        </fieldset><br>
            <!--Preenchimento de Formulário segunda parte-->
        <fieldset> 
        <label for="você pratica algum esporte?" class="fontes">Você pratica algum esporte?</label><br><br>
        <label for="sim"><input id="sim" type="radio" name="account-type" value="sim"> Sim</label><br><br>
        <label for="não"><input id="não" type="radio" name="account-type" value="não"> Não</label><br><br>
        <label for="se sim qual?" class="fontes">Se sim, qual?
            <select name="referrer" id="referrer" class="alinhar">
                <option value="">(selecione um)</option>
                <option value="1">Futball</option>
                <option value="2">Handball</option>
                <option value="3">Atletismo</option>
                <option value="4">Ciclismo</option>
                <option value="5">Esgrima</option>
                <option value="6">Natação</option>
                <option value="7">Tênis</option>
                <option value="8">Outros</option>
            </select>
        </label>
        </fieldset><br>           
            <!--Preenchimento de Formulário terceira parte-->
        <fieldset> 
        <label for="Qual tipos de esportes você gostaria de práticar?(se no caso a resposta acima tenha sido não ou no caso de desejar práticar outos esportes)." class="fontes">Qual tipos de esportes você gostaria de práticar?(se no caso a resposta acima tenha sido não ou no caso de desejar práticar outos esportes).</label><br><br>
        <label for="futball"><input id="futball" type="checkbox" value="futball">Futball</label><br>
        <label for="handball"><input id="handball" type="checkbox" value="handball">Handball</label><br>
        <label for="atletismo"><input id="atletismo" type="checkbox" value="atletismo">Atletismo</label><br>
        <label for="ciclismo"><input id="ciclismo" type="checkbox"value="ciclismo">Ciclismo</label><br>
        <label for="esgrima"><input id="esgrima" type="checkbox" value="esgrima">Esgrima</label><br>
        <label for="natação"><input id="natação" type="checkbox" value="natação">Natação</label><br>
        <label for="tênis"><input id="tênis" type="checkbox" value="tênis">Tênis</label><br>
        <label for="outros"><input id="outros" type="checkbox" value="outros">Outros</label><br><br>
            <!--Preenchimento da caixa de texto-->
            <label for="sugestão" class="fontes">Adicione outra sugestão de esporte que não esteja...<br>
                <textarea  id="sugestão" cols="66" rows="10" placeholder="Coloque aqui sua sugestão" class="container"></textarea>
            </label>
        </fieldset><br>
        <div>    
            <input id="submit" type="Submit" style="width: 510px;height: 25px;background-color: rgb(37, 228, 37); margin: 5px; font-family: Arial, Helvetica, sans-serif; font-weight: bold; font-size: medium;" value="Submit" class="button">
        </div>  
    </form>          
</body>
</html>
