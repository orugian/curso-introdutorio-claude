# 02.02 — A anatomia de um bom prompt

| | |
|---|---|
| **Duração alvo** | 9 min |
| **Slides** | 3 (bloco de código com a estrutura) |
| **Material base** | `modulos/02-chat/README.md` § 2.2 |
| **Arquivo de vídeo** | `M02-A02-anatomia-do-prompt.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck no **slide 3** (o bloco `[Contexto] [Tarefa] [Formato] [Tom] [Restrições]`)
- [ ] Conversa **nova e vazia** no Claude
- [ ] Prompts 1, 2 e 3 já copiados em um bloco de notas ao lado (você vai colar três vezes)
- [ ] Nada do módulo anterior visível na lateral

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho — o prompt ruim | 0:00 | Tela |
| A estrutura, os 5 blocos | 1:15 | Slide 3 |
| Demo: reescrevendo ao vivo | 3:00 | Tela |
| Comparação lado a lado | 6:30 | Tela |
| Fecho | 8:00 | Slide 3 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[TELA: claude.ai]` · **fala literal + ação**

Digite (não cole — esse é curto e o efeito é melhor digitando) e envie:

```
Me ajuda com marketing
```

Enquanto responde:

> "Olha o que acontece. Eu pedi ajuda com marketing, e ele me devolve… isso.
> Um panorama genérico, correto, e completamente inútil pra mim.
>
> Só que o problema aqui não é ele. Sou eu. Eu não disse quem eu sou, o que eu
> vendo, pra quem, nem o que eu preciso receber de volta. Ele preencheu os
> buracos com o que dava.
>
> Nos próximos nove minutos você vai aprender uma estrutura de cinco partes que
> transforma pedidos desse tipo em resposta aproveitável. E a gente vai reescrever
> esse mesmo prompt no final."

---

### ⏱ 1:15 — A ESTRUTURA · `[SLIDE 3]` · **fala literal para cada bloco**

Percorra os cinco, um a um. Fale devagar — este é o núcleo da aula.

> **Contexto.** Quem é você e qual o cenário. Sem isso, ele escreve para
> ninguém. 'Sou coordenador de TI de uma empresa com duzentos funcionários'
> muda tudo que vem depois.

> **Tarefa.** O que precisa ser feito, específico. 'Melhore isso' não é tarefa.
> 'Reescreva em três parágrafos com tom formal' é tarefa.

> **Formato.** Como você quer receber. Tabela, lista, e-mail pronto, código,
> texto corrido. Se você não disser, ele escolhe — e normalmente escolhe texto
> corrido, que é o formato que menos serve.

> **Tom.** Formal, casual, técnico, didático. Esse é o que mais gente esquece e
> o que mais gera retrabalho.

> **Restrições.** O que NÃO fazer. Esse é o segredo mal contado: dizer o que
> você não quer economiza mais tempo do que dizer o que você quer.

Fechamento do bloco:

> "Você não precisa dos cinco toda vez. Mas repara: quase todo prompt frustrante
> que você já escreveu estava faltando pelo menos dois deles."

---

### ⏱ 3:00 — DEMO: REESCREVENDO AO VIVO · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1** (versão estruturada do e-mail). Enquanto gera, narre:

- Aponte na tela cada parte do prompt e nomeie qual bloco ela é.
- "Isso aqui é contexto. Isso é tarefa. Isso é formato. Isso é restrição."

Quando a resposta vier:
- Mostre que ele respeitou o formato pedido, item por item.
- Mostre que ele respeitou a restrição — não incluiu o que você proibiu.

> **Fala literal:**
> "Repara que eu não pedi para ele ser bom. Eu descrevi o que 'bom' significa
> nesse caso. É isso que a estrutura faz."

Agora cole o **Prompt 2** (mesmo pedido, só trocando o Tom):

- Não recomece a conversa — mande na sequência.
- Mostre lado a lado: mesmo conteúdo, temperatura completamente diferente.

> **Fala literal:**
> "Uma linha. Eu mudei uma linha e o texto virou outra coisa. É por isso que o
> Tom entra na estrutura."

Cole o **Prompt 3** (terceiro tom) e passe rápido — o aluno já entendeu o
mecanismo, aqui é só reforço visual.

---

### ⏱ 6:30 — COMPARAÇÃO · `[TELA: destaque]` · **fala livre**

Role a conversa para cima, até o "Me ajuda com marketing" do começo.

- Deixe a primeira resposta e a última na mesma tela, se der.
- > **Fala literal:**
  > "Mesmo modelo. Mesma conta. Mesmo dia. A única variável que mudou fui eu."

Agora reescreva o prompt de marketing ao vivo, usando a estrutura — cole o
**Prompt 4** e deixe rodando enquanto fala o fecho.

---

### ⏱ 8:00 — FECHO · `[SLIDE 3]` · **fala literal**

> "Cinco blocos: contexto, tarefa, formato, tom, restrições. Se você sair desse
> curso só com isso, já valeu o módulo.
>
> Meu pedido pra essa aula: pega um prompt que você escreveu essa semana e que
> te decepcionou. Reescreve com os cinco blocos. Manda de novo. Você vai ver a
> diferença antes de terminar o café.
>
> Na próxima aula a gente sobe um degrau: quatro técnicas que resolvem os casos
> em que nem a estrutura completa dá conta. Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — estrutura completa, tom formal**

```
[Contexto] Sou coordenador de TI de uma empresa com 200 funcionários.
Vamos migrar para um novo sistema de gestão no próximo trimestre.

[Tarefa] Escreva o e-mail de anúncio dessa migração para todos os
funcionários.

[Formato] E-mail pronto para envio, com assunto, no máximo 4 parágrafos
e um bloco final de "próximos passos" com 3 itens.

[Tom] Formal e institucional.

[Restrições] NÃO inclua detalhes técnicos da migração. NÃO prometa datas
específicas além do trimestre. NÃO use "revolucionário", "inovador" ou
"disruptivo".
```

**Prompt 2 — mesmo pedido, tom próximo**

```
Reescreva o mesmo e-mail mudando apenas o Tom: agora próximo e
conversacional, como se eu estivesse falando com um colega de outro setor.
Mantenha o mesmo formato e as mesmas restrições.
```

**Prompt 3 — mesmo pedido, tom direto**

```
Agora mais uma versão: tom direto e enxuto, para quem lê e-mail no celular
entre uma reunião e outra. Máximo 120 palavras no corpo. Mantenha o assunto
e o bloco de próximos passos.
```

**Prompt 4 — o "me ajuda com marketing" reescrito**

```
[Contexto] Sou coordenador de TI da mesma empresa de 200 funcionários.
Preciso comunicar internamente a migração do sistema de gestão.

[Tarefa] Monte um plano de comunicação interna em 3 fases:
pré-lançamento, lançamento e pós-lançamento.

[Formato] Tabela com as colunas: Fase | Ação | Canal | Responsável sugerido.
Duas ações por fase.

[Tom] Profissional, mas acessível.

[Restrições] NÃO inclua aspectos técnicos da migração — isso será
comunicado separadamente pela equipe de sistemas.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| O "Me ajuda com marketing" veio bom demais | Acontece. Vire a favor: "olha, até que veio decente — só que veio sobre marketing em geral, e eu preciso de comunicação interna de TI. Ele acertou a pergunta errada." O argumento continua de pé. |
| Ele ignorou uma restrição | **Mostre.** É ouro didático: "ele furou uma restrição aqui — restrição é pedido, não garantia. Você confere." Não regrave. |
| As três versões de tom ficaram parecidas | Peça explicitamente o contraste: *"Compare as três versões que você escreveu e me diga em uma frase o que muda entre elas."* Ele explicita a diferença. |
| A resposta ficou longa demais para caber na tela | Role devagar enquanto narra. Não leia tudo — leia o começo e aponte a estrutura. |

---

## Notas de edição

- `⏱ 0:00–1:15` — a resposta genérica do gancho precisa aparecer, mas **não
  inteira**. Mostre 3 segundos rolando e corte.
- `⏱ 1:15–3:00` — os cinco blocos entram **um a um** no slide, sincronizados
  com a fala. É a sequência mais importante do módulo inteiro.
- `⏱ 4:30` e `⏱ 5:30` — nas trocas de tom, **tela dividida** com as duas
  versões lado a lado vale mais que mil palavras.
- `⏱ 6:30` — o "mesmo modelo, mesma conta, mesmo dia" pede **card de texto**
  em tela cheia por 2s.
- Corte todas as esperas de geração. Esta aula tem quatro.
- **Título sugerido:** "Por que o Claude te dá respostas genéricas (e como resolver)"
- **Thumbnail:** o prompt "Me ajuda com marketing" com um X vermelho ao lado.
