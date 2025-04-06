## Questões para praticar

---

### Questão 1: Sobre variáveis compostas homogêneas, é correto afirmar que:

A) Elas podem armazenar valores de diferentes tipos de dados.
B) São conhecidas como structs em C++.
C) Arrays são um exemplo de variáveis compostas homogêneas.
D) Sempre possuem tamanho variável na memória.

---

### Questão 2:   Em relação a variáveis compostas heterogêneas, marque a alternativa correta:

A) São usadas para armazenar dados do mesmo tipo.
B) Structs e classes podem ser exemplos desse tipo de variável.
C) Um array de inteiros é um exemplo de variável composta heterogênea.
D) São sempre armazenadas em memória contígua.

---

### Questão 3: Considere a declaração int matriz[3][2];. Quantos elementos a matriz pode armazenar?

A) 3
B) 5
C) 6
D) 9

---

### Questão 4: Qual alternativa representa a forma correta de acessar o elemento da segunda linha e primeira coluna da matriz int mat[4][4];?

A) mat(2,1)
B) mat[2][1]
C) mat[1][0]
D) mat[1][1]

---

### Questão 5: Qual é a principal vantagem do uso de arrays multidimensionais?

A) Aumentam o desempenho dos programas automaticamente.
B) Permitem representar estruturas como tabelas e imagens.
C) Reduzem o consumo de memória drasticamente.
D) Eliminam a necessidade de uso de laços de repetição.

---

### Questão 6: Em um array bidimensional int arr[3][4];, quantas colunas existem?

A) 3
B) 4
C) 7
D) 12

---

### Questão 7: Qual das alternativas abaixo inicializa corretamente uma matriz 2x2 de inteiros em C++?

A) int mat[2][2] = {1, 2, 3, 4};
B) int mat[2][2] = {{1, 2}, {3, 4}};
C) int mat[2][2] = [1, 2, 3, 4];
D) int mat[2,2] = {1, 2, 3, 4};

---

### Questão 8:  Considerando float notas[3][2], como acessar o último elemento corretamente?

A) notas[2][1]
B) notas[3][2]
C) notas[1][2]
D) notas[2][2]

---

### Questão 9: O que acontece se tentarmos acessar um índice fora dos limites de um array em C++?

A) O programa sempre exibe um erro de compilação.
B) O código para de executar imediatamente.
C) O programa pode apresentar comportamento indefinido.
D) O compilador ajusta automaticamente os índices para um valor válido.

---

### Questão 10: Qual código soma corretamente todos os elementos da matriz int M[2][3] = {{1, 2, 3}, {4, 5, 6}};?

A)
int soma = 0;
for (int i = 1; i <= 2; i++)
    for (int j = 1; j <= 3; j++)
        soma += M[i][j];
B)
int soma = 0;
for (int i = 0; i < 2; i++)
    for (int j = 0; j < 3; j++)
        soma += M[i][j];
C)
int soma = 0;
for (int i = 0; i < 3; i++)
    for (int j = 0; j < 2; j++)
        soma += M[i][j];
D)
int soma = 0;
for (int i = 1; i < 2; i++)
    for (int j = 1; j < 3; j++)
        soma += M[i][j];

---



## Gabarito:

1) C;
2) B;
3) C;
4) C;
5) B;
6) B;
7) B;
8) A;
9) C;
10) B;
