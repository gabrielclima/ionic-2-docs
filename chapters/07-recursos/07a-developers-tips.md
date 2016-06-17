# Dicas para Desenvolvedores Ionic

## Usando um Debugger

A palavra chave `debugger` pode ser usada para depurar sua aplicação. Quando a maioria dos browsers encontram uma declaração `debugger`, a execução do JavaScript é interrompida, e o seu browser carregará a depuração. Isso pode ser usado para pôr `breakpoints` na sua aplicação. Por exemplo, se você escreve uma função que não retorna o que você espera, você pode adicionar declarar um debugger na primeira linha da função:

```javascript
function minhaFuncaoZoada() {
      debugger;
      // faça outra coisa
}
```

Quando seu aplicativo for executado, isso irá fazer uma pausa nesta função. A partir daí, você pode usar as ferramentas de desenvolvimento do seu browser para executar apenas o JavaScript passo a passo. Isso vai permitir você ver exatamente qual linha ou função que está causando problemas na sua função.

## Trocando a Plataforma

Por padrão, quando você exibir seu aplicativo no navegador, o Ionic irá aplicar o tema do iOS. No entanto, uma vez que componentes Ionic podem se adaptar de acordo com a sua plataforma, isso pode ser útil para possibilitar que você veja como seu app seria exibido no Android. Para fazer isso, simplesmente adicione `?ionicplatform=android` na URL onde seu app está sendo servido: `http://localhost:8100/?ionicplatform=android`. Isso irá mudar a forma que o Ionic vê em qual plataforma você está.




