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
