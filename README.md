# 🚀 FIAP - Mobile Development CP3

Repositório contendo os projetos desenvolvidos durante as aulas de Mobile Development utilizando React Native + Expo.

---

# Aluno

- Nome: Estevam Melo Acosta
- RM: 555124
- Turma: 3ESPG
- Disciplina: Mobile Development
- Instituição: FIAP

---

# Estrutura do Repositório

```bash
fiap-mdi-cp3/
├── aula03-cartao-visita/
├── aula04-contador-hidratacao/
├── aula05-meu-perfil/
├── aula06-memolist/
├── aula07-mini-loja/
├── aula09-cadastro-completo/
└── README.md
```

---

# Projetos Desenvolvidos

## Aula 03 — Cartão de Visita

Aplicação simples exibindo informações pessoais e estilização básica utilizando React Native.

### Demonstração

![Cartão de Visita](./aula03-cartao-visita/meu-perfil/assets/image.png)

### Funcionalidades
- Exibição de nome
- Exibição de profissão
- Layout estilizado
- Componentes básicos

### Tecnologias
- React Native
- Expo
- StyleSheet

---

## Aula 04 — Contador de Hidratação

Aplicativo para controle de consumo diário de água.

### Demonstração

![Contador Inicial](./aula04-contador-hidratacao/assets/images/hidratar1.png)
![Contando os Copos](./aula04-contador-hidratacao/assets/images/hidratar2.png)
![Meta Atingida](./aula04-contador-hidratacao/assets/images/hidratar3.png)

### Funcionalidades
- Incrementar contador
- Resetar consumo
- Atualização em tempo real

### Tecnologias
- React Native
- useState
- TouchableOpacity

---

## Aula 05 — Meu Perfil

Mini app com navegação entre telas utilizando Expo Router.

### Demonstração

![Página 1](./aula05-meu-perfil/app-router/assets/perfil1.png)
![Página 2](./aula05-meu-perfil/app-router/assets/perfil2.png)

### Funcionalidades
- Tela Home
- Tela Perfil
- Navegação entre páginas
- Estilização inspirada nas cores da FIAP

### Tecnologias
- Expo Router
- React Native
- Flexbox

---

## Aula 06 — MemoList

Aplicativo de lista de tarefas com persistência local.

### Demonstração

![Padrão](./aula06-memolist/MemoList/assets/images/memolist1.png)
![Funcionaliades](./aula06-memolist/MemoList/assets/images/memolist2.png)
![Removendo Itens](./aula06-memolist/MemoList/assets/images/memolist3.png)

### Funcionalidades
- Adicionar tarefas
- Remover tarefas
- Marcar tarefas como concluídas
- Persistência com AsyncStorage
- Contador de tarefas pendentes
- Limpeza total da lista

### Tecnologias
- AsyncStorage
- FlatList
- Switch
- useEffect
- React Native

---

## Aula 07 — Mini Loja

Mini sistema de loja virtual com carrinho de compras.

### Demonstração

![Loja](./aula07-mini-loja/mini-loja/assets/loja1.png)
![Produtos](./aula07-mini-loja/mini-loja/assets/loja2.png)
![Carrinho](./aula07-mini-loja/mini-loja/assets/loja3.png)
![Comprando](./aula07-mini-loja/mini-loja/assets/loja4.png)

### Funcionalidades
- Listagem de produtos
- Carrinho de compras
- Adicionar produtos
- Remover produtos
- Soma total dos valores
- Context API para gerenciamento global de estado

### Tecnologias
- Context API
- useContext
- FlatList
- React Native

---

## Aula 09 — Cadastro Completo

Formulário completo com validações e interface moderna.

### Demonstração

![Tela Padrão](./aula09-cadastro-completo/cadastro-app/assets/images/cadastro1.png)
![Registrando](./aula09-cadastro-completo/cadastro-app/assets/images/cadastro2.png)
![Erro no registro](./aula09-cadastro-completo/cadastro-app/assets/images/cadastro3.png)

### Funcionalidades
- Campo de nome
- Campo de e-mail
- Campo de CPF com máscara
- Campo de telefone com máscara
- Campo de senha
- Validação de e-mail com Regex
- Validação em tempo real
- Seleção de perfil
- Aceite de termos
- Feedback visual de erros
- Botão dinâmico
- KeyboardAvoidingView

### Tecnologias
- React Native
- useRef
- Regex
- ScrollView
- KeyboardAvoidingView

---

# Identidade Visual

Os projetos foram estilizados utilizando como referência a identidade visual da FIAP:

- Preto
- Cinza escuro
- Branco
- Magenta

---

# Pré-requisitos

Antes de executar os projetos, instale:

- Node.js
- VS Code
- Expo CLI

---

# Instalação do suporte Web

Execute o comando abaixo em cada projeto para habilitar a visualização no navegador:

```bash
npx expo install react-dom react-native-web @expo/metro-runtime
```

---

# Como Executar os Projetos

## ula 03 — Cartão de Visita

```bash
cd aula03-cartao-visita
cd meu-perfil
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

## Aula 04 — Contador de Hidratação

```bash
cd aula04-contador-hidratacao
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

## Aula 05 — Meu Perfil

```bash
cd aula05-meu-perfil
cd app-router
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

## Aula 06 — MemoList

```bash
cd aula06-memolist
cd MemoList
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

## Aula 07 — Mini Loja

```bash
cd aula07-mini-loja
cd mini-loja
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

## Aula 09 — Cadastro Completo

```bash
cd aula09-cadastro-completo
cd cadastro-app
npm install
npx expo start
```

Pressione:

```bash
w
```

para abrir no navegador.

---

# Tecnologias Utilizadas

- React Native
- Expo
- JavaScript
- AsyncStorage
- Expo Router
- Context API
- Flexbox
- FlatList
- Switch
- Hooks
- Regex

---

# Conceitos Aplicados

Durante o desenvolvimento dos projetos foram praticados:

- Componentização
- Navegação entre telas
- Gerenciamento de estado
- Persistência local
- Context API
- Máscaras de formulário
- Validação de dados
- Estilização avançada
- Responsividade
- Manipulação de listas

---

# Observações

Todos os projetos foram desenvolvidos para fins acadêmicos durante a CP3 da disciplina de Mobile Development da FIAP.

---