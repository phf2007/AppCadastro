# App Cadastro

> Um aplicativo Android simples que cadastre o usuário.

## 📱 Descrição

O **App Cadastro** permite ao usuário cadastrar sua conta usando nome, telefone e endereço.

## 🔧 Funcionalidades

- [x] 3 Telas
- [x] App de cadastro de conta
- [x] Fácil de entender
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/AppSalario/salario.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

CadastroSys
├── app
│   ├── main
│   │   ├── java/com.example.sistemadecadastro  
│   │   │   ├── MainActivity.java                  # Atividade principal onde está o código que ativa a ArrayList
│   │   │   ├── Registro.java                      # Atividade que pega os registros e os transforma em strings
│   │   │   ├── TelaCadastroUsuario.java           # Atividade principal da tela de cadastro
│   │   │   ├── TelaListagemUsuarios.java          # Atividade principal de listar usuário
│   │   │   ├── TelaPrincipal.java                 # Atividade principal da tela principal
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   │   ├── cadastro.xml                   # Layout da tela de cadastro
│   │   │   │   ├── lista.xml                      # Layout da tela que lista os usuários
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, tem apenas dois botões, um que leva à tela de cadastro e outro para a tela de lista

**Tela Secundária** 

Na tela secundária, tem 3 caixas de texto, uma de nome, outra de telefone e outra de cpf, abaixo delas tem 2 botões que um volta e o outro salva

**Tela Terciária** 

Na tela terciária é onde fica a lista dos usuários que foram criados na tela de cadastro e abaixo um botão pra voltar

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
