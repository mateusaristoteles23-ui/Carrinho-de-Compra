# 🛒 Lista de Compras

## 📌 Sobre o projeto

O projeto **Lista de Compras** é um aplicativo desenvolvido com React Native e Expo, utilizando TypeScript, com o objetivo de facilitar a organização de produtos que precisam ser comprados.

A aplicação permite adicionar produtos à lista, informar suas quantidades, visualizar os itens cadastrados e removê-los quando necessário. A interface foi organizada em componentes para facilitar a manutenção e a compreensão do código.

## 🎯 Objetivos

* Desenvolver uma aplicação utilizando React Native.
* Praticar a criação e reutilização de componentes.
* Utilizar estados para atualizar as informações na tela.
* Trabalhar com propriedades (props) e tipagem com TypeScript.
* Implementar funcionalidades de inclusão e remoção de itens.
* Criar uma interface simples, organizada e intuitiva.

## ⚙️ Funcionalidades

* **Visualização da lista:** exibe os produtos cadastrados e suas respectivas quantidades.
* **Adição de produtos:** permite informar o nome e a quantidade de cada produto.
* **Validação do formulário:** verifica se o nome do produto foi preenchido.
* **Quantidade padrão:** utiliza a quantidade 1 quando o campo de quantidade está vazio ou contém um valor que não pode ser convertido em número.
* **Remoção de produtos:** permite excluir um item da lista por meio de um botão.
* **Lista vazia:** apresenta uma mensagem quando não há produtos cadastrados.
* **Contador de itens:** exibe no rodapé a quantidade de produtos presentes na lista.

## 🛠️ Tecnologias utilizadas

* **React Native:** desenvolvimento da interface do aplicativo.
* **Expo:** ferramenta para executar e testar a aplicação.
* **TypeScript:** tipagem de dados, propriedades e funções.
* **JavaScript:** lógica de funcionamento da aplicação.
* **Git e GitHub:** ferramentas que podem ser utilizadas para versionamento e compartilhamento do projeto.

## 📂 Estrutura do projeto

```text
lista-de-compras/
├── assets/
├── components/
│   ├── Cabeçalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── app.json
├── index.ts
├── index.tsx
├── package.json
├── tsconfig.json
└── types.ts
```

### Principais arquivos

* **App.tsx:** componente principal, responsável por gerenciar os itens e integrar o cabeçalho, o formulário, a lista e o rodapé.
* **Cabeçalho.tsx:** apresenta o título e a descrição do aplicativo.
* **FormularioItem.tsx:** contém os campos para inserir o nome e a quantidade do produto, além do botão de adicionar.
* **ItemCompra.tsx:** representa individualmente cada produto e disponibiliza o botão para removê-lo.
* **ListaCompras.tsx:** utiliza `FlatList` para exibir os produtos e mostrar uma mensagem quando a lista estiver vazia.
* **types.ts:** define a interface `ItemDeCompra`, utilizada para padronizar os dados dos produtos.
* **package.json:** contém as dependências e os comandos de execução do projeto.

## ▶️ Como executar o projeto

### Pré-requisitos

* Node.js instalado.
* npm instalado.
* Um terminal ou editor de código, como o Visual Studio Code.

### Passos para execução

Abra o terminal na pasta do projeto e execute os comandos abaixo:

```bash
# 1. Instalar as dependências
npm install

# 2. Iniciar o Expo
npm start
```

Após iniciar o Expo, utilize uma das opções disponíveis no terminal para executar a aplicação:

* **Navegador:** pressione `w`, se a opção estiver disponível.
* **Android:** pressione `a`, com o ambiente Android configurado, ou utilize o aplicativo Expo Go conforme a configuração do projeto.
* **iOS:** pressione `i`, em um ambiente compatível com o simulador iOS.

Também é possível executar diretamente pelo terminal:

```bash
# Executar na Web
npm run web

# Executar no Android
npm run android

# Executar no iOS
npm run ios
```

## 🧠 Conceitos praticados

Durante o desenvolvimento, foram trabalhados os seguintes conceitos:

* Componentização com React Native.
* Uso do hook `useState` para controlar os dados da aplicação.
* Comunicação entre componentes por meio de props.
* Criação de funções para adicionar e remover produtos.
* Manipulação de arrays com métodos como `filter`.
* Renderização de listas com `FlatList`.
* Tipagem de interfaces e funções com TypeScript.
* Estilização de componentes com `StyleSheet`.
* Validação de campos de formulário.

## 📌 Considerações finais

O projeto Lista de Compras permite aplicar conceitos fundamentais do desenvolvimento de aplicativos com React Native e TypeScript. A divisão da aplicação em componentes torna o código mais organizado, facilita a manutenção e contribui para o aprendizado de práticas de desenvolvimento de interfaces.

A aplicação mantém os itens no estado da própria execução, sem utilizar um banco de dados para armazenamento permanente.

---

**Projeto:** Lista de Compras
**Versão:** 1.0.0
**Tecnologias principais:** React Native, Expo e TypeScript
