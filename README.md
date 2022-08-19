![GitHub commit activity](https://img.shields.io/github/commit-activity/y/Lubrum/dsdeliver-sds2) ![GitHub last commit](https://img.shields.io/github/last-commit/Lubrum/dsdeliver-sds2) ![GitHub repo size](https://img.shields.io/github/repo-size/Lubrum/dsdeliver-sds2)

# Semana Dev Superior 2.0 - DSDelivery

Este é um projeto concebido na semana Dev Superior 2.0, em que o objetivo era desenvolver um sistema para realização de pedidos e entregas de encomendas de um restaurante. 

Adicionalmente, também foi desenvolvido um app para os entregadores das encomendas. 

Tecnologias utilizadas:

- [Backend: Java, Spring Boot](https://github.com/Lubrum/dsdeliver-sds-backend)

- [Frontend: ReactJS](https://github.com/Lubrum/dsdeliver-sds2/tree/main/front-web)

- [Mobile: React-Native](https://github.com/Lubrum/dsdeliver-sds2/tree/main/front-mobile)

# Pré-requisitos

## Instalação das ferramentas no Linux (Ubuntu/Debian)

## Ferramentas:

- Curl
- Git
- Java JDK 17
- Maven
- STS
- Postman
- Postgresql e pgAdmin
- Heroku CLI
- Node & NPM
- VS Code

## Curl

- Instalar o curl
```
sudo apt-get install -y curl
```
- Conferir a instalação: 
```
curl
```

## Git

- Instalar: 
```
sudo apt-get install -y git
```

- Conferir a instalação: 
```
git
```

## Java JDK 11

- Instalar Java: 
```
sudo apt install openjdk-17-jdk
```

- Verificar a instalação: 
```
java -version
```
- Configurar JAVA_HOME:
  - Verificar caminho Java: 
  ```
  sudo update-alternatives --config java
  ```
  - Copie o caminho do Java
  - Edite o arquivo .bashrc: 
  ```
  sudo gedit ~/.bashrc
  ```
  - Copie o código abaixo no final do arquivo. Salve o arquivo.
  - Abra um novo terminal e teste: 
  ```
  echo $JAVA_HOME
  ```

```
JAVA_HOME=/usr/...
export JAVA_HOME
export PATH=$PATH:$JAVA_HOME
```

## Maven

- Instalar Maven: 
```
sudo apt-get install maven
```
- Verificar a instalação: 
```
mvn -v
```

## STS

- Google: STS
- Baixar
- Descompactar (exemplo: /home/user/apps)
- Iniciar STS
  - Selecione um workspace (exemplo: /home/user/Workspaces/ws-sts)
- Liberar permissão na pasta do workspace: 
```
sudo chmod -R ugo+rw /home/user/Workspaces/ws-sts
```

## Postman

- Instalar com snap: 
```
snap install postman
```

## Postgresql

```
https://www.postgresql.org/download/linux/ubuntu/
```

## pgAdmin

```
https://www.pgadmin.org/download/pgadmin-4-apt/
```

## Heroku CLI

```
https://devcenter.heroku.com/articles/heroku-cli
```

## Node & NPM

```
sudo apt update

curl -sL https://deb.nodesource.com/setup_lts.x | sudo -E bash -

sudo apt-get install nodejs
```

## YARN (Caso queira usar o YARN ao invés do NPM)
No Debian e no Ubuntu:
```
 curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
 
 echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
 
 sudo apt-get update && sudo apt-get install yarn

```

## VS Code

```
https://code.visualstudio.com/download

sudo snap install code --classic
```

