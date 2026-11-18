# PIX Console Kit

**PIX de ponta a ponta para Next.js + shadcn/ui: da cobrança ao 'Pago'.**

Cobrança → Webhook recebido → Pago.

PIX Console Kit junta as telas e a camada de pagamentos num kit para Next.js. Você cria a cobrança, recebe o webhook e mostra o status, com adaptadores para os provedores que já usa no Brasil. A base visual é Next.js 16, Tailwind CSS v4 e shadcn/ui.

## O que tem dentro

- ✅ Telas de status PIX: pendente, pago e expirado
- ✅ Checkout com QR Code PIX
- ✅ Tabela de transações formatada em R$
- ✅ Gráficos de recebíveis
- ✅ Campos de CPF e CNPJ com máscara e validação
- ✅ Textos em português (Brasil) e inglês
- ✅ `AGENTS.md` para agentes de código trabalharem bem no repositório
- ✅ Camada de pagamentos única: criar cobrança, consultar status e estornar, com adaptadores prontos para AbacatePay e Mercado Pago (Asaas e Woovi em seguida)
- ✅ Rota de webhook com verificação de assinatura e idempotência
- ✅ Schema de cobranças
- ✅ Telas de estorno (MED)
- ✅ Guia de sandbox

## Stack

![Next.js 16](https://img.shields.io/badge/Next.js-16-black?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8?style=flat&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-black?style=flat&logo=shadcnui&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

## Construindo em público

O kit ainda está em construção. A lista de espera abre em breve, junto com blocos de exemplo gratuitos sob licença MIT.

Pré-venda para fundadores: R$ 97 (vagas limitadas). Depois: R$ 197 Personal / R$ 497 Team.

- X: https://x.com/pixconsolekit
- Lista de espera: em breve
- Amostras gratuitas: Em breve, MIT

---

## In English

PIX Console Kit is end-to-end PIX for Next.js and shadcn/ui: from the charge to "Paid".

Charge → Webhook received → Paid.

Screens for PIX status (pending, paid, expired), QR checkout, a BRL transactions table, receivables charts, masked CPF/CNPJ inputs, PT-BR and EN copy, and an `AGENTS.md` for AI coding agents. On the backend: one payment layer (create a charge, check status, refund) with ready adapters for AbacatePay and Mercado Pago (Asaas and Woovi next), a webhook route with signature checks and idempotency, a charges schema, MED refund screens, and a sandbox guide.

Building in public. Waitlist and free MIT sample blocks are coming soon. $49 Personal / $129 Team.

- X: https://x.com/pixconsolekit
- Waitlist: coming soon
- Free samples: coming soon, MIT
