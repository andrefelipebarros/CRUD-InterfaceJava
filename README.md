
# CRUD-InterfaceJava

Aplicação **CRUD** desenvolvida em **Java Swing** que permite gerenciar usuários com os seguintes dados:

* Nome
* CPF
* Tipo de Cartão
* Saldo
* Status (Ativo/Inativo)

## 🖼️ Interface

A interface gráfica possui:

* Formulário para preenchimento dos campos.
* Tabela dinâmica exibindo todos os registros.
* Botões de **Adicionar**, **Atualizar** e **Deletar**.

## ⚙️ Funcionalidades

* **Adicionar**: insere um novo registro na tabela.
* **Atualizar**: altera os dados do registro selecionado.
* **Deletar**: remove o registro selecionado.
* **Seleção automática**: ao clicar em uma linha da tabela, os dados são carregados nos campos para edição.

## 🚀 Tecnologias

* **Java SE 8+**
* **Swing (javax.swing)** para construção da interface gráfica.

## 📦 Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/andrefelipebarros/CRUD-InterfaceJava.git
   ```
2. Abra o projeto em uma IDE (NetBeans, IntelliJ, Eclipse).
3. Compile e execute a classe principal:

   ```
   andrefelipebarros.trabalho_falvio.Interface
   ```
4. A interface gráfica será exibida.

## 📂 Estrutura do Projeto

```
src/
└── andrefelipebarros/trabalho_falvio/
    ├── Interface.java     # Classe principal com toda a lógica do CRUD
    ├── adicionar.png      # Ícone do botão Adicionar
    ├── pen-circle.png     # Ícone do botão Atualizar
    └── circle-trash.png   # Ícone do botão Deletar
```

## 👨‍💻 Autor

Projeto desenvolvido por **André Felipe Barros**.
