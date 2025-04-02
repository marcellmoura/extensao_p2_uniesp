# Casos de Uso

## Caso de Uso 01: Login do Professor

**Ator principal:** Professor  
**Pré-condição:** O professor já está cadastrado no sistema com seu nome de usuário (sem acentos e minúsculo, ex: marcellmoura) e senha.  
**Descrição:** O professor acessa o sistema pelo navegador, em seu computador ou celular, clicando em um link fornecido pela escola. Ele informa seu nome de usuário e senha. O sistema verifica os dados e, se estiverem corretos, redireciona o professor para o painel principal.  
**Pós-condição:** O professor está autenticado no sistema.

---

## Caso de Uso 02: Acesso ao Painel Principal

**Ator principal:** Professor  
**Pré-condição:** O professor está autenticado no sistema.  
**Descrição:** Após o login, o professor é direcionado para o painel principal (dashboard). Nessa tela, ele vê uma mensagem de boas-vindas e os seguintes botões:  
- Minhas Turmas  
- Lançar Notas  
- Registrar Faltas  
- Relatórios  
- Trocar Senha  
Cada botão leva a uma funcionalidade específica do sistema.  
**Pós-condição:** O professor pode navegar pelas funcionalidades disponíveis.

---

## Caso de Uso 03: Visualizar Turmas

**Ator principal:** Professor  
**Pré-condição:** O professor está autenticado e acessou a opção "Minhas Turmas".  
**Descrição:** O sistema exibe uma lista com as turmas atribuídas ao professor, mostrando:  
- Nome da turma  
- Disciplina  
- Dias e horários das aulas  
O professor pode clicar em uma turma para visualizar os alunos.  
**Pós-condição:** O professor escolhe uma turma para gerenciar.

---

## Caso de Uso 04: Visualizar Alunos da Turma

**Ator principal:** Professor  
**Pré-condição:** O professor clicou em uma turma para visualizar os alunos.  
**Descrição:** O sistema mostra a lista de alunos da turma, com:  
- Nome do aluno  
- Quantidade total de faltas  
- Média atual de notas  
Abaixo da lista, o sistema apresenta dois botões:  
- Registrar Faltas do Dia  
- Lançar Notas  
**Pós-condição:** O professor tem acesso às informações da turma e pode realizar ações.

---

## Caso de Uso 05: Registrar Faltas

**Ator principal:** Professor  
**Pré-condição:** O professor está na tela da turma e clicou em "Registrar Faltas do Dia".  
**Descrição:** O sistema exibe uma lista com todos os alunos e caixas de seleção para marcar os que faltaram. O professor seleciona os alunos ausentes e clica em "Salvar". O sistema registra as faltas com a data atual.  
**Pós-condição:** As faltas do dia são registradas no sistema.

---

## Caso de Uso 06: Lançar Notas

**Ator principal:** Professor  
**Pré-condição:** O professor está na tela da turma e clicou em "Lançar Notas".  
**Descrição:** O sistema exibe a lista de alunos com campos para digitar as notas de uma avaliação (ex: Prova 1). O professor preenche os valores e clica em "Salvar".  
**Pós-condição:** As notas da avaliação são salvas no sistema e atualizam a média do aluno.

---

## Caso de Uso 07: Visualizar Relatório da Turma

**Ator principal:** Professor  
**Pré-condição:** O professor clicou na opção "Relatórios" no painel principal.  
**Descrição:** O sistema exibe uma tabela com todos os alunos da turma, contendo:  
- Nome  
- Média de notas  
- Total de faltas  
Há também a opção de gerar um arquivo PDF com esse relatório, para fins de consulta ou envio à coordenação.  
**Pós-condição:** O professor visualiza e, se desejar, imprime o relatório da turma.

---

## Caso de Uso 08: Trocar Senha

**Ator principal:** Professor  
**Pré-condição:** O professor está autenticado e clicou na opção "Trocar Senha".  
**Descrição:** O sistema solicita a senha atual e a nova senha. O professor preenche os campos e confirma a alteração. O sistema atualiza os dados de acesso.  
**Pós-condição:** O professor passa a utilizar a nova senha para futuros acessos.
