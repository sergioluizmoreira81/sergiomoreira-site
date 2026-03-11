# Histórico de Mudanças — sergiomoreira.com.br

Documento de controle de evolução do site portfólio de Sergio Moreira.
Mantido para referência das próximas etapas de desenvolvimento.

---

## [v0.4] — 2026-03-11 · SEO e ajustes de conteúdo

- Alterado valor de experiência de `10+` para `20+` anos em tecnologia
- Removido card "Próximos blocos do site" da seção Destaques
- Seção Competências expandida para ocupar largura total
- Adicionado `<title>` completo: _Sergio Moreira | Engenharia, Automação e Tecnologia_
- Adicionadas metatags `description` e `keywords` para SEO básico

---

## [v0.3] — 2026-03-11 · Responsividade e menu mobile

- Adicionado menu hamburguer com animação para telas mobile
- Menu mobile fecha automaticamente ao clicar em um link
- Título hero reduzido em mobile (`text-3xl` → `text-6xl` em desktop)
- Botões com padding adaptado para mobile
- Cards de highlights com grid fixo de 3 colunas em todos os tamanhos
- Textos, paddings e espaçamentos ajustados com breakpoints `sm:` e `md:`
- Projetos com grid `sm:grid-cols-2` antes do `md:grid-cols-3`

---

## [v0.2] — 2026-03-11 · Novo layout React + Tailwind

- Substituído HTML estático por componente React com Tailwind CSS via CDN
- Layout com seções: Hero, Sobre, Áreas de Atuação, Competências, Contato
- Adicionada foto de perfil (`sergio4.jpg`)
- Borda do card da foto ajustada para acompanhar tamanho da imagem (`inline-block`)
- Tamanho da foto reduzido em ~10% (`w-44 / md:w-52`)
- Placeholder exibido enquanto foto não estava disponível
- GitHub Pages ativado com domínio personalizado `sergiomoreira.com.br`

---

## [v0.1] — 2026-03-11 · Página inicial

- Criação do repositório `sergiomoreira-site`
- HTML inicial com badge "Em construção", título e botão para o sistema de chamados
- Corrigidos erros de HTML com tags duplicadas/quebradas

---

## Próximas evoluções planejadas

### Conteúdo
- [ ] Adicionar seção de **experiência profissional** com linha do tempo
- [ ] Adicionar seção de **cases e projetos reais** com descrições e resultados
- [ ] Adicionar seção de **serviços e consultoria** com detalhamento
- [ ] Adicionar **formulário de contato** funcional

### Visual
- [ ] Galeria visual / apresentações de projetos
- [ ] Animações de entrada nas seções (scroll reveal)
- [ ] Modo claro (light mode) opcional

### Técnico
- [ ] Migrar para build com Vite + React para melhor performance
- [ ] Adicionar Google Analytics ou similar
- [ ] Melhorar SEO com Open Graph (og:image, og:title) para redes sociais
- [ ] Configurar DNS completo no Cloudflare para o domínio
