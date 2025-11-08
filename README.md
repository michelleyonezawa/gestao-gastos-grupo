1) Cadastro de um Usuário
Como um usuário do software,
Eu quero me cadastrar no sistema,
Para que eu possa acessar as funcionalidades de criação e gestão de grupos de gastos.

Regras de Negócio:
- O e-mail deve ser único, não podendo existir dois usuários com o mesmo e-mail.
- A senha deve possuir no mínimo 6 caracteres.
- Todos os campos obrigatórios devem ser preenchidos (nome, e-mail e senha).

2) Cadastro de um Grupo
Como um usuário autenticado,
Eu quero criar um grupo,
Para que eu possa gerenciar gastos compartilhados com outras pessoas.

Regras de Negócio:
- Cada grupo deve possuir um nome único.
- O usuário criador deve ser automaticamente adicionado ao grupo como integrante.
- O grupo deve ter ao menos um usuário vinculado no momento da criação.

3) Entrada de um Usuário em um Grupo Existente
Como um usuário já cadastrado,
Eu quero entrar em um grupo já existente,
Para que eu possa acompanhar e registrar gastos compartilhados com seus membros.

Regras de Negócio:
- O usuário só pode entrar em um grupo se não fizer parte dele atualmente.
- Deve existir um código ou identificador do grupo para entrada.
- O grupo deve estar ativo (não arquivado/excluído).

4) Registro de Gasto por Integrante
Como um integrante de um grupo,
Eu quero registrar um gasto que realizei,
Para que os demais membros possam visualizar e considerar esse gasto no balanço do grupo.

Regras de Negócio:
- O gasto deve estar associado a um grupo e a um usuário.
- O valor do gasto deve ser maior que zero.
- Deve ser registrado a data do gasto.
- O usuário só pode registrar gasto em grupos dos quais faça parte.

5) Visualização de Gastos do Grupo
Como um integrante de um grupo,
Eu quero visualizar os gastos realizados por cada membro,
Para que eu possa acompanhar o fluxo financeiro e entender o total gasto.

Regras de Negócio:
- O usuário só pode visualizar gastos de grupos dos quais participa.
- Deve ser possível visualizar o gasto detalhado (valor, data, autor e descrição).
- O sistema deve permitir visualizar o total de gastos por integrante e o total do grupo.
