# Desafio 03 do Bootcamp GoStack:

# Criando um aplicação utilizando Express.

# Nessa aplicação configurei as seguintes ferramentas:

Sucrase + Nodemon;
ESLint + Prettier + EditorConfig;
Sequelize utilizando PostgresSQL;

# Aplicação:

Criando o back-end da aplicação chamado Meetapp (um acrônimo à Meetup + App).

# Autenticação:

Permite que um usuário se autentique em sua aplicação utilizando e-mail e senha.

A autenticação é feita utilizando JWT.

# Cadastro e atualização de usuários:

Permite que novos usuários se cadastrem em sua aplicação utilizando nome, e-mail e senha.

Para atualizar a senha, o usuário deve também enviar um campo de confirmação com a mesma senha.

Criptografei a senha do usuário para a segurança.

# Gerenciamento de arquivos:

Criei uma rota para upload de arquivos que cadastra em uma tabela o caminho e nome do arquivo e retorna todos dados do arquivo cadastrado.

# Gerenciamento de meetups:

O usuário pode cadastrar meetups na plataforma com título do meetup, descrição, localização, data e hora e imagem (banner). Todos campos são obrigatórios. Adicionei também um campo user_id que armazena o ID do usuário que organiza o evento.

Não deve ser possível cadastrar meetups com datas que já passaram.

O usuário também pode editar todos dados de meetups que ainda não aconteceram e que ele é organizador.

Criei uma rota para listar os meetups que são organizados pelo usuário logado.

O usuário pode cancelar meetups organizados por ele e que ainda não aconteceram. O cancelamento deve deletar o meetup da base de dados.

# Inscrição no meetup:

O usuário pode se inscrever em meetups que não organiza.

O usuário não pode se inscrever em meetups que já aconteceram.

O usuário não pode se inscrever no mesmo meetup duas vezes.

O usuário não pode se inscrever em dois meetups que acontecem no mesmo horário.

Sempre que um usuário se inscrever no meetup, vai ser enviado um e-mail ao organizador contendo os dados relacionados ao usuário inscrito.

# Listagem de meetups:

Criei uma rota para listar os meetups com filtro por data (não por hora).

# Listagem de inscrições:

Criei uma rota para listar os meetups em que o usuário logado está inscrito.

Listei apenas meetups que ainda não passaram e ordene meetups mais próximos como primeiros da lista.
