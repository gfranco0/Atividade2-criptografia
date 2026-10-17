# Criptografia Simples em C

Integrantes do grupo:
Joaquim Martins Ferreira Neto RGM: 47609630
Gabriel Franco RGM: 47451289

## Objetivo

Este trabalho foi feito para a disciplina de Algoritmo e Pensamento Computacional. A ideia é criar um programa simples em linguagem C que criptografa uma palavra usando a Cifra de César e uma sequência matemática.

A palavra escolhida pelo grupo foi **Paschoal**, o SHIFT usado foi **6** e a sequência escolhida foi a **Progressão Aritmética (PA)**.

## Como funciona

O programa usa duas camadas de criptografia aplicadas em conjunto:

### 1. Cifra de César
Na primeira camada, o programa desloca cada letra da palavra por um valor fixo de **6 posições** para frente no alfabeto.

### 2. Progressão Aritmética (PA)
Na segunda camada, o programa aplica um deslocamento dinâmico baseado na posição ordinal de cada letra na palavra. A sequência da PA utilizada é:

`1, 2, 3, 4, 5, 6, 7, 8`

Cada termo da sequência corresponde à posição da letra na palavra. O deslocamento total final de cada caractere é a soma do SHIFT fixo com o termo da PA (`6 + n`).

## Como executar

1. Tenha um compilador C instalado, como o GCC.
2. Salve o código com o nome `criptografia_pa.c`.
3. Abra o terminal na pasta onde o arquivo foi salvo.
4. Compile o programa com o comando:

```bash
gcc criptografia_pa.c -o criptografia
```
## arquivo de resultado

quando o programa é executado ele tenta salvar o resultado no arquivo `resultado_criptografia.txt`. o arquivo registra a palavra codificada o SHIFT o tipo da sequencia e a quantidade de letras

## conclusão

com este trabalho conseguimos praticar conceitos fundamentais da linguagem C, como variáveis, laços de repetição (for), condições (if/else), manipulação de caracteres e gravação de arquivos, também compreendemos como unir conceitos de matemática aplicada com criptografia simples
