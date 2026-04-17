# Publicacao do Site

Este projeto e um site estatico. A entrada publica deve ser o arquivo `index.html`.

## Opcao 1: Netlify

Mais rapida para publicar sem preparar repositório.

1. Abra [Netlify](https://www.netlify.com/).
2. Entre com sua conta.
3. Use a opcao de criar um site por upload manual.
4. Envie a pasta `Ensaio_Validacao` inteira.
5. Aguarde a geracao do link publico.

Resultado:
- O `index.html` vira a pagina inicial.
- Os links para `framework_metodologia.html` e `ensaio_visao_geral.html` continuam funcionando.

## Opcao 2: GitHub Pages

Melhor se voce quiser manter versao, historico e atualizacoes futuras.

1. Crie um repositório no GitHub.
2. Envie estes arquivos para a raiz do repositório.
3. No GitHub, abra `Settings > Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch principal e a pasta `/ (root)`.
6. Salve e aguarde a publicacao.

Resultado:
- O GitHub gera um link publico.
- O `index.html` sera a pagina inicial do site.

## Arquivos necessarios

Publique juntos:
- `index.html`
- `framework_metodologia.html`
- `ensaio_visao_geral.html`

## Observacoes

- O tema claro/escuro e salvo no navegador do visitante por `localStorage`.
- As paginas secundarias dependem do `index.html` para o botao de voltar.
- Nao ha backend nem banco de dados; qualquer hospedagem estatica funciona.
