# 📱 Calculadora React Native

Aplicação de calculadora matemática desenvolvida com React Native, compatível com Android e iOS. Implementa operações básicas (adição, subtração, multiplicação e divisão) com interface intuitiva e responsiva.

![React Native](https://img.shields.io/badge/React_Native-0.70.1-61DAFB?logo=react&logoColor=white)
![React](https://img.shields.io/badge/React-18.1.0-61DAFB?logo=react&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-lightgrey)

## 🚀 Tecnologias Utilizadas

- **React Native** - Framework para desenvolvimento mobile nativo
- **React** - Biblioteca JavaScript para interfaces
- **JavaScript** - Linguagem de programação
- **Class Components** - Componentes com estado
- **React Hooks** - Gerenciamento de estado (state)
- **StyleSheet API** - Estilização nativa
- **Dimensions API** - Layout responsivo

## ✨ Funcionalidades

- ✅ Operações matemáticas básicas (+, -, ×, ÷)
- ✅ Entrada de números decimais
- ✅ Botão AC (All Clear) para limpar memória
- ✅ Display responsivo com overflow controlado
- ✅ Layout adaptável para diferentes tamanhos de tela
- ✅ Botões com feedback visual (TouchableHighlight)
- ✅ Validação de entrada de ponto decimal
- ✅ Tratamento de erros em operações

## 🎯 O que Aprendi

Durante o desenvolvimento desta calculadora, pratiquei e aprofundei:

- **React Native Core**: Componentes nativos (SafeAreaView, View, Text, TouchableHighlight)
- **Class Components**: Gerenciamento de estado com `this.state` e `setState`
- **Componentização**: Separação em componentes reutilizáveis (Button, Display)
- **Layout Responsivo**: Uso da API Dimensions para adaptar UI a diferentes telas
- **Event Handling**: Manipulação de eventos de toque e callbacks
- **State Management**: Controle de estado complexo com múltiplos valores
- **StyleSheet**: Estilização performática e organizada
- **Lógica de Calculadora**: Implementação de operações matemáticas encadeadas

## 📦 Estrutura do Projeto

```
Calculadora-ReactNative/
├── android/          # Configuração Android
├── ios/              # Configuração iOS
├── src/
│   └── components/
│       ├── Button.js    # Componente de botão
│       └── Display.js   # Componente de display
├── App.js            # Componente principal
├── index.js          # Entry point
└── package.json      # Dependências
```

## 🛠️ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **Node.js** (v14 ou superior)
- **npm** ou **yarn**
- **React Native CLI**
- **Xcode** (para iOS - apenas macOS)
- **Android Studio** (para Android)
- **JDK 11** ou superior

## 🚀 Como Executar

### 1. Clone o repositório
```bash
git clone https://github.com/charlesbatista/Calculadora-ReactNative.git
cd Calculadora-ReactNative
```

### 2. Instale as dependências
```bash
npm install
# ou
yarn install
```

### 3. Execute no Android
```bash
npm run android
# ou
yarn android
```

### 4. Execute no iOS (apenas macOS)
```bash
cd ios && pod install && cd ..
npm run ios
# ou
yarn ios
```

### 5. Inicie o Metro Bundler (caso necessário)
```bash
npm start
# ou
yarn start
```

## 📱 Scripts Disponíveis

- `npm run android` - Executa o app no Android
- `npm run ios` - Executa o app no iOS
- `npm start` - Inicia o Metro Bundler
- `npm test` - Executa os testes
- `npm run lint` - Verifica o código com ESLint

## 🎨 Design

A interface segue um design clean e funcional:
- Display com fundo escuro para melhor legibilidade
- Botões operacionais destacados em laranja (#fa8231)
- Botões numéricos em cinza claro (#f0f0f0)
- Layout responsivo que se adapta ao tamanho da tela
- Tipografia clara e de fácil leitura

## 🧪 Testado em

- ✅ Android 12+
- ✅ iOS 14+

## 📝 Licença

Este projeto foi desenvolvido para fins de aprendizado e portfólio.

---

Desenvolvido por [Charles Batista](https://github.com/charlesbatista)
