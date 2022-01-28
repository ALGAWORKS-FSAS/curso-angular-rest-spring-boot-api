# curso-angular-rest-spring-boot-api

Existem várias formas de usar o Maven. Vou colocar aqui uma pequena lista de comandos úteis

- Limpeza do Projeto
./mvnw clean
- Compilação
./mvnw compile
- Execução do projeto
./mvnw spring-boot:run
- Verificação da árvore de dependências (útil para verificação de conflitos de dependências)
./mvnw dependency:tree
- Empacotamento (packaging) do projeto (geração do JAR ou WAR)
./mvnw package
- Realização de testes automatizados (os testes devem ser programados)
./mvnw verify
Existem diversos outros comandos. É possível executar comandos em sequência, por exemplo
./mvnw clean compile spring-boot:run
