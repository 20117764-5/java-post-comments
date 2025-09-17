# Java Post Comments

Mini-sistema de postagens com comentários desenvolvido em Java, focado em **Programação Orientada a Objetos (POO)**. Este projeto demonstra a criação de classes, composição de objetos e manipulação de listas.

---

## Funcionalidades

- Criação de posts com:
  - Título
  - Conteúdo
  - Data/Hora
  - Quantidade de likes
- Adição de comentários em cada post
- Impressão formatada dos posts e comentários usando **`StringBuilder`**

---

## Tecnologias e Conceitos

- Java (JDK 8+)
- Programação Orientada a Objetos (POO)
  - Classes e objetos
  - Construtores
  - Getters e Setters
  - Composição de classes (`Post` contém `Comment`)
- Listas (`ArrayList`) para armazenar comentários
- Formatação de datas (`SimpleDateFormat`)
- **`StringBuilder`** para gerar saída formatada de forma eficiente

---

## Estrutura do Projeto
```
java-post-comments/
├── src/
│ ├── application/
│ │ └── Program.java
│ └── entities/
│ ├── Post.java
│ └── Comment.java
└── README.md
```
---

## Exemplo de Saída

Traveling to New Zealand
12 Likes - 21/06/2018 13:05:44
I'm going to visit this wonderful country!
Comments:
Have a nice trip!
Wow that's awesome!

Good night guys
5 Likes - 28/07/2018 23:14:19
See you tomorrow
Comments:
Good night
May the Force be with you

---

## Objetivo do Projeto

Este projeto foi desenvolvido com objetivo educacional, para praticar:

Composição de classes

Manipulação de listas

Formatação de saída em console usando StringBuilder

Boas práticas de POO em Java

Destaques
Demonstra entendimento de associação entre objetos (Post e Comment).

Uso de listas para armazenar e manipular comentários dinamicamente.

StringBuilder utilizado para gerar saída formatada de forma eficiente e legível.

Código limpo e organizado, pronto para servir como exemplo de estudo ou portfólio.

---

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/java-post-comments.git
```
2. Navegue até a pasta src e compile os arquivos Java:
```
javac application/Program.java entities/*.java
```
3. Execute o programa:
```
java application.Program
```


