# 📝 Projeto: Bloco de Notas Falso (Exercício 4)

Projeto desenvolvido como parte de um exercício prático da faculdade.  
O objetivo é simular um bloco de notas com funcionalidades básicas de inserção e busca de texto usando Java e Swing.

---

## 📌 Funcionalidades

- **Área de texto editável** onde o usuário pode escrever livremente.
- **Campo de entrada** e botão **Adicionar**, que insere uma nova linha na área de texto.
- **Atalho de teclado Ctrl+F** para abrir a janela de busca.
- **Janela de busca (Procura)** com:
  - Campo com **ComboBox editável**.
  - Registro automático das buscas realizadas.
  - Busca de texto na área principal com **destaque em azul**.

---

## 🧠 Tecnologias Utilizadas

- Java
- Swing (`JFrame`, `JTextArea`, `JComboBox`, `JButton`, `JPanel`, `FlowLayout`, `BorderLayout`)
- Event Listeners (`ActionListener`, `KeyBindings`)

---

## 🚀 Como Executar

1. Compile os arquivos:
   ```bash
   javac Main.java Frame.java Procura.java
   ```

2. Execute o programa:
   ```bash
   java Main
   ```

---

## 🎯 Atalhos Importantes

| Ação                | Tecla        |
|---------------------|--------------|
| Adicionar linha     | Botão "Adicionar" |
| Buscar texto        | `Ctrl + F`   |

---

## 🖼️ Interface

| Janela Principal                | Janela de Busca (Ctrl + F)         |
|--------------------------------|------------------------------------|
| ![Main](./Captura%20de%20tela%20de%202025-03-30%2003-27-01.png) | ![Busca](./Captura%20de%20tela%20de%202025-03-30%2003-27-04.png) |

---

## 🤓 Sobre o Exercício

O exercício consistia em aplicar:
- Organização de layout com `JPanel` e diferentes `LayoutManager`s.
- Criação de janelas independentes (`JFrame`) com interação entre elas.
- Captura de ações do teclado com `Key Bindings`.

---

## 👨‍💻 Autor

> Desenvolvido por Mateus — estudante de Ciência da Computação.

