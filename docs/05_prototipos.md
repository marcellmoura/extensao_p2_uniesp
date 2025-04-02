# Protótipos das Telas

## Tela de Login

A tela de login será simples e objetiva, com os seguintes elementos:

- Campo para nome de usuário (texto)
- Campo para senha (texto oculto)
- Botão "Entrar"
- Link "Esqueci minha senha" (opcional)
- Mensagem de erro caso os dados estejam incorretos

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Principal (Dashboard)

Após o login, o professor é direcionado à tela principal do sistema, onde encontrará um layout com menu lateral fixo à esquerda da tela e o conteúdo à direita.

**Elementos do menu lateral:**
- Logo da escola ou nome do sistema (no topo)
- Botão "Minhas Turmas"
- Botão "Registrar Faltas"
- Botão "Lançar Notas"
- Botão "Relatórios"
- Botão "Trocar Senha"
- Botão "Sair"

**Área principal da tela (à direita do menu):**
- Mensagem de boas-vindas ("Bem-vindo, Professor Marcell")
- Informações básicas (ex: data atual, nome completo, turma atual selecionada)
- Atalhos para ações recentes (opcional)

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Minhas Turmas

Essa tela exibe uma lista simples com todas as turmas atribuídas ao professor.

Cada item da lista apresenta as seguintes informações:

- Nome da turma (ex: 6º Ano A)
- Nome da disciplina (ex: Matemática)
- Turno (ex: manhã)
- Dias da semana em que a aula ocorre (ex: segunda e quarta-feira)
- Horário da aula (ex: 08:00 às 09:30)

Ao lado de cada turma há um botão "Visualizar" que leva o professor à tela com a lista de alunos daquela turma.

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Alunos da Turma

Essa tela exibe uma tabela com todos os alunos da turma selecionada.

**Elementos exibidos por aluno:**
- Nome completo
- Total de faltas
- Média das notas

**Abaixo da tabela há dois botões:**
- "Registrar Faltas do Dia": leva para a tela onde o professor marca quais alunos faltaram na data atual.
- "Lançar Notas": leva para a tela onde o professor insere as notas da avaliação selecionada.

Também pode haver um botão "Voltar" para retornar à tela anterior.

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Registrar Faltas do Dia

Essa tela permite ao professor registrar a frequência dos alunos da turma para a data atual.

**Elementos da tela:**
- Data atual exibida no topo da tela (com possibilidade de edição, se necessário)
- Lista de alunos da turma com caixas de seleção ao lado de cada nome
  - Alunos marcados como "ausente"
  - Alunos não marcados são considerados "presentes"
- Botão "Salvar Faltas"
- Mensagem de confirmação ao salvar

Ao clicar em "Salvar Faltas", o sistema registra a ausência dos alunos selecionados, associando à turma, disciplina e data.

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Lançar Notas

Essa tela permite ao professor lançar as notas de uma avaliação para os alunos da turma.

**Elementos da tela:**
- Nome da turma e disciplina (no topo)
- Campo para inserir o nome ou descrição da avaliação (ex: Prova 1, Trabalho 2)
- Lista de alunos com campos de input ao lado de cada nome para digitação da nota (ex: campo numérico de 0 a 10)
- Botão "Salvar Notas"
- Mensagem de confirmação após o salvamento

Ao clicar em "Salvar Notas", o sistema registra os valores informados para a avaliação, vinculando-os ao aluno, turma e disciplina.

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*

---

## Tela Relatórios da Turma

Essa tela exibe um relatório geral da turma selecionada, com as principais informações de desempenho e frequência dos alunos.

**Elementos da tela:**
- Nome da turma e disciplina
- Tabela com as seguintes colunas:
  - Nome do aluno
  - Média das notas
  - Total de faltas

**Outros elementos:**
- Botão "Gerar PDF" para exportar o relatório
- Botão "Voltar" para retornar à tela anterior

O relatório pode ser gerado em formato PDF, facilitando o envio ou impressão para a coordenação pedagógica.

*O protótipo visual desta tela será elaborado no Figma e adicionado ao repositório posteriormente.*
