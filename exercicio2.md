# Exercício 2

Crie um campo label e um campo input na página HTML, e preencha o campo com o nome de mais uma fruta.
Depois disso, escreva **No DevTools** o código necessário para que seja possível imprimir o valor do input escrito no console.
Cole o comando aqui:
```jsx
    cole o código JS nesta área.
    function adicionar(){
        let nomeFruta = document.getElementById("nome").value
        let lista = document.getElementById("lista-de-frutas").innerHTML
        lista = lista + "<li>"+nomeFruta+"</li>"

        document.getElementById("lista-de-frutas").innerHTML = lista
    }
```