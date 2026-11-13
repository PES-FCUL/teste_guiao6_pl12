# Branch de avaliação `fc65621`

Este branch é só teu. Contém um pequeno projeto Java 17 / Maven (`app-215`).

## O que tens de fazer

O `pom.xml` declara 5 dependências. **Pelo menos duas delas estão desatualizadas.**

1. **Descobre quais** usando o maven.
2. **Atualiza à mão** a versão de pelo menos duas dependências no `pom.xml`
   (para a versão mais recente indicada). Não alteres as outras dependências.
3. **Gera o jar**. O ficheiro fica em **`target/app-215-1.0.jar`**.
   Confirma que funciona: `java -jar target/app-215-1.0.jar`
4. **Faz commit** do `pom.xml` e do jar.
5. **Faz push** do teu branch: `git push origin fc65621`
6. **Abre um PR** para o repositório original, com base no branch `fc65621`.

Não alteres nada dentro de `src/`.

## Comandos do guião

Referência rápida dos comandos Maven vistos no Guião 6.

| Comando |
|---|
| `mvn archetype:generate -DgroupId=pt.ul.fc -DartifactId=guiao6 -Dversion=1.0 -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false` |
| `mvn clean` |
| `mvn compile` |
| `mvn test` |
| `mvn package` |
| `mvn install` |
| `mvn deploy` |
| `mvn dependency:tree` |
| `mvn versions:display-dependency-updates` |

Comandos de Git para a entrega:

| Comando |
|---|
| `git fetch origin` |
| `git checkout fc65621` |
| `git status` |
| `git add -A` |
| `git commit -m "mensagem"` |
| `git push origin fc65621` |
| `git reset --soft HEAD~1` |
