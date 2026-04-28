# O Caso Jeffrey Epstein: Mistérios e Investigações

Este projeto é uma página web informativa e responsiva que detalha as investigações e os impactos do escândalo Jeffrey Epstein. O site foi reestruturado para demonstrar a aplicação prática do framework **Bootstrap 5**, focando em produtividade e design responsivo.

---

## Tecnologias Utilizadas

Abaixo estão as ferramentas e bibliotecas aplicadas no desenvolvimento desta versão:

| Ferramenta | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura semântica e acessível. |
| **Bootstrap 5.3** | Framework CSS para componentes e sistema de grid. |
| **CDN (Content Delivery Network)** | Método de importação das dependências do Bootstrap. |
| **Markdown** | Documentação técnica do repositório. |

---

## Principais Classes Bootstrap Aplicadas

Nesta versão, substituímos o CSS manual por classes utilitárias do Bootstrap:

* `container`: Centralização e limitação da largura máxima.
* `row` & `col-md-X`: Sistema de grid para colocar textos ao lado de imagens.
* `card`: Utilizado na seção de curiosidades para criar um box destacado.
* `btn-dark`: Estilização moderna para o botão de envio do formulário.
* `img-fluid`: Garantia de que as fotos nunca ultrapassem a largura da tela.
* `nav-pills`: Estilo de "pílulas" para os links de navegação.

---

## Estrutura de Pastas

```text
/
├── assets/              # Imagens (imagem_principal.png, jeff_preso.png, ilha.jpg)
├── index.html           # Código principal com Bootstrap 5
├── script.js            # Lógica de recebimento dos dados do formulário
└── README.md            # Documentação do projeto