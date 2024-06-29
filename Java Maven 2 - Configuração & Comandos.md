202406041733
Status: #study 
Tags:
[[Java]], [[Coding]], [[bootCampSantander]]
# Java Maven 2 - Configuração & Comandos
```bash
mvn archetype:generate -DgroupId=one.digitalinovation -DartifactId=quick-start-maven -Darchetype=maven-archetype-quickstart -DinteractiveMode=false
```
>`mvn`: Comando

>`archetype:generate`: gerador de arquétipo 

>`-DgroupID`: D para definir e group ID é o nome do grupo

>`-DartifactID`: D para definir o nome do projeto

>`-Darchetype`: D para definir o arquétipo Quick Start pro maven

>`-DinteractiveMode`: Maven executa em modo não interativo. Isso significa que ele não pedirá nenhuma entrada ao usuário durante a execução e usará valores padrão ou falhará se não tiver todas as informações necessárias. Isso é útil para automatizar tarefas de build em ambientes de integração contínua (CI), onde a intervenção do usuário não é possível.

## Comandos no dia-a-dia

- `mvn compile`: Para compilar o código com maven 
- `mvn test`: Para realizar os teste do código necessário
- `mvn package`: Para empacotar o projeto em um arquivo do tipo **.jar**
- `mvn clean`: Limpar o ambiente de trabalho, no caso apagando a pasta **target**
## Criando diferentes tipos de projeto com Maven archetype

> Podendo ser tanto pesquisado pelo próprio site do maven, ou por clones de github, tem como se utilizar arquétipos para criação de tipos de projetos específicos no maven. Como Web App, Desktop App etc.
```bash
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.4
```



___
# References
- [Maven](https://maven.apache.org/)
- [MVN Repository](https://mvnrepository.com/)
