---
type: map
title: Mapa da Knowledge Base
description: Porta de entrada da base — estrutura, ordem de leitura e as decisões fundadoras.
tags: [mapa, navegacao]
timestamp: 2026-06-23
related:
  - 01_tese.md
  - 02_lexico.md
  - ../09-operacao/00_schema.md
  - ../../STATE.md
---

# Mapa da KB Achei o Manto

> Comece por aqui. Este é o documento canônico de navegação da base.

## As decisões fundadoras

> Cole aqui suas respostas às [oito perguntas fundamentais](../00-comece-aqui/01_perguntas-fundamentais.md).

- **Objeto:** Marca Achei o Manto: catálogo, vendas e comunicação.
- **Públicos:** Feito para outras IAs absorverem o conhecimento e produzirem a mesma saída de informação (ver `views/`).
- **Camadas:** uma camada.
- **Privacidade:** público — nunca entra: segredos, tokens, preços de custo, margens e dados pessoais de clientes.
- **Manutenção:** PR-only; merge pelo dono (Gabriel); ritual uma sessão = uma branch = uma PR.
- **Agentes:** Claude e outras IAs em geral; identificação por trailer `Co-Authored-By:` e prefixo de branch.
- **Frontmatter:** leve (OKF).
- **Ingestão de calls:** sim, usa `projeto/`.

## Estrutura

- `01-base/` — fundação: tese, léxico, entidades
- `02-conteudo/` — o conhecimento do objeto (seções que você define)
- `09-operacao/` — governança da própria base: schema, camadas, ingestão
- `views/` — trilhas de leitura por público
- `type/` — tipos de nota como lente
- `projeto/` — operação viva: inbox, decisões, logs, handoffs (opcional)

## Ordem de leitura sugerida

1. Este mapa
2. [Estado atual](../../STATE.md)
3. [Tese](01_tese.md)
4. [Léxico](02_lexico.md)
5. [Entidades](03_entidades.md)
