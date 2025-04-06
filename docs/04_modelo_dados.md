# Modelo de Dados

## Entidades e Relacionamentos

### USUARIO
- id (PK)
- nome
- usuario
- senha
- tipo_usuario (admin, coordenador, professor)

### TURMA
- id (PK)
- nome_turma

### DISCIPLINA
- id (PK)
- nome_disciplina

### USUARIO_TURMA_DISCIPLINA
(Tabela de ligação entre professor, turma e disciplina)
- id (PK)
- id_usuario (FK → USUARIO)
- id_turma (FK → TURMA)
- id_disciplina (FK → DISCIPLINA)

### ALUNO
- id (PK)
- numero_matricula
- nome
- data_nascimento
- nome_responsavel (opcional)

### ALUNO_TURMA
(Vínculo do aluno com a turma)
- id (PK)
- id_aluno (FK → ALUNO)
- id_turma (FK → TURMA)
- data_ingresso
- data_saida (opcional)
- status (ativo, concluído, transferido)

### AVALIACAO
- id (PK)
- id_usuario_turma_disciplina (FK → USUARIO_TURMA_DISCIPLINA)
- titulo
- descricao
- data_aplicacao
- peso (opcional)

### NOTA
- id (PK)
- id_aluno_turma (FK → ALUNO_TURMA)
- id_avaliacao (FK → AVALIACAO)
- valor
- data_lancamento

### FREQUENCIA
- id (PK)
- id_aluno_turma (FK → ALUNO_TURMA)
- id_usuario_turma_disciplina (FK → USUARIO_TURMA_DISCIPLINA)
- data_frequencia
- presente (1 = sim, 0 = não)

### ANOTACAO_ALUNO
- id (PK)
- id_usuario (FK → USUARIO)
- id_aluno_turma (FK → ALUNO_TURMA)
- data_anotacao
- texto_anotacao

### AGENDA_ESCOLAR
- id (PK)
- id_usuario_turma_disciplina (FK → USUARIO_TURMA_DISCIPLINA)
- dia_semana
- hora_inicio
- hora_fim

### COMUNICADO
- id (PK)
- id_usuario_remetente (FK → USUARIO)
- titulo
- mensagem
- data_envio

### CALENDARIO_ESCOLAR
- id (PK)
- titulo
- descricao
- data_evento
- tipo_evento (ex: feriado, reunião, prova)

---

## Diagrama ER

O diagrama entidade-relacionamento completo pode ser visualizado no link abaixo:

[Visualizar DER no Google Drive](https://drive.google.com/file/d/1FernGLp6eQat9t5ap18EXrTltOUP8hOV/view?usp=sharing)

