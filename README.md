# Venda Certa — Kit de Vendas com IA para WhatsApp

Landing page + produto digital low-ticket (R$29,90). Pronta para deploy na Vercel.

## Deploy na Vercel

1. Suba este repo para o GitHub (ou conecte o diretório direto).
2. Na [Vercel](https://vercel.com), clique em **Add New → Project**.
3. Importe o repo.
4. Framework preset: **Other** (é HTML estático).
5. **Deploy**. Pronto.

> O projeto é 100% estático (puro HTML/CSS/JS). Não precisa de build nem variáveis de ambiente.

## O produto

**Kit Venda Certa** — a IA escreve suas mensagens de venda no WhatsApp em português:
- +250 prompts de venda (abordagem, oferta, objeção, follow-up, cobrança, reativação)
- Fórmula de resposta com IA
- Roteiros de venda no WhatsApp
- Guia de adaptação por nicho
- Atualizações vitalícias

## Checkout atual

Hoje o CTA leva pro **WhatsApp** (`wa.me/5511922103713`) para o pedido ser fechado manualmente.
Próximo passo recomendado: plugar um checkout (Hotmart, Kiwify, PayT, Cartpanda, Ticto, Asaas)
para pagamento automático via Pix/cartão.

## Roadmap de escalabilidade (order bumps & upsells)

A estrutura da oferta já foi pensada para escalar. Ordem natural:

1. **Valide a base** (R$29,90 — este kit).
2. **Order bump** — na confirmação do checkout, ofereça "Kit Completo + Templates Premium" por +R$19,90 (já venha incluso a planilha de promos, os modelos de card, e a biblioteca de frases por nicho num arquivo separado).
3. **Upsell 1** — "Refill mensal de prompts" (novos nichos toda semana) como acesso vitalício por +R$29,90.
4. **Down-sell / Tripwire** — versão "mini" (50 prompts) por R$9,90 pra quem hesita.
5. **Produto mais alto** — "Venda Certa Pro": + templates de card, + formação em copy rápida, por R$97–197.

Para isso, separar o produto em **módulos independentes** (base + bump + upsell) e plugar a plataforma de checkout que suporta bumps (Kiwify, Hotmart, Ticto, PayT, Cartpanda, Asaas).

## Customização

- Troque o número do WhatsApp no arquivo `index.html` (procure `wa.me/5511922103713`).
- Ajuste preço / mensagem onde aparece.
- Marca/logo: edite os blocos `nav-brand` e footer.