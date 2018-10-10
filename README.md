# Blog

Projeto de um blog simples com a permissão para comentários por post.

Neste projeto foi utilizado ruby 2.5.1, rails 5.2.1.

Para testar a aplicação:

1) git clone https://github.com/wleandrooliveira/Blog.git

2) cd Blog

3) Blog\bundle install

4) O projeto usar o como gerenciador de banco de dados o PostgreSQL, portando será necessário, instalar o PostgreSQL, caso não esteja instalado.

5) Configure o usuário e senha do arquivo database.yml para o usuário do postgres da máquina.

6) Após a configuração do usuário e senha do postgres, execute os seguintes comandos abaixo:

7) rails db:create
 
8) rails db:migrate

9) Para executar a aplicação execute o comando rails server. Após isso acesso http://localhost:3000.


