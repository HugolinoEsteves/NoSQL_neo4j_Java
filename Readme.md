
# Controle de gastos

O projeto se baseia em controlar os gastos que uma pessoa 
tem, afim de facilitar a distribuição por criteiro de 
prioridades o uso do dinheiro e economizar para
certas eventualidades.

###  Prioridades

- Alimentação
- Aluguel
- Contas
- Lazer

### Instalaçao da imagem

Atraves de um docker pull realize o download da imagem

```bash
   docker pull neo4j/neo4j-experimental
```
Depois do download da imagem iremos iniciar com o seguinte 
comando direto no terminal

```bash
docker run \
    --publish=7474:7474 --publish=7687:7687 \
    --volume=$HOME/neo4j/data:/data \
    neo4j/neo4j-experimental
```
Acesse o neo4j com o seguinte endereço
```
http://localhost:7474.
```
Use a configuração "padrão",

- login: neo4j
- Password: neo4j
Logo em seguida insira a nova senha e estará pronto para
ser usado.

### Linguagem utilizada

Utilizada a seguinte Linguagem de programação

- JAVA

### Banco de dados utilizado

- Neo4j
  
  O Neo4j e um banco de dados nao relacional que usando o "modo"
  de grafos, que foca nos relacionamentos dos 
  registros, ajudando a obter informações complexas muito 
  rapidamente
