# Planejamento de Desenvolvimento

O sistema será desenvolvido com foco em simplicidade, organização e aprendizado. As tecnologias foram escolhidas de forma a permitir a implementação por etapas, com recursos acessíveis e bem documentados.

## Tecnologias utilizadas

- **Front-end:** HTML, CSS e JavaScript nativo (sem utilização de frameworks)
- **Back-end:** PHP estruturado, sem uso de frameworks
- **Banco de dados:** MySQL

Essa combinação oferece boa integração entre as camadas e facilita o desenvolvimento sem necessidade de bibliotecas ou estruturas complexas neste momento.

## Estrutura do projeto

O sistema será dividido em três camadas principais:

### 1. Apresentação (front-end)
- Interface visual baseada nos protótipos definidos
- Navegação entre telas utilizando HTML
- Estilização com CSS
- Utilização de JavaScript nativo para validações e interações simples com o usuário

### 2. Lógica de negócio (back-end)
- Código PHP responsável por:
  - Autenticação de login
  - Registro de faltas e notas
  - Consulta de dados no banco
  - Geração de relatórios
- Arquivos organizados por funcionalidades específicas (ex: login.php, notas.php)

### 3. Persistência (banco de dados)
- MySQL com tabelas baseadas no modelo relacional definido
- Todas as ações do sistema interagem com o banco de dados, garantindo integridade e consistência das informações

## Abordagem de desenvolvimento

O desenvolvimento será dividido por etapas, priorizando as funcionalidades essenciais:

1. Tela de login e autenticação do professor  
2. Dashboard com menu lateral e navegação  
3. Listagem das turmas e alunos  
4. Registro de faltas do dia  
5. Lançamento de notas  
6. Visualização e exportação de relatórios

Após essas etapas, melhorias e funcionalidades adicionais poderão ser implementadas de acordo com a disponibilidade de tempo e necessidade do sistema.

*Funcionalidades extras e otimizações poderão ser exploradas ao final do processo de desenvolvimento.*
