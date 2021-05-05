# AFD
Autômato finito determinístico

Devem ser inseridos dois arquivos: 

O automato.txt com a estrutura do automato, como no exemplo: 

```
q1 q2 q3 q4 # Linha com o conjunto de estados, separados por espa¸co
0 1 # Linha com o alfabeto, s´ımbolos separados por espa¸co
q1 # inicio da descricao da matriz linha 0, coluna 0
q1 q2 # linha 0, coluna 1
* # linha 0, coluna 2
q3 # matriz linha 1, coluna 0
*
q3
* # matriz linha 2, coluna 0
q4
*
q4 # matriz linha 3, coluna 0
q4
*
q1 # estado inicial
q4 # estados finais
```

E o arquivo entrada.txt com as entradas a serem testadas, como no exemplo: 
```
0 1 1 0 1 0 1
0 1 0 1 1 1 0
1 1 0 1 0 1 0
```

O simulador gerará o arquivo passos.txt descrevendo os passos de execução do AFN e o arquivo resultado.txt com o resultado para cada entrada.
