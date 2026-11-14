Site Pessoal – Versão 2 (HTML + CSS responsivo)

Aluno: Lucas Motta Poncio
Curso: Engenharia de Software – UTFPR, Campus Dois Vizinhos

Objetivo da atividade

Transformar visualmente a página criada na etapa anterior (somente HTML), separando a estrutura/conteúdo (index.html) da apresentação (style.css). O CSS é escrito primeiro para telas pequenas (mobile-first) e adaptado para telas maiores com media queries.

Arquivos
index.html – estrutura e conteúdo da página (liga o CSS com <link rel="stylesheet">)
style.css – cores, tipografia, espaçamentos, bordas, links, formulário e layout
fotos/ftprincipal.jpg – foto usada no cabeçalho
O que foi aplicado no CSS
Arquivo CSS externo e viewport configurado no <head>
Cores e medidas em variáveis (:root), tipografia e espaçamentos em rem
Sem larguras fixas; imagem com max-width: 100%
Flexbox (navegação, etiquetas de habilidades, botões) e Grid (cabeçalho e seções)
Estilo de links, formulário e estados hover e focus
Responsividade
Largura	Layout
~375 px (mobile)	Uma coluna, menu quebrando em linhas
~768 px (tablet)	Foto ao lado do texto, título das seções na coluna da esquerda
≥ 1200 px (desktop)	Fontes e foto maiores, cursos de formação lado a lado

Testado no DevTools nessas três larguras.

Como visualizar

Mantenha index.html, style.css e a pasta fotos/ juntos e abra o index.html no navegador.
