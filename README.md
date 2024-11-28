# Dev Controle - Sistema de Gerenciamento de Clientes e Chamados
### Dev Controle é um sistema web desenvolvido com Next.js, Prisma ORM, MongoDB e TailwindCSS para gerenciar clientes e chamados de atendimento de forma eficiente e fácil.
![image](https://github.com/user-attachments/assets/926978f8-11f3-4e14-8d14-5a13c0918e44)


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
### Vá até a página de clientes.
### Clique em "Novo Cliente".
### Preencha os campos necessários como nome, email, telefone e endereço.
![image](https://github.com/user-attachments/assets/90617f09-9ded-42b3-85fc-1fd1f1497e3c)


### O cliente será salvo no banco de dados e listado na página de clientes.
![image](https://github.com/user-attachments/assets/acd900e8-47d7-4f23-a4c9-c1924347be12)


### Abrir um Novo Chamado
![image](https://github.com/user-attachments/assets/d11daee1-2c7e-4f02-b0e5-07a90102dffa)


### Abrir um Chamado sem Login
### Usuários não autenticados podem abrir um chamado por meio de um link público.

### O administrador do sistema pode gerar um link específico para abertura de chamados.
### O usuário acessa o link público.
### Preenche os dados necessários, como descrição do problema e informações de contato.
### O chamado é registrado no sistema com status "Aberto".
![image](https://github.com/user-attachments/assets/243a42cb-6779-4d75-8dc0-c2bbb308c08b)



### Acesse o dashboard.
### Clique em "Abrir Chamado".
### Associe o chamado a um cliente e defina o status como "Aberto".
### O chamado será registrado é listado na interface.
![image](https://github.com/user-attachments/assets/8260c3a8-948a-4d18-b659-4e7bcf8521c8)
![image](https://github.com/user-attachments/assets/556e6d40-cc13-407a-b7fa-b820b4d3eb9e)


