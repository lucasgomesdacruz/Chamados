# Dev Controle - Sistema de Gerenciamento de Clientes e Chamados
### Dev Controle é um sistema web desenvolvido com Next.js, Prisma ORM, MongoDB e TailwindCSS para gerenciar clientes e chamados de atendimento de forma eficiente e fácil.

## Funcionalidades
### Autenticação com Google: Login e autenticação usando o NextAuth com o provedor Google.
### Cadastro de Clientes: Criação, visualização e exclusão de clientes com informações como nome, email, telefone e endereço.
### Gerenciamento de Chamados: Abertura e acompanhamento de chamados com status "Aberto", associando clientes a tickets.
### Validação de Formulários: Utiliza react-hook-form para validação de entradas de formulário com zod.
### Backend em Isomorfismo: Renderização no lado do cliente e do servidor com Next.js para maximizar a performance e a experiência do usuário.
### Banco de Dados: Utiliza Prisma como ORM para interação com o banco de dados relacional PostgreSQL e MongoDB.

### Tecnologias Usadas
### Next.js: Framework React para desenvolvimento isomórfico.
### Prisma: ORM para interagir com o banco de dados.
### MongoDB: Banco de dados não-relacional utilizado para armazenar informações do cliente e chamados.
### NextAuth: Autenticação com Google.
### React Hook Form: Para fácil validação de formulários.
### Tailwind CSS: Framework de CSS para criação de UI responsiva e estilosa.


### Como Usar
### Criar um Novo Cliente
### Vá até a página de clientes.
### Clique em "Novo Cliente".
### Preencha os campos necessários como nome, email, telefone e endereço.
### O cliente será salvo no banco de dados e listado na página de clientes.
### Abrir um Novo Chamado
### Acesse o dashboard.
### Clique em "Abrir Chamado".
### Associe o chamado a um cliente e defina o status como "Aberto".
### O chamado será registrado é listado na interface.
