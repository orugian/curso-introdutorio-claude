# 02.07 — Construindo e iterando um dashboard

| | |
|---|---|
| **Duração alvo** | 10 min |
| **Slides** | 13 (prompt do dashboard) |
| **Material base** | `modulos/02-chat/README.md` § 2.4 + "Modelo de Artifact" |
| **Arquivo de vídeo** | `M02-A07-dashboard-e-iteracao.mp4` |

> ⚠️ **Grave esta aula e a 02.08 na mesma sessão, com a mesma conversa aberta.**
> A 02.08 publica exatamente este dashboard. Se a conversa se perder, você
> reconstrói do zero.

---

## Preparação (antes do REC)

- [ ] Deck no **slide 13**
- [ ] Conversa **nova e vazia**, fora de qualquer Projeto
- [ ] Prompts 1 a 4 copiados na ordem, em bloco de notas
- [ ] Janela larga (o painel do artifact precisa de espaço)
- [ ] Reserve ~25 min de gravação para 10 min de vídeo — geração de dashboard demora

**Contexto desta aula:** loja fictícia de acessórios para celular, vendendo em
Mercado Livre e Shopee. É o exemplo de marketplace do módulo — os dados são
inventados e ditos como inventados.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 13 |
| Anatomia do prompt de dashboard | 0:45 | Slide 13 |
| Geração — v1 | 2:30 | Tela |
| Iteração 1: filtro | 4:45 | Tela |
| Iteração 2: tabela | 6:15 | Tela |
| Iteração 3: correção de erro | 7:30 | Tela |
| Fecho | 9:15 | Slide 13 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 13]` · **fala literal**

> "Dez minutos. É o tempo que a gente vai levar pra sair do zero e chegar num
> dashboard funcional, com gráfico, filtro e tabela — sem escrever uma linha de
> código.
>
> Mas o que eu quero mesmo que você leve dessa aula não é o dashboard. É o
> **método**. Porque a primeira versão nunca é a boa, e a diferença entre quem
> tira valor disso e quem desiste está inteira em como você itera."

---

### ⏱ 0:45 — ANATOMIA DO PROMPT DE DASHBOARD · `[SLIDE 13]` · **fala literal**

Mostre o prompt do slide e disseque. **Não leia** — explique a lógica dele.

> "Repara que esse prompt não pede 'faça um dashboard bonito'. Ele especifica
> cinco coisas, e são sempre as mesmas cinco:
>
> **Um: a tecnologia.** HTML com uma biblioteca de gráfico. Se você não disser, ele
> escolhe — e pode escolher algo que não abre no seu navegador.
>
> **Dois: o visual.** Tema, cor de fundo, cor de destaque. Uma frase resolve.
>
> **Três: os componentes.** Quais cards, quais gráficos, qual tabela. Item por item.
>
> **Quatro: os dados.** De onde vêm. Aqui eu vou pedir dados fictícios, e vou dizer
> que são fictícios — na aula 09 a gente faz com dado de verdade.
>
> **Cinco: as restrições.** Responsivo, autocontido, sem depender de nada externo.
>
> Guarda essa lista de cinco. Ela vale pra qualquer artifact visual que você for
> pedir na vida."

---

### ⏱ 2:30 — GERAÇÃO v1 · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1**. A geração é longa — **narre, não fique em silêncio**:

- Aponte o painel abrindo e o código sendo escrito.
- Comente o que está acontecendo: "agora ele montou a estrutura, agora está nos
  dados, agora nos gráficos".
- > **Fala literal, enquanto gera:**
  > "Esse tempo de espera existe e é normal. Eu prefiro esperar quarenta segundos
  > aqui do que passar duas horas montando isso à mão."

Quando renderizar:
- Passe o mouse pelos gráficos (mostre o tooltip).
- Role a página do artifact.
- **Seja honesto sobre o que ficou ruim.**
  > **Fala literal:**
  > "Veio bom? Veio. Veio pronto? Não. E é aqui que a maioria das pessoas para —
  > acha que a primeira versão é a resposta. A primeira versão é o rascunho."

---

### ⏱ 4:45 — ITERAÇÃO 1: FILTRO · `[TELA]` · **fala livre**

Cole o **Prompt 2** (adicionar filtro por canal).

> **Fala literal — a regra da iteração:**
> "Presta atenção em como eu pedi. Eu não descrevi o dashboard inteiro de novo.
> Eu disse só o que muda.
>
> Essa é a regra: na iteração você fala da **diferença**, não do todo. Quem
> reescreve o pedido completo toda vez costuma perder o que já estava bom."

Quando atualizar:
- Use o filtro na tela. Troque entre os canais e mostre os gráficos respondendo.
- Aponte que ele preservou tudo o que já existia.

---

### ⏱ 6:15 — ITERAÇÃO 2: TABELA · `[TELA]` · **fala livre**

Cole o **Prompt 3** (tabela de top 5 produtos).

- Mostre a tabela aparecendo integrada ao layout, não pregada no fim.
- Comente: ele manteve a paleta, o espaçamento, a fonte — porque o contexto da
  conversa inteira continua valendo.

> **Fala literal:**
> "Terceira versão. Cada rodada custou uma frase. É esse o ritmo."

---

### ⏱ 7:30 — ITERAÇÃO 3: CORREÇÃO · `[TELA]` · **fala livre**

Aqui você corrige algo que **realmente** ficou ruim na sua tela. Escolha o que
couber (o Prompt 4 traz três opções prontas):

- Cor com contraste ruim
- Número sem formatação de real
- Gráfico apertado / legenda cortada
- Algo quebrado no mobile

> **Fala literal — o fechamento do método:**
> "E esse é o terceiro tipo de iteração. A primeira adiciona. A segunda expande.
> A terceira **conserta**.
>
> Você não precisa saber consertar. Você precisa saber **descrever o que está
> errado**. 'Esse texto está difícil de ler contra o fundo' é uma instrução
> perfeitamente boa de programação, quando quem programa é ele."

Se quiser fechar com força, peça a visão mobile: redimensione a janela e mostre
o dashboard respondendo.

---

### ⏱ 9:15 — FECHO · `[SLIDE 13]` · **fala literal**

> "Dashboard pronto, em quatro rodadas: gerou, filtrou, expandiu, consertou.
>
> Grava o método: primeiro prompt completo com os cinco itens; depois só a
> diferença, uma coisa por vez.
>
> E agora vem a parte que faz esse trabalho sair da sua tela: na próxima aula a
> gente publica esse dashboard e gera um link que qualquer pessoa abre — sem
> conta no Claude, sem instalar nada.
>
> **Não fecha essa conversa.** A gente continua exatamente daqui. Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — geração inicial**

```
Crie um dashboard de vendas usando HTML + Chart.js via CDN, como artifact.

CONTEXTO: loja de acessórios para celular que vende em Mercado Livre e Shopee.

VISUAL:
- Tema escuro profissional, fundo #1a1a2e, cor de destaque #e94560
- Layout limpo, com respiro entre os blocos

COMPONENTES:
- 4 cards no topo: Receita total, Ticket médio, Pedidos, Produto campeão
- Gráfico de barras: receita por mês, 12 meses
- Gráfico de linha: média móvel de 3 meses sobre a mesma receita
- Gráfico de rosca: participação de cada canal (Mercado Livre x Shopee)

DADOS: fictícios, mas realistas para uma loja de acessórios de celular
faturando entre R$ 40 mil e R$ 90 mil por mês, com sazonalidade de fim de ano.

RESTRIÇÕES:
- Responsivo, precisa funcionar no celular
- Arquivo único e autocontido
- Valores em real, formatados com R$ e separador de milhar
```

**Prompt 2 — iteração 1**

```
Adicione um filtro no topo para alternar entre "Todos os canais",
"Mercado Livre" e "Shopee". Ao trocar o filtro, os 4 cards e os dois
primeiros gráficos precisam recalcular. Mantenha o resto igual.
```

**Prompt 3 — iteração 2**

```
Adicione uma tabela com os 5 produtos mais vendidos, com as colunas
Produto, Canal, Unidades e Receita. A tabela também deve respeitar
o filtro de canal. Mantenha o estilo visual do resto do dashboard.
```

**Prompt 4 — iteração 3 (escolha a que se aplicar à sua tela)**

```
O contraste do texto dos cards contra o fundo está baixo. Aumente a
legibilidade mantendo a paleta atual.
```

```
Os valores do gráfico de barras estão sem formatação de moeda.
Formate como R$ com separador de milhar, inclusive nos tooltips.
```

```
No celular os gráficos ficam espremidos e a legenda corta.
Ajuste o layout para telas menores que 600px.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| **O gráfico não renderizou (tela em branco)** | O mais provável nesta aula. Peça: *"O dashboard está em branco. Verifique se a biblioteca de gráfico carregou e corrija."* Mostre a correção — é conteúdo real e o aluno vai passar por isso. |
| A geração passou de 90s | Narre o que espera ver e marque `[CORTE]`. Nunca fique em silêncio. |
| Uma iteração quebrou o que já funcionava | **Excelente material.** Diga: *"Isso acontece."* e peça: *"Você quebrou o filtro que já funcionava. Restaure o comportamento anterior e mantenha a mudança nova."* |
| Os dados fictícios vieram absurdos | Peça números coerentes com a faixa do prompt. Reforce em voz alta que são fictícios — não deixe dúvida no aluno. |
| A conversa se perdeu / aba fechou | Pare a gravação da 02.08. Refaça o dashboard com os prompts 1 a 3 antes de gravar a publicação. |
| Passou de 12 min | Corte a iteração 2 (tabela). O método já está demonstrado com adicionar + consertar. |

---

## Notas de edição

- **A aula com mais tempo morto do módulo.** Corte agressivamente: cada geração
  vira 2 a 3 segundos de código passando em velocidade acelerada.
- `⏱ 0:45–2:30` — os cinco itens do prompt entram **numerados na tela**, um a um.
  É o resumo que o aluno vai printar.
- `⏱ 2:30` — a v1 renderizando merece **transição limpa**, sem corte no meio.
- `⏱ 4:45` e `⏱ 6:15` — em cada iteração, **antes/depois lado a lado** por 2s.
- `⏱ 5:30` — o filtro sendo usado precisa ser **gravado em movimento real**
  (clicar, ver mudar). É o que prova que o dashboard funciona.
- `⏱ 8:45` — se gravar a visão mobile, use **redimensionamento suave** da janela.
- **Timer/contador na tela** ("v1 → v2 → v3 → v4") ajuda o aluno a acompanhar as rodadas.
- **Título sugerido:** "Dashboard funcional em 4 prompts (sem escrever código)"
- **Thumbnail:** o dashboard final, escuro, com os gráficos visíveis.
