# Dev Controle - Sistema de Gerenciamento de Clientes e Chamados
### Dev Controle é um sistema web desenvolvido com Next.js, Prisma ORM, MongoDB e TailwindCSS para gerenciar clientes e chamados de atendimento de forma eficiente e fácil.
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_25_PM](https://github.com/user-attachments/assets/625fecb1-acd2-4fe6-b536-0e26dd5cdac1)

## Funcionalidades
### Autenticação com Google: Login e autenticação usando o NextAuth com o provedor Google.
### Cadastro de Clientes: Criação, visualização e exclusão de clientes com informações como nome, email, telefone e endereço.
### Gerenciamento de Chamados: Abertura e acompanhamento de chamados com status "Aberto", associando clientes a tickets.
### Validação de Formulários: Utiliza react-hook-form para validação de entradas de formulário com zod.
### Backend em Isomorfismo: Renderização no lado do cliente e do servidor com Next.js para maximizar a performance e a experiência do usuário.
### Banco de Dados: Utiliza Prisma como ORM para interação com o banco de dados relacional PostgreSQL e MongoDB.
### Abertura de Chamados sem Login: Usuários não autenticados podem abrir um chamado através de um link público gerado pelo sistema.

### Tecnologias Usadas
### Next.js: Framework React para desenvolvimento isomórfico.
### Prisma: ORM para interagir com o banco de dados.
### MongoDB: Banco de dados não-relacional utilizado para armazenar informações do cliente e chamados.
### NextAuth: Autenticação com Google.
### React Hook Form: Para fácil validação de formulários.
### Tailwind CSS: Framework de CSS para criação de UI responsiva e estilosa.


### Como Usar
### Criar um Novo Cliente
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_30_PM](https://github.com/user-attachments/assets/905f2e9b-b1e1-4678-b666-0315ca833a99)

### Vá até a página de clientes.
### Clique em "Novo Cliente".
### Preencha os campos necessários como nome, email, telefone e endereço.
### O cliente será salvo no banco de dados e listado na página de clientes.
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_28_PM](https://github.com/user-attachments/assets/36aa330a-e4df-449b-a41a-9db6d1135b34)

### Abrir um Novo Chamado
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_30_PM](https://github.com/user-attachments/assets/fd87f52a-a75b-4262-93cc-20098e0e1aee)![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_29_PM](https://github.com/user-attachments/assets/66e62471-8381-447b-a5f3-54391ec1eebd)


### Abrir um Chamado sem Login
### Usuários não autenticados podem abrir um chamado por meio de um link público.

### O administrador do sistema pode gerar um link específico para abertura de chamados.
### O usuário acessa o link público.
### Preenche os dados necessários, como descrição do problema e informações de contato.
### O chamado é registrado no sistema com status "Aberto".
![Uploading Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_29_PM.png…]()


### Acesse o dashboard.
### Clique em "Abrir Chamado".
### Associe o chamado a um cliente e defina o status como "Aberto".
### O chamado será registrado é listado na interface.
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_26_PM](https://github.com/user-attachments/assets/3cbd7965-5bcd-4197-a4c6-d8996b7580aa)
![Dev-Controle-seu-sistema-de-gerenciamento--11-27-2024_09_27_PM](https://github.com/user-attachments/assets/31d3c85a-23cf-4db1-85f5-37bd33cffe9a)

