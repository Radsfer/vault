202406071815
Status: #study 
Tags:
[[Java]], [[bootCampSantander]], [[Coding]]
# Java Maven 2 - POM (Project Object Model)

## POM
> O POM consegue passar todas as informações necessárias para o projeto como bibliotecas, etc. Para que o Maven o crie. Sendo o formato `xml`.

![[Pasted image 20240607181846.png]]

Como pode ser visto na imagem, o mínimo de informação necessário que o `Maven` pede ao `Pom.xml ` é a sua versão do modelo com `<modelVersion>` seu ID do grupo/ dos pacotes com `<groupId>` o `<artifactId>` que é o nome do projeto e por fim a versão do projeto com o `<version>`.

## Super POM

- O Maven trabalha com sistema de heranças onde isso afeta o `Pom.xml`, o estendendo para o `Super POM`.
- O `SUPER POM` nada mais é que um modelo base que serve para passar o resto das informações necessárias para o `Maven`. Ao passar as sua informações pelo `Pom.xml` esta sendo sobrescrito `(@Override)` o que está presente no `SUPER POM`

## Repositórios

![[Pasted image 20240607183435.png]]

## Adicionando dependências



___
# References
- [Super POM Maven](https://maven.apache.org/ref/3.0.4/maven-model-builder/super-pom.html)
