# robotron-2000

//  Propriedades e métodos para alterar elementos no HTML
    
element.innerHTML - Esta propriedade obtém ou altera qualquer elemento no HTML, inclusive tags.
element.innerText - Esta propriedade permite inserir textos no HTML.
element.attribute - Esta propriedade altera o valor de um elemento HTML
element.setAttribute(atributo, valor) - Este método altera o valor de um atributo de um elemento HTML.

//  Adicionando e excluindo elementos

document.write() - Escreve no fluxo de saída do HTML.
document.appendChild() - Adiciona um elemento HTML.
document.removeChild() - Remove um elemento HTML.
document.replaceChild() - Substitui um elemento HTML.
document.createElement() - Cria um elemento HTML.

Mudar o texto de algo (document.getElementById('texto').innerText="Escreva o texto aqui")

//HOISTING

//COMO RETIRAR UM ELEMENTO DO ARRAY??

var lista = ["Laranja", "Vermelho", "Branco", "Amarelo", "Rosa"]; 

lista.splice(1,1)

console.log(lista);

//DATA ATTRIBUTES

A primeira parte é o identificador deste dado, que consiste em data- + o nome de sua escolha que melhor identifica o tipo de dado a ser atribuído.
A segunda parte é o valor atribuído à este data-attribute, este valor deve sempre estar entre aspas “”, e dessa maneira é lido como uma string.