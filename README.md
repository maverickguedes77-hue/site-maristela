# Site — Maristela Rosa Guedes · Psicóloga · Terapia Sistêmica

## 🌐 NO AR
**https://maristelarosapsi-lab.github.io/site-maristela/**

Repositório: `maristelarosapsi-lab/site-maristela` (conta da Maristela — transferência concluída em 02/07/2026). Todo o SEO (canonical, sitemap, robots, Open Graph) aponta para esta URL. A URL antiga (maverickguedes77-hue) deixou de existir — atualize favoritos e o link da bio do Instagram/TikTok.

## Estrutura (esta pasta É a pasta de edição do site)
- `index.html` — o site inteiro (HTML único, CSS e JS embutidos)
- `fotos/` — ensaio profissional (02/07): `hero.jpg` (poltrona clara, sorriso), `sobre.jpg` (blusa verde), `galeria-livro.jpg`, `galeria-estudo.jpg`, `galeria-poltrona.jpg` — otimizadas para web (~115–200 KB)
- `ebooks/` — os 2 PDFs de download direto ("5 Padrões" e "Pensar Sistêmico")
- `council/` — relatório e transcript da análise do conselho de especialistas (não publicado)
- `psi/` — arquivos originais da sessão anterior (não publicado)

## ✏️ Como editar e republicar
1. Edite `index.html` (ou peça ao Claude nesta pasta).
2. No terminal, dentro desta pasta:
   ```
   git add -A
   git commit -m "descrição da mudança"
   git push
   ```
3. O GitHub Pages republica sozinho em ~1 minuto.

Para testar localmente antes: `python -m http.server 8000` e abrir `http://localhost:8000`.

## ✔ Estado atual (02/07/2026 — 2ª publicação)
- Copy 100% do documento oficial + brandbook (Fraunces+Inter, Forest/Bone/Clay/Gold)
- **Hero sem promessas de resultado** (sem "8 semanas") — usa o texto oficial de acolhimento
- Valor: **R$ 200** · Formação: 4 anos · Público: adolescentes, adultos, casais e famílias
- Calendly real + Mercado Pago real (**sem boleto** no texto — conferir também no painel do MP se o link aceita boleto e desativar lá)
- E-books com download direto + **leads enviados por e-mail via FormSubmit** (grátis, sem conta)
- CTA "Quero agendar minha primeira sessão" no painel pós-download do e-book
- **Seção de depoimentos removida** — futuro: avaliações reais do Google (ver pendência 3)
- Sem menção a recibo/reembolso de plano de saúde (removido a pedido)
- Quiz 100% no navegador · LGPD no rodapé · Aviso ético CFP (CVV 188/SAMU 192) · Zero tags EDITAR
- Conta GitHub da Maristela (**maristelarosapsi-lab**) convidada como **admin** do repositório — aceitar o convite no e-mail maristelarosapsi@gmail.com

## ⚡ Ações imediatas (tudo no e-mail maristelarosapsi@gmail.com)
1. **Aceitar a transferência do repositório** — e-mail do GitHub "Repository transfer": clicar em Accept. Isso tira o "maverickguedes77" da URL.
2. **Ativar os leads (1 clique)** — e-mail do FormSubmit: clicar em "Activate". Depois disso, cada download de e-book chega como e-mail com nome, e-mail e livro escolhido (o lead de teste já foi enviado).
3. **Clicar nos 3 botões de pagamento** do site uma vez cada, conferindo os valores (R$ 200 / 250 / 280) e se o boleto está desativado nos links (config no painel do Mercado Pago).
4. **Google Search Console** (para aparecer rápido no Google): acessar https://search.google.com/search-console logada no Google dela → adicionar propriedade com a URL nova → verificar → enviar o sitemap `sitemap.xml`. O site já tem todo o SEO on-page pronto (palavras-chave, dados estruturados, sitemap, robots).

## 🌐 Domínio próprio (ex.: maristelaguedespsi.com.br)
1. Registrar em https://registro.br (~R$40/ano). Sugestões: `maristelaguedespsi.com.br` · `maristelarosaguedes.com.br` · `maristelaguedes.psc.br`
2. No painel DNS do registro.br, criar:
   - 4 registros **A** para `@`: `185.199.108.153` · `185.199.109.153` · `185.199.110.153` · `185.199.111.153`
   - 1 registro **CNAME** para `www` → `maverickguedes77-hue.github.io`
3. No GitHub: repositório → Settings → Pages → Custom domain → digitar o domínio → salvar → marcar "Enforce HTTPS" (aparece após ~1h de propagação).
4. Pronto — o site responde no domínio próprio sem mudar mais nada.

## 📋 Pendências (pós-lançamento)
1. **Teste de ponta a ponta**: agendar horário-teste no Calendly e abrir o checkout do MP até o fim (conferir R$ 200 e se boleto está desativado no link).
2. **Google Business Profile** (para os comentários reais no Google): criar perfil "Maristela Rosa Guedes — Psicóloga" em https://business.google.com; quando houver avaliações, adicionamos a seção no site puxando as reais.
3. **Fotos melhores** (guia no documento oficial): Hero = rosto próximo; "Quem sou eu" = espontânea; Propósito = voluntariado; extra = caminhando em parque. Proporção 4:5.

## O que NÃO alterar sem consultar o brandbook
- Paleta (hex exatos) e regra 60/25/10/5 · Fraunces + Inter · Aviso ético do rodapé (não-negociável) · Alternância de fundos claro/escuro
