<h1>Projetos feitos no #7DaysOfCode</h1>

<h2>Desafios</h2>


⨀ [Desafio JS 1/7](#lógica-js-17-operações-booleanas)

⨀ [Desafio JS 2/7](#7daysofcode---lógica-js-27--variáveis)

⨀ [Desafio JS 3/7](#7daysofcode---lógica-js-37-fluxo-de-decisão)

⨀ [Desafio JS 4/7](#7daysofcode---lógica-js-47--mais-loops-e-randomização)

⨀ [Desafio JS 5/7](#7daysofcode---lógica-js-57-arrays-e-coleções)



## Lógica JS 1/7: Operações Booleanas

<p>Sendo assim, a sua tarefa de hoje é reescrever o código abaixo de maneira que ele imprima as informações de maneira correta, que faça sentido e sem erros:</p>
  
let numeroUm = 1
  
let stringUm = '1'
  
let numeroTrinta = 30
  
let stringTrinta = '30'
  
let numeroDez = 10
  
let stringDez = '10'

<code>if (COMPARAR O numeroUm e a stringUm) {
  console.log('As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroUm e stringUm não tem o mesmo valor')
}</code>

<code>if (COMPARAR O numeroTrinta e a stringTrinta) {
  console.log('As variáveis numeroTrinta e stringTrinta tem o mesmo valor e mesmo tipo')
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo')
}</code>

<code>if (COMPARAR O numeroDez e a stringDez) {
  console.log('As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroDez e stringDez não tem o mesmo valor')
}</code>

[Solucão](https://github.com/wesleyLM/-7DaysOfCode-/blob/main/LogicaJS1-7OperacoesBooleanas.js)

## 7DaysOfCode - Lógica JS 2/7: 👩🏽‍💻 Variáveis

Desenvolver um programa simulando um desses sites. Ele deve pedir para o usuário responder 3 perguntas:

- Qual o seu nome?
- Quantos anos você tem?
- Qual linguagem de programação você está estudando?

À medida que as perguntas forem sendo feitas, a pessoa que estiver usando o programa deve responder cada uma delas.

No final, o sistema vai exibir a mensagem:

"Olá [nome], você tem [idade] anos e já está aprendendo [linguagem]!"

Note que cada informação entre [ ] é uma das respostas dadas pela pessoa.
EXERCÍCIO OPCIONAL
Se você quiser se aprofundar no assunto de hoje, eu tenho mais um exercício para você.

Mas ele é 100% opcional.

Você vai complementar o código para que, depois de exibir a mensagem anterior, o programa pergunte:

Você gosta de estudar [linguagem]? Responda com o número 1 para SIM ou 2 para NÃO.

E aí, dependendo da resposta, ele deve mostrar uma das seguintes mensagens:

1 > Muito bom! Continue estudando e você terá muito sucesso.
2 > Ahh que pena... Já tentou aprender outras linguagens?

[Solucão](https://github.com/wesleyLM/7DaysOfCode/blob/main/L%C3%B3gica%20JS%202-7%F0%9F%91%A9%F0%9F%8F%BD%E2%80%8D%F0%9F%92%BB%20Vari%C3%A1veis.html)

## 7DaysOfCode - Lógica JS 3/7: Fluxo de decisão

Seu desafio de hoje é criar os destinos possíveis de um jogo, em que o usuário consiga escolher:

1. Se quer seguir para área de Front-End ou seguir para a área de Back-End.

2. Caso esteja na área de Front-End, se quer aprender React ou aprender Vue. Caso esteja na área de Back-End, poderá aprender C# ou aprender Java.

3. Depois, independente das escolhas anteriores, o usuário poderá escolher entre seguir se especializando na área escolhida ou seguir se desenvolvendo para se tornar Fullstack. Você deve exibir na tela uma mensagem específica para cada escolha.

4. Por fim, pergunte quais são as tecnologias nas quais a pessoa gostaria de se especializar ou de conhecer. Aqui, a pessoa pode responder N tecnologias, uma de cada vez. Então, enquanto ela continuar respondendo ok para a pergunta: “Tem mais alguma tecnologia que você gostaria de aprender?”, continue apresentando para ela o Prompt, para que ela complete o nome da tecnologia em questão. E, logo depois, apresente uma mensagem comentando algo sobre a linguagem inserida.

O importante é que a pessoa que estiver jogando possa sempre escolher qual decisão tomar para conseguir aprender e se desenvolver na área de programação.

Além disso, também é essencial que, ao final do jogo, ela possa inserir quantas tecnologias quiser na lista de aprendizado.

[Solução](https://github.com/wesleyLM/7DaysOfCode/blob/main/L%C3%B3gica%20JS%203-7%20Fluxo%20de%20decis%C3%A3o.html)

## 7DaysOfCode - Lógica JS 4/7: 👩🏽‍💻 Mais loops e randomização

Você deve criar um programinha que comece com um valor específico pré-definido entre 0 a 10 para o número que você vai adivinhar (7, por exemplo).

Em seguida, o programa vai perguntar para você qual o valor que você deseja chutar e, caso você acerte, ele irá te parabenizar. Caso erre, ele vai te dar mais 2 tentativas.

No fim, caso você não acerte nenhuma vez, ele vai imprimir qual era o número inicial.

Depois que o programinha estiver funcionando, tente usar um número randômico em vez de um número pré-definido.

[Solução](https://github.com/wesleyLM/7DaysOfCode/blob/main/L%C3%B3gica%20JS%204-7%20%F0%9F%91%A9%F0%9F%8F%BD%E2%80%8D%F0%9F%92%BB%20Mais%20loops%20e%20randomiza%C3%A7%C3%A3o.html)

## 7DaysOfCode - Lógica JS 5/7: Arrays e coleções

Então hoje, para facilitar a sua ida ao supermercado, você deve criar um programa em Javascript que perguntará se você deseja adicionar uma comida na sua lista de compras, e você deve poder responder com sim ou não.

Em seguida, ele perguntará qual comida você deseja inserir, e você digitará o nome dela, como por exemplo batata.

Depois, ele deverá perguntar em qual categoria essa comida se encaixa, com algumas opções já pré-definidas, como frutas, laticínios, congelados, doces e o que mais você achar interessante. Assim, você poderá separar tudo no seu devido grupo.

Por fim, caso você não queira mais adicionar nada na lista de compras e responder não na primeira pergunta, ele irá exibir uma lista com todos os itens agrupados, da seguinte forma:

Caso você adicione na sua lista:

´banana, leite em pó, tomate, leite vegetal, chiclete, bala de ursinho, maçã, uva, abacate e leite de vaca´

O programa deverá imprimir, por exemplo:

<code>Lista de compras:
  
    Frutas: banana, tomate, maçã, uva, abacate
    Laticínios: leite vegetal, leite de vaca, leite em pó
    Congelados:
    Doces: chiclete e bala de ursinho</code>
    

[Solução](https://github.com/wesleyLM/7DaysOfCode/blob/main/L%C3%B3gica%20JS%205-7%20Arrays%20e%20cole%C3%A7%C3%B5es.html)
