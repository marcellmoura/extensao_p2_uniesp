# Modelo de Dados

## Entidades e Relacionamentos

### Professor
- id_professor (PK)
- nome
- usuario
- senha

### Disciplina
- id_disciplina (PK)
- nome

### Turma
- id_turma (PK)
- nome
- ano (ex: 6º ano)
- turno (manhã/tarde)
- ano_letivo

### Professor_Turma_Disciplina
(Tabela de ligação entre professor, turma e disciplina)
- id (PK)
- id_professor (FK)
- id_turma (FK)
- id_disciplina (FK)

### Aluno
- id_aluno (PK)
- nome
- data_nascimento

### Matricula
- id_matricula (PK)
- id_aluno (FK)
- id_turma (FK)
- data_entrada
- data_saida (pode ser nulo)

### Nota
- id_nota (PK)
- id_matricula (FK)
- id_disciplina (FK)
- descricao_avaliacao (ex: Prova 1)
- valor

### Frequencia
- id_frequencia (PK)
- id_matricula (FK)
- id_disciplina (FK)
- data
- presente (booleano: true/false)

---

## Diagrama ER

*O diagrama entidade-relacionamento deste modelo está em construção e será adicionado ao repositório em breve.*
