# Criação da Página "Quem Sou" (quem-sou.html)

A página "Quem Sou" será desenvolvida para apresentar a Rachel Amancio, focando em autoridade, história e provas sociais (certificações e aparições). A página compartilhará a mesma identidade visual, estrutura de fontes, cabeçalho e rodapé do arquivo `index.html` original.

## User Review Required

Por favor, valide se a estrutura e a escolha dos componentes estão alinhados com o que você deseja para a página, principalmente a abordagem do carrossel de fotos pessoais e a divisão das seções.

## Arquivos a serem modificados/criados

### [NEW] quem-sou.html
Criação do novo arquivo HTML contendo 6 seções principais:

1. **Header & Base CSS**: Copiados integralmente de `index.html` para manter 100% de consistência na navegação (inclusive atualizando a ordem dos links recém-ajustada).
2. ** Hero (Topo)**:
   - Layout dividido entre texto forte à esquerda e imagem de destaque da Rachel à direita.
   - Aplicações de animação em *slide-up* e *delay*.
3. **Seção Sobre**:
   - Foco em legibilidade e tipografia fluida (fonte Inter) com grande espaçamento.
4. **Seção Especializações**:
   - Grid moderno de cards de "vidro" (Glassmorphism) com ícones minimalistas representando cada formação/título listado.
5. **Seção de Destaques (Prova Social)**:
   - Implementação de um Carrossel "Marquee" contínuo animado para as imagens de certificações/participações, nos mesmos moldes do carrossel das empresas de `index.html`, mas com os cantos arredondados, leve sombra e `hover` escalonado.
6. **Seção Missão**:
   - Faixa com contraste visual sutil e foco total no texto "Minha missão...", fechando com um ar de liderança inspiracional.
7. **CTA Final**:
   - Bloco de chamada para ação com o botão animado Premium ("Beam Button") chamando para "Quero desenvolver minha liderança" direcionando para contato.
8. **Footer**: Copiado de `index.html`.

## Open Questions

- Na área de Hero, você gostaria que utilizássemos uma imagem específica para a foto profissional da página (ex: a imagem da xícara/rosto usada em index)? Senão utilizarei um bom placeholder da base de imagens temporária ou reaproveitarei as do index até fornecida.
- A navegação da página nova deve ter os links ancorados na home page (ex: `index.html#solucoes`)? Como "Quem Sou" será uma página externa, precisamos ajustar os links do Header para apontar para `index.html/...` quando o usuário quiser voltar.

## Verification Plan

1. Construir e salvar o arquivo `quem-sou.html`.
2. Validar que as imagens carregam apropriadamente.
3. Checar a responsividade (Visualização mobile da seção especializações e carrossel de imagem interativas).
4. Conferir a funcionalidade das animações do Design System importado.
