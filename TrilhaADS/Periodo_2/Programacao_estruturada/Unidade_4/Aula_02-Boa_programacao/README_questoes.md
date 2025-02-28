## Questões para praticar

---

### Questão 1: O que é um algoritmo?

A) Um conjunto finito de passos para resolver um problema.
B) Um código escrito em qualquer linguagem de programação.
C) Um compilador que traduz código-fonte para binário.
D) Um tipo de dado utilizado para armazenar valores numéricos.

---

### Questão 2: Qual a importância da indentação no código-fonte?

A) Deixa o código mais rápido.
B) Facilita a leitura e manutenção do código.
C) Evita erros de compilação.
D) Reduz o tamanho do executável.

---

### Questão 3:  Como armazenar corretamente um caractere acentuado em C++ sem problemas de compatibilidade?

A) Usar o tipo char e armazenar diretamente.
B) Utilizar setlocale(LC_ALL, "") para configurar a codificação correta.
C) Apenas evitar o uso de caracteres acentuados.
D) Escrever caracteres acentuados dentro de printf(), pois isso corrige o problema.

---

### Questão 4: Qual a principal característica da pesquisa sequencial?

A) Funciona apenas em vetores ordenados.
B) Sempre encontra o elemento na primeira tentativa.
C) Percorre os elementos um por um até encontrar o valor desejado.
D) Usa divisão e conquista para acelerar a busca.

---

### Questão 5: Qual é o tamanho ocupado por um int na maioria dos sistemas de 64 bits?

A) 2 bytes
B) 4 bytes
C) 8 bytes
D) Depende do valor armazenado

---

### Questão 6: O que a função rand() faz em C++?

A) Retorna sempre o mesmo número.
B) Retorna um número pseudoaleatório.
C) Gera um número completamente aleatório baseado no hardware.
D) Somente funciona em sistemas operacionais Unix.

---

### Questão 7: Como garantir que rand() gere números diferentes a cada execução do programa?

A) Chamando rand() várias vezes antes de usar o valor.
B) Utilizando srand(time(0)) antes de chamar rand().
C) Somando 1 ao valor retornado por rand().
D) rand() sempre gera números diferentes automaticamente.

---

### Questão 8: Qual alternativa representa corretamente um código para gerar um número aleatório entre 1 e 100?

A)
int x = rand() % 100;

B) 
int x = rand() % 100 + 1;

C) 
int x = rand(1, 100);

D)
int x = random(1, 100);


---

### Questão 9: Qual alternativa contém um erro na declaração de variáveis em C++?

A) int idade = 25;
B) float altura = 1.75;
C) char letra = "A";
D) double preco = 99.99;

---

### Questão 10: Qual código abaixo realiza uma pesquisa sequencial corretamente em um vetor de inteiros?

A) 
for (int i = 0; i < n; i++) {
    if (vetor[i] == valor) {
        return i;
    }
}

B)
for (int i = 0; i < n; i++) {
    if (vetor[i] = valor) {
        return i;
    }
}

C) 
while (vetor[i] != valor) {
    return i;
}

D)
for (int i = 0; i < n; i++) {
    cout << vetor[i] == valor;
}


---

## Gabarito:

1) A;
2) B;
3) B;
4) C;
5) B;
6) B;
7) B;
8) B;
9) C;
10) A;
