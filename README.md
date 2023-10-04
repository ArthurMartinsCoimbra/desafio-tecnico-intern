# Questionário para estágio de desenvolvedor web (PHP/JavaScript)

Para responder a este questionário, crie um fork do repositório e responda às perguntas no arquivo README.md. Em seguida, envie o link do seu fork para análise.

## Questionário

- Explique o que é um framework web e qual a sua importância.
- Quais são os principais frameworks web PHP?
- Quais são os principais frameworks web JavaScript?
- Explique o que é um banco de dados relacional e quais são os seus componentes.
- Quais são os principais tipos de dados em SQL?
- Crie uma função em PHP que receba um nome e uma idade como parâmetros e retorne uma mensagem de boas-vindas.
- Crie uma função em JavaScript que receba um número como parâmetro e retorne o seu fatorial.
- Crie uma query em SQL que retorne todos os registros de uma tabela.
- Explique o que é uma API e quais são os seus benefícios.
- Descreva um projeto de desenvolvimento web que você já realizou.

## Entrega

Ao finalizar o desafio, envie o link do seu fork para nós. Avaliaremos a estrutura, clareza, boas práticas e funcionamento correto.
Boa sorte!

### Respostas
##### Por Arthur Martins Coimbra


#### 1) Explique o que é um framework web e qual a sua importância

 Um framework web, é um tipo especifico de framework focado para aplicações web. Um framework é uma estrutura genérica de código que desempenha dadas funcionalidades que podem variar de framework para framework, geralmente se utilizando de um ou mais conjuntos de bibliotecas para alcançar seus objetivos.

#### 2) Quais são os principais frameworks web PHP?

Tenho pouquíssima experiência com PHP, mas pelo que pude ver ao pesquisar alguns minutos sobre o assunto, há vários frameworks web para PHP, mas o três principais parecem ser o Laravel, CodeIgniter e Symfony. Cada um desses três parece se destacar frente aos demais no que tange características como sintaxe simples, alta performace e flexibilidade.

#### 3) Quais são os principais frameworks web JavaScript?

Pessoalmente, do que eu sei de JavaScript, conheço apenas o Angular, porém já ouvi falar de frameworks como o Bootstrap. Ambos possuem como pontos positivos, possuirem boa legibilidade do código e terem uma comunidade ativa.

#### 4) Explique o que é um banco de dados relacional e quais são os seus componentes.

Um banco de dados relacional é uma coleção de informações (dados) que se ligam uns aos outros de forma que se complementem. Em suma, essa relação se da principalmente atravez de seus componentes, que basicamente são tabelas, linhas e colunas.

#### 5) Quais são os principais tipos de dados em SQL?

O SQL possue muitos tipos de dados, mas os que eu mais costumo usar, creio eu que sejam os principais são SMALLINT, VARCHAR e FLOAT. Basicamente, são tipos de dados que se referem a numeros (SMALLINT e FLOAT) e a conjuntos de simbolos ou letras (VARCHAR) mas também há outros tipos de dados que se referem a outras naturezas de dados como o tipo de dado BOOLEAN que se refere a booleanos.

#### 6) Crie uma função em PHP que receba um nome e uma idade como parâmetros e retorne uma mensagem de boas-vindas.


Como disse anteriormente, não possuo quase experiência em php, estudei por uma hora, e esse foi o melhor que consegui
'''
<!DOCTYPE html>
<html>
<body>

	<?php
function saudacao($nome, $idade) {
    echo "Seja bem-vindo $nome! Vejo que tem $idade anos!";
}

$nome = "Leonardo";
$idade = "28"; // Chutei a sua idade
saudacao($nome, $idade);
?>

</body>
</html>

'''
#### 7) Crie uma função em JavaScript que receba um número como parâmetro e retorne o seu fatorial.

Aqui está uma função que fornece o fatorial de um dado numero em JavaScript, fiz de forma recursiva.

'''
function fatorial(numero) {
    if (numero >= 0) {
        if (numero == 0 || numero == 1) {
            return 1;
        } else {
            return numero * fatorial(numero - 1);
        }
    } 
}

const resultado = fatorial();
console.log(resultado);

'''
#### 8) Crie uma query em SQL que retorne todos os registros de uma tabela.

Essa query vai retornar todas a colunas da tabela nomeTabela

   SELECT *
   FROM nomeTabela

#### 9) Explique o que é uma API e quais são os seus benefícios.

Uma API ou interface de programação de aplicativos, são padrões que uma aplicação pode seguir, para se comunicar com outras plataformas. Os principais beneficios se manidestão principalmente em uma maior integração e acessibilidade de serviços de outros desenvolvedores.

#### 10) Descreva um projeto de desenvolvimento web que você já realizou.

 Já participei de um projeto de conclusão de um curso de web development desenvolvido pela Sirius, que consistia em fazer um site de venda de produtos orgânicos chamado Pequi. Eu fazia parte de uma equipe de 4 membros, onde usamos Html, Css, Python, JavaScript e SQL. Eu e mais um do grupo tomamos as rédias do backend, enquanto os demais membros do grupo se concentraram no frontend. No backend usamos na época o framework Django, do Python, para conectar um banco de dados PostgreSQL ao site e criar um banco de dados relacional que consistia basicamente numa relação de produtor/produto e cliente/compras. Atualmente o site se encontra fora do ar.