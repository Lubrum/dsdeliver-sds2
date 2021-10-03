# Projeto Mobile

Este é o código do aplicativo gerado para os entregadores das encomendas. 

Tecnologias utilizadas:

- React-Native;

# Criando o projeto do zero com o `Expo`:

```bash
expo init front-mobile -t expo-template-blank-typescript --npm
```

Após a instalação, remover a pasta `.git` de `front-mobile`.

```bash
rm -rf .git
```

# Pré-requisitos

## Instalação das seguintes ferramentas no Linux (Ubuntu/Debian)

- expo-cli
- @react-navigation/stack
- @react-native-community/masked-view
- react-native-screens
- react-native-gesture-handler
- @react-navigation/native
- expo-app-loading
- @expo-google-fonts/open-sans
- expo-font
- dayjs
- intl

# Instalação (com expo e npm)

## O expo-cli e dependências do expo

```bash 
npm install --global expo-cli
expo install expo-app-loading @expo-google-fonts/open-sans expo-font
```

## Dependências do React

```bash 
expo install @react-navigation/stack @react-native-community masked-view  react-native-screens  react-native-gesture-handler  @react-navigation/native 
```

## Dependências adicionais

```bash 
npm install dayjs --save
npm install intl
```

# Execução

```bash
npm start
```

Para utilizar o Expo Go no Android, [seguir este tutorial](https://docs.expo.dev/get-started/create-a-new-app/).
