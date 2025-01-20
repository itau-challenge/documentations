# documentations
Project documentations

# draft:
* Este projeto possui dois domínios:
  * corretor: sistema de informação das corretoras associadas:
  * seguradora: sistema de informação da seguradora;

* Toda a configuração de disponibilidade, resiliencia e autorização, sao feitas nas OPS, e os certificados de acesso criados nas lambdas da aws;
* Foi utilizado o kafka para a comunicação assincrona
* Foi utilizada a arquitetura em camadas
* Foi utilizado o Quarkus 3 com java 17 na implementação;
* Foi utilizado NativeQuery para persistencia com banco de dados;
* Foi utilizado o Postgres como banco de dados relacional;
* Foi utilizado o Junit e mockito para os testes integrados e unitários;
* Foi utilizado o Jacoco para medição da cobertura do codigo;
* Foi utilizado o Sonnar para medição da qualidade do código;
* Foi utilizado o opentelemetry para medição de volumetria, performance e disponibilidade;
* Foi utilizado o grafana, para disponibilizar os relatórios estatísticos do sistema;

