# heranca-hibernate

Esse projeto tem o objetivo de demostra a herança do hibernate utilizando tilizando uma Super Classe @MappedSuperclass

O projeto cria duas tabelas Aluno e Projessor onde ambas são estendidas da super classe Pessoa, quando e realizado uma select all em Pessoa e recuperado a informação de ambas as classes.

O projeto foi criado com Srping 3, java 17 e OpenApi 2.5.0

Para acessar os serviços via Swagger
URL: http://localhost:8080/swagger-ui/index.html