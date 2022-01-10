# tdd-notes

### Ordem de execuçao de testes

- Preparar cenário de testes
- Executar a ação a ser testada
- Comparar resultados


## Sobre testes de unidade

Ao implementar testes automatizados é importante que estes sejam descritivos o suficiente para indicar o que eles estão fazendo, isto é, o que está sendo testado.

Em testes de unidade é interessente separar os testes para cada comportamento que está sendo testado.

Para evitar o uso excessivo de comentários no código para explicar o cenário de testes podemos adotar um estilo de nomeclatura que torne os nomes dos testes descritivos

```
[nomeDoMetodo]_[estadoDoTeste]_[resultadoEsperado]
deve_[resultadoEsperado]_[estadoDeTeste]
```

Ao utilizar properties de classe, a cada execução de teste é criada uma instância nova da classe de teste.
