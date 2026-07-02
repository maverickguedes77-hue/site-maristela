# Site — Maristela Rosa Guedes · Psicóloga · Terapia Sistêmica

Site one-page completo em **HTML único** (`index.html`), sem dependências além do Google Fonts.
Construído a partir do **Brandbook v1.0/2026** (paleta Forest/Bone/Clay/Gold, Fraunces + Inter, prompt das págs. 15–17).

## Estrutura
- `index.html` — o site inteiro (CSS e JS embutidos)
- `fotos/maristela.jpg` — foto atual (provisória; ver checklist)

## Como visualizar
Basta abrir `index.html` no navegador, ou servir a pasta:
```
python -m http.server 8000 --directory .
```

## ✔ Já integrado (02/07/2026)
- **Copy oficial** do `SITE OFICIAL (2).docx`: hero, identificação, benefícios da terapia, "Quem sou eu", voluntariado (Associação Evangelizar, 3+ anos), modalidades (individual/casal/família — inclui **adolescentes**), primeira conversa de 20 minutos, FAQ oficial (10 perguntas), encerramento e redes sociais (Instagram + TikTok).
- **Calendly real**: `calendly.com/maristelarosapsi/sessao-psicoterapia` (embed na seção Agendamento).
- **Mercado Pago real**: link de pagamento (preference-id `11887111-f8e98343...`) no botão da seção Agendamento.

## ✅ Checklist ANTES de publicar (itens marcados com tag "EDITAR" no site)

**Obrigatórios (ética/veracidade):**
1. **Números da faixa de confiança** (anos de experiência, pessoas atendidas, prazo médio) — substituir pelos números reais ou remover a faixa.
2. **Depoimentos** — são exemplos ilustrativos com aviso visível. Só remover o aviso quando houver depoimentos reais **com autorização por escrito** (Código de Ética CFP).
3. **Formação** (seção Sobre) — preencher instituições e anos reais.

**Dados a confirmar:**
4. **Valor da sessão** — R$ 220 é placeholder; ajustar nos dois lugares (Investimento e Agendamento) e conferir se bate com o valor do link do Mercado Pago.
5. **Vagas/mês** ("4 novos horários") — confirmar número real.
6. **Endereço presencial** — confirmar/adicionar na seção Agendamento.
7. **E-books em PDF** — os formulários hoje registram o pedido via WhatsApp (funciona sem backend). Para envio automático por e-mail, criar conta no [Formspree](https://formspree.io) e seguir o comentário no bloco `/* E-book */` do JS.

**Recomendado:**
8. **Fotos** — o próprio documento oficial sugere: Hero = rosto próximo olhando para a câmera (a atual serve); "Quem sou eu" = foto espontânea (poltrona, xícara, ambiente real); Propósito = foto em atividade do voluntariado; e uma foto caminhando em parque (comunica "novos caminhos"). Substituir em `fotos/` mantendo proporção 4:5.

## Publicação
Qualquer host estático serve: Netlify Drop (arrastar a pasta), Vercel, GitHub Pages ou Cloudflare Pages.

## O que NÃO alterar sem consultar o brandbook
- Paleta (hex exatos) e regra 60/25/10/5
- Fraunces (títulos) + Inter (corpo) — nunca trocar
- Aviso ético do rodapé (CVV 188 / SAMU 192) — **não-negociável**
- Alternância de fundos bone → forest → bone-2 (nunca duas seções escuras seguidas)
