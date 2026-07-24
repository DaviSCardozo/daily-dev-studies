# 📚 Daily Dev Studies

Bem-vindo ao meu repositório de estudos!

## Objetivo

Registrar minha evolução diária em programação, desenvolvimento web e outras tecnologias.

## Trilhas de estudo

## CSS

### Exercicio html-css-basico-01.html
### Exercicio html-css-basico-02.html
### Exercicio html-css-basico-03.html
### Exercicio html-css-basico-04.html
### Exercicio html-css-basico-05.html
### Exercicio Efeito Cascata
### Exercicio Herança
### Exercicio Modelo de Caixa (Box Model)

Neste estudo feito arquivo html com um lista não ordenada linkada com exercicicios de CSS com exemplos diverços:

### html-css-basico-01.html:
foi executado atividade de integração de style como no body cor de fundo,h1 trocado a cor e no h2 cor do bloco de fundo e cor da letras.
Exercicio 
<style>
body{
    background-color: darkblue;
}

 h1{
    color: chartreuse;
}

h2{
    background-color: aliceblue;
    color: red;
}
</style>

### html-css-basico-02.html:
foi executado atividade de integração de de style com seletor ID (jogo da velha (#) chama um ID, que é exclusivo para um único elemento. No CSS, o ID tem maior peso (prioridade) numa item de lista).

<style>
    #primeiroIrmão{
        font-size: 20px;
        font-weight: bold;
        color: red;
    }
    #segundoIrmão{
        color:green;
    }
    #terceiroIrmão{
        color: palevioletred;
    }
    #quartoIrmão{
        color: grey;
    }
    #quintoIrmão{
        color:brown;
    }
    #sextoIrmão{
        color: orangered;
    }
    #setimoirmão{
        color: rgb(0, 140, 255);
    }
    #eu{
        color: blueviolet; 
    }
    #nonoIrmão{
        color:crimson;
    }
</style>

<body>
    <h1>Lista de Irmaõs</h1>
    <ul>
        <li id="primeiroIrmão">Cleversonli>
        <li id="segundoIrmão">Gilson</li>
        <li id="terceiroIrmão">Roselaineli>
        <li id="quartoIrmão">Fernando</li>
        <li id="quintoIrmão">Tiago</li>
        <li id="sextoIrmão">Orlando</li>
        <li id="setimoIrmão">Daniel</li>
        <li id="eu">Davi</li>
        <li id="nonoIrmão">Alexasandro</li>
    </ul>
</body>

### html-css-basico-03.html:
foi executado atividade de integração de de style com seletor classe numa item de lista.Ponto (. - Class): Usado quando você precisa aplicar a mesma formatação a múltiplos elementos na sua página. Por exemplo, background-color: crimson; trocando o fundo do bloco da div.

<style>

    body{
        background-color: black;
        color: white;
    }
    .par{
        background-color: crimson;
        font-weight: bold;
        color: gold;                
    }
    .destaque{
        font-size: 25px;
    }
<ul>
    <li class="destaque">Cleverson</li>
    <li class="par destaque">Gilson</li>
</ul>
</style>

observação exemplos acima foi feito CSS internamente.
temos 3 tipos e trabalha r com css em html eles ~sao:

interno = utilizamos dentro do html dentro do blobo head do Html.

Externo = css é criado num arqui .css separado e vinculo no html que vai ser utilizado entre exemplo e vinculação (link rel="stylesheet" href="estilos.css")

InLine = O CSS Inline é aplicado diretamente na tag HTML usando o atributo style. Ele afeta apenas aquele elemento específico em que foi declarado, exemplo (<p style="color: blue; font-size: 16px;">Este é um texto azul e maior.</p>)

### html-css-basico-04.html:
foi executado atividade de integração de css externo (link rel="stylesheet" href="").

<link rel="stylesheet"href="html-css-basico-04 .css">

html-css-basico-05.html = foi Concatenado os 3 tipos de trabalhar com css no html interno,Externo e InLine.

### Exercicio Efeito Cascata:
foi apresentado tipos especificação de seletor e sua prioridades (0.0.0)
A ordem de importância dos seletores (do maior para o menor) é:
id #area2 (1.0.0)
class .estaque (0.1.0)
tag div (0.0.1)

Quanto maior a especificidade (pontuação mais à esquerda), maior a prioridade da regra para definir a estilização dos elementos.

### Exercicio Herança:
aplicado herança da borda do block body pra block div que recebeu a herança com comando inherit.
<style>
    body {
        border: solid 6px red;
        font-family: 'Courier New', Courier, monospace;
        background-color: black;
        color: white;
    
    div{
        border: inherit;
    
    #texto {
        color: white;
        font-size: 20px;
    }
</style>

### Exercicio Modelo de Caixa (Box Model):
feixo atiuvidade de dar espaçamento nas margin,padding e border  utilizano seletores id e por tags.

### Modelo de Caixa (Box Model):
neste estudo foi trabalhado exemplos de caixa de modelagem com style de div e ID para cada div com seu ID definido para dar style para cada um diferente
### Margin Collapse: 
foi aplicada varios tipos de stylos no body nas classes ,DIV e span para desmostra seu comprtamente em cada uma delas.
### Propriedade Display #01:
demostrando no funç~
ao e sua reação em cada uma das tags DIV e Span
### Propriedade Display #02:
na aula passado foi levando o problema de espaço em branco entre as spans e foi aplicado display: flex para retirar e espaço.

### Seletores:
tipos de seletores element(TAG), .CLASS (.), ID(#), seletor univeral (*) e seletor por atributo ([]). OBS:seletor ID é mais perfomatico que o seletor de atributo[].


## Tecnologias

- HTML
- CSS3
- Git
- GitHub

---

⭐ Repositório em constante atualização.