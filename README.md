# Ebook Publications

Camada de publicação dos e-books individuais produzidos pelo Montador.

## Estrutura

Cada livro publicado ocupa um diretório próprio identificado pelo seu `book_id`:

```
livros/
└── {book_id}/
    └── index.html
```

O repositório é destinado aos artefatos publicados e será conectado à Vercel para hospedagem pública.

## Regras

- Cada livro é uma unidade independente.
- O `book_id` é a identidade técnica do livro.
- O título não identifica o livro.
- Não armazenar código da Estante neste repositório.
- Não armazenar código do Montador neste repositório.
- A URL pública de cada livro será derivada do seu caminho de publicação.
