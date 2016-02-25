# Dicas para Desenvolvedores

## Usando um Debugger

A palavra chave `debugger` pode ser usada para fazer debug na sua aplicação. Quando a maioria dos browsers encontram um statemente `debugger`, a execução do JavaScript é parada, e o seu browser carregará esse `debugger`. Isso pode servir como `breakpoints` na sua aplicação. Por exemplo, se você escreve uma função que não retorna o que você espera, você pode adicionar um statemente `debugger` na primeira linha da função:

```javascript
function myBrokenFunction() {
      debugger;
      // faça outra coisa
}
```

Quando seu aplicativo for executado, será feita uma pausa nesta função. A partir daí, você pode usar as ferramentas de desenvolvimento do seu browser apenas para executar o JavaScript passo a passo. Isso vai permitir você ver exatamente qual linha ou função que está causando problemas na sua função.


