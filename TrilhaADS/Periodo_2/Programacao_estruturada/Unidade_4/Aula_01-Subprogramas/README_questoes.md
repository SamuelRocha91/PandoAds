## Questões para praticar

---

### Questão 1: Em C++, qual a principal diferença entre uma função e um procedimento?

A) Procedimentos sempre retornam um valor, enquanto funções não.
B) Funções obrigatoriamente retornam um valor, enquanto procedimentos não.
C) Procedimentos são mais rápidos do que funções.
D) Funções só podem ser usadas dentro da main.

---

### Questão 2: Qual palavra-chave define uma função em C++ que não retorna um valor?

A) define
B) procedure
C) return
D) void

---

### Questão 3:  Sobre variáveis locais em funções, marque a alternativa correta:

A) São acessíveis de qualquer parte do programa.
B) Permanecem na memória durante toda a execução do programa.
C) Só existem durante a execução da função onde foram declaradas.
D) São inicializadas automaticamente com zero.

---

### Questão 4: O que acontece se uma função tenta acessar uma variável local de outra função?

A) O código compila normalmente e acessa a variável.
B) O código exibe um aviso, mas compila.
C) O compilador gera um erro, pois a variável não está no escopo.
D) A variável é convertida automaticamente para global.

---

### Questão 5: Qual das alternativas abaixo representa corretamente uma função recursiva para calcular fatorial?

A)
int fatorial(int n) {
    return n * fatorial(n - 1);
}
B)
int fatorial(int n) {
    if (n <= 1) return 1;
    return n * fatorial(n - 1);
}
C)
int fatorial(int n) {
    for (int i = n; i > 1; i--)
        n *= i;
    return n;
}
D)
void fatorial(int n) {
    return n * fatorial(n - 1);
}


---

### Questão 6: Sobre variáveis globais em C++, assinale a alternativa correta:

A) Podem ser acessadas de qualquer parte do código.
B) Devem ser declaradas dentro da main.
C) Só podem ser modificadas uma vez.
D) São automaticamente desalocadas após o uso.

---

### Questão 7: Qual das opções abaixo define corretamente uma função que recebe dois inteiros e retorna a soma deles?

A) 
void soma(int a, int b) {
    return a + b;
}

B)
int soma(int a, int b) {
    return a + b;
}

C) 
float soma(int a, int b) {
    cout << a + b;
}
D) 
int soma(int a, int b) {
    cout << a + b;
}


---

### Questão 8: Qual das alternativas abaixo representa corretamente a chamada de uma função int quadrado(int x)?

A) int y = quadrado(x);
B) quadrado x = y;
C) y = quadrado();
D) quadrado(int x);

---

### Questão 9: Qual alternativa descreve corretamente uma característica da recursividade?

A) Funções recursivas não podem ter condição de parada.
B) Recursividade sempre consome menos memória do que laços for.
C) Uma função recursiva sempre chama a si mesma dentro do bloco main.
D) Uma função recursiva deve ter pelo menos um caso base para evitar loops infinitos.

---

### Questão 10: Qual das alternativas abaixo contém um erro na definição da função?

A) 
int multiplica(int a, int b) {
    return a * b;
}

B) 
void mensagem() {
    cout << "Ola!";
}

C) 
int soma(int a, int b) {
    cout << a + b;
}

D) 
float divide(int x, int y) {
    return (float) x / y;
}

---


## Gabarito:

1) B;
2) D;
3) C;
4) C;
5) B;
6) A;
7) B;
8) A;
9) D;
10) C;
