# LP-CONFICON

## Leitura do Design

- Paleta principal: azul institucional `#001e40`, fundo claro `#f9f9fc`, branco `#ffffff`, dourado claro `#ffdea5`, acento dourado escuro `#775a19`, texto `#43474f`, texto secundario azul `#799dd6`.
- Tipografia: Roboto Flex Regular. H1 e grandes CTAs em 48px com line-height aproximado de 60px; H2 de secoes em 32px/38.4px; cards principais em 24px/31.2px; corpo em 18px, 16px e 14px; eyebrows em 12px uppercase com tracking alto.
- Grid e espacamento: frame desktop de 1280px, container util de 1152px com margens laterais de 64px, grid de 12 colunas, gaps de 32px, secoes com padding vertical de 96px. Cards usam raio 4px ou 8px; CTA final usa raio 16px.
- Blocos da pagina: TopNavBar, Hero, Problem Section, Services Section, Differentials / Proof Section, About Section, CTA Final e Footer.
- Componentes reutilizaveis: Logo, Navbar, Button, Eyebrow, ProblemCard, ServiceCard, ProofItem, FinalCTA, FooterColumn e Newsletter.
- Imagens exportadas do Figma: foto bruta do hero (`assets/hero-photo.png`) e foto consultiva do bloco de diferenciais (`assets/meeting-photo.png`). As capturas `hero-section.png` e `meeting-section.png` foram mantidas apenas como referencia visual.
- Textos editaveis: todos os titulos, chamadas, descricoes, menus, cards, CTA, links do footer e newsletter estao em `src/main.js`, sem texto achatado dentro de imagem.

## Como Abrir

Abra `index.html` em um navegador moderno. A pagina nao depende de build para visualizar.

## Publicacao

Projeto estatico pronto para Vercel. O comando de build apenas confirma que nao ha etapa de compilacao obrigatoria.
