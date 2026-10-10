# Criptografia Simples em C

## objetivo

esse trabalho foi feito para a disciplina de Algoritmo e Pensamento Computacional. a ideia é criar um programa simples em linguagem C que criptografa uma palavra usando a cifra de cesar e uma sequencia matematica.

A palavra escolhida pelo grupo é **Abacate**, o SHIFT usado é **3** e a sequencia escolhida foi Fibonacci.

## como funciona

O programa usa duas camadas de criptografia

### 1. Cifra de Cesar

na primeira camada o programa muda cada letra 3 posições para frente no alfabeto. por exemplo a letra A vira D e a letra B vira E

### 2. Sequencia de Fibonacci

na segunda camada o programa usa os numeros da sequencia de Fibonacci para deslocar as letras novamente. a sequencia usada é:

`1, 1, 2, 3, 5, 8, 13`

Cada numero é usado na posição correspondente da palavra. assim cada letra pode ter um deslocamento diferente

## como executar

1. Tenha um compilador C instalado, como o GCC
2. Salve o codigo com o nome `atividade_abacate_fibonacci.c`
3. Abra o terminal na pasta onde o arquivo foi salvo
4. Compile o programa com o comando:

```bash
gcc atividade_abacate_fibonacci.c -o atividade
```
## arquivo de resultado

quando o programa é executado ele tenta salvar o resultado no arquivo `resultado_criptografia.txt`. o arquivo registra a palavra codificada o SHIFT o tipo da sequencia e a quantidade de letras

## conclusão

com esse trabalho conseguimos praticar alguns conceitos de C como variaveis, laços de repetição, condições e gravação em arquivos. também aprendemos como usar uma sequencia matematica junto com uma cifra simples para mudar uma palavra
