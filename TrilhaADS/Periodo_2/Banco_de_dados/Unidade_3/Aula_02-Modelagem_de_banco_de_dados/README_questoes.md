## Questões para praticar

---

### Questão 1: O que é um modelo de dados conceitual?

A) Uma representação abstrata dos dados, sem preocupação com implementação.
B) A estrutura física do banco de dados no SGBD.
C) Um conjunto de tabelas e índices otimizados para consultas rápidas.
D) A implementação do banco de dados diretamente no ambiente de produção.

---

### Questão 2: No Modelo Entidade-Relacionamento (MER), uma entidade-tipo representa:

A) Um objeto real ou abstrato do mundo real com significado para o banco de dados.
B) Um atributo dentro de uma entidade.
C) Um relacionamento entre duas ou mais entidades.
D) Um índice criado para otimizar buscas em uma tabela.

---

### Questão 3: Em um modelo de dados, os atributos representam:

A) Características ou propriedades das entidades.
B) Relações entre entidades.
C) As tabelas físicas do banco de dados.
D) Regras de negócio aplicadas no banco de dados.

---

### Questão 4:  Um relacionamento no MER conecta:

A) Apenas duas entidades obrigatoriamente.
B) Atributos entre si.
C) Uma ou mais entidades para representar associações entre elas.
D) Tabelas no banco de dados físico.

---

### Questão 5: Qual das alternativas define corretamente um relacionamento do tipo 1:N (um para muitos)?

A) Uma entidade pode se relacionar com várias outras entidades, e estas só podem estar relacionadas a uma única entidade.
B) Ambas as entidades podem se relacionar com várias instâncias uma da outra.
C) Uma entidade se relaciona obrigatoriamente com apenas uma outra entidade.
D) O relacionamento é obrigatório em ambas as direções.

---

### Questão 6: A cardinalidade de um relacionamento refere-se a:

A) A quantidade mínima e máxima de ocorrências de uma entidade que pode se associar a outra entidade.
B) O número de tabelas envolvidas na relação.
C) O tipo de chave primária utilizada no banco de dados.
D) O número total de atributos de uma entidade.

---

### Questão 7: Qual das alternativas apresenta um tipo de cardinalidade correto?

A) (0,1), (1,1), (1,N), (0,N).
B) (0,0), (1,2), (2,3), (N,M).
C) (A,B), (B,N), (X,Y), (0,3).
D) (1,1), (2,2), (3,N), (N,0).

---

### Questão 8: Qual é um exemplo de um relacionamento do tipo N:M (muitos para muitos)?

A) Um professor pode dar aula para vários alunos e um aluno pode ter vários professores.
B) Um carro pertence a uma única pessoa.
C) Um funcionário gerencia apenas um departamento.
D) Um país tem um único presidente.

---

### Questão 9: O que caracteriza um relacionamento do tipo especial agregação?

A) Um relacionamento entre um relacionamento e uma entidade.
B) Um relacionamento que ocorre apenas em bancos NoSQL.
C) A criação de tabelas físicas para armazenar dados de relacionamento.
D) Um tipo de relacionamento exclusivo para chaves primárias compostas.

---

### Questão 10: Qual das afirmativas sobre chaves primárias está correta?

A) A chave primária é um identificador único para cada tupla da entidade.
B) Uma entidade não pode ter mais de uma chave primária.
C) Chaves primárias sempre possuem um único atributo.
D) O banco de dados escolhe automaticamente a chave primária de uma tabela.

---

### Questão 11: Qual alternativa define corretamente uma chave estrangeira?

A) Um atributo ou conjunto de atributos que referenciam a chave primária de outra entidade.
B) Um identificador único dentro de uma entidade.
C) Um atributo que pode ter valores repetidos dentro de uma entidade.
D) Uma chave que não pode ser utilizada em relacionamentos.

---

### Questão 12: Qual é a principal função dos índices em um banco de dados?

A) Melhorar a performance das consultas, facilitando a busca de dados.
B) Definir relacionamentos entre tabelas.
C) Garantir a integridade referencial entre entidades.
D) Criar backups automáticos das tabelas do banco.

---

### Questão 13: Na teoria da normalização, qual das alternativas define corretamente a Primeira Forma Normal (1FN)?

A) Uma tabela está na 1FN se não possuir atributos multivalorados ou compostos.
B) Uma tabela está na 1FN se todos os atributos forem chaves primárias.
C) Uma tabela está na 1FN apenas se não houver chaves estrangeiras.
D) A 1FN não é necessária para evitar redundância de dados.

---

### Questão 14: A Terceira Forma Normal (3FN) exige que:

A) A tabela esteja na 2FN e que todos os atributos não-chave sejam dependentes apenas da chave primária.
B) A tabela esteja na 1FN e não tenha atributos compostos.
C) Todas as chaves estrangeiras sejam removidas.
D) Nenhuma relação tenha cardinalidade maior que 1:N.

---

### Questão 15: Qual das seguintes afirmações sobre normalização está INCORRETA?

A) O objetivo da normalização é reduzir a redundância e melhorar a integridade dos dados.
B) A normalização pode aumentar a complexidade das consultas devido ao uso de mais tabelas.
C) A Desnormalização é sempre recomendada, pois melhora a performance.
D) Uma tabela na 3FN evita dependências transitivas.

---

## Gabarito:

1) A;
2) A;
3) A;
4) C;
5) A;
6) A;
7) A;
8) A;
9) A;
10) A;
11) A;
12) A;
13) A;
14) A;
15) C;
