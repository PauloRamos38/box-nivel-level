# Modelo de caixas: box-level e inline-level

Exercício simples desenvolvido durante os estudos de **HTML5 e CSS3** no
[Curso em Vídeo](https://www.cursoemvideo.com/), com o Professor Guanabara.

## Sobre o exercício

O objetivo é visualizar como o navegador organiza os elementos em caixas e
entender a diferença entre:

- **Box-level:** ocupa, por padrão, toda a largura disponível e inicia em uma
  nova linha. Exemplos: `h1`, `h2`, `p` e `section`.
- **Inline-level:** ocupa apenas o espaço necessário e permanece na mesma
  linha do conteúdo. O elemento `a` é um exemplo comum.

Também são apresentados os principais componentes do modelo de caixas:

```text
margin -> border -> padding -> content
```

## Conteúdos praticados

- Estrutura semântica com `header`, `main`, `section` e `footer`;
- Configuração de idioma, título e descrição da página;
- Cores, bordas, espaçamento interno e externo;
- Uso de `box-sizing: border-box`;
- Links externos com `target="_blank"` e `rel="noopener noreferrer"`;
- Diferença visual entre elementos de bloco e elementos em linha.

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador.

Também é possível usar uma extensão como **Live Server** no VS Code para
acompanhar as alterações automaticamente.

## Estrutura

```text
.
├── index.html
├── README.md
├── .gitignore
├── .env.example
└── favicon.svg
```

## Configuração e segurança

Este é um projeto estático e não precisa de variáveis de ambiente para
funcionar. O arquivo `.env` está no `.gitignore` para evitar o envio acidental
de configurações locais ou segredos. O arquivo `.env.example` serve apenas
como modelo caso o projeto passe a precisar de configurações no futuro.

## Referência

- [Curso em Vídeo](https://www.cursoemvideo.com/)
- [MDN: CSS box model](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Styling_basics/Box_model)
