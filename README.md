# Página de Login

Esta página de login foi criada utilizando HTML e CSS, com um layout responsivo e elementos visuais atraentes. O design inclui animações sutis e uma interface amigável, com foco na usabilidade.

## Estrutura do HTML

O arquivo HTML contém a seguinte estrutura básica:

- **Cabeçalho (`<head>`)**:
  - Define o conjunto de caracteres e a configuração de viewport para responsividade.
  - Inclui links para estilos externos (CSS) e fontes do Google Fonts.
  - Referencia um arquivo JavaScript (script.js) para funcionalidades adicionais.

- **Corpo (`<body>`)**:
  - Um `<div>` principal que contém duas seções: uma para mensagens de boas-vindas e outra para o formulário de login.
  - A seção da esquerda contém um título e uma imagem de uma carteira.
  - A seção da direita inclui um formulário com campos para usuário e senha.

## Estilo CSS

O arquivo CSS proporciona um design moderno e responsivo:

- **Estilos Globais**:
  - Reseta margens e preenchimentos, e define o box-sizing para facilitar o controle do layout.

- **Estilos do Corpo**:
  - Define uma fonte e um fundo com gradiente escuro, centralizando o conteúdo vertical e horizontalmente.

- **Estilos da Seção de Login**:
  - A seção de login é dividida em duas partes (esquerda e direita) com igual largura.
  - O título é estilizado com um tamanho de fonte responsivo e cor branca.
  - A imagem da carteira é responsiva, ajustando-se ao tamanho da tela.

- **Estilos do Formulário**:
  - O formulário tem um fundo escuro com bordas arredondadas e sombras para criar um efeito de profundidade.
  - Os campos de entrada têm transições suaves ao focar, mudando de cor e exibindo sombras.
  - O botão de login tem um design chamativo, mudando de cor ao passar o mouse e uma animação ao ser clicado.

## Funcionalidades JavaScript

- Validar entradas de usuário antes de enviar o formulário.
- Exibir mensagens de erro ou sucesso após tentativas de login.

## Responsividade

O design é responsivo, adaptando-se a diferentes tamanhos de tela:

- Para telas menores que 950px, o cartão de login se expande.
- Para telas menores que 600px, a seção esquerda (com a imagem) é oculta e o layout se reorganiza para uma única coluna.

## Considerações Finais
