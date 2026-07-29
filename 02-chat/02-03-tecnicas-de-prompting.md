# 02.03 — Quatro técnicas de prompting

| | |
|---|---|
| **Duração alvo** | 9 min |
| **Slides** | 4 |
| **Material base** | `modulos/02-chat/README.md` § 2.2 |
| **Arquivo de vídeo** | `M02-A03-tecnicas-de-prompting.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck no **slide 4** (lista das técnicas)
- [ ] Conversa **nova e vazia**
- [ ] Prompts 1 a 5 copiados em bloco de notas ao lado
- [ ] ⚠️ Grave esta aula **depois** da 02.02 — ela referencia os cinco blocos

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 4 |
| Zero-shot vs Few-shot | 0:45 | Slide → tela |
| Demo few-shot | 2:00 | Tela |
| Chain of Thought | 4:00 | Tela |
| Role prompting | 6:00 | Tela |
| Quando usar cada uma | 7:45 | Slide 4 |
| Fecho | 8:20 | Slide 4 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 4]` · **fala literal**

> "Na aula passada a gente montou a estrutura de um bom prompt. Cinco blocos.
> Funciona pra oitenta por cento dos casos.
>
> Essa aula é sobre os outros vinte. Quatro técnicas com nome feio e uso simples,
> que resolvem três problemas específicos: quando você não consegue descrever o
> formato que quer, quando o Claude erra a conta, e quando você precisa de um
> especialista e não de um assistente genérico."

---

### ⏱ 0:45 — ZERO-SHOT vs FEW-SHOT · `[SLIDE 4]` · **fala literal**

> "Zero-shot é o que você já faz: 'faça X'. Sem exemplo. É o padrão, e na maior
> parte do tempo basta.
>
> Few-shot é quando você mostra em vez de descrever. Você dá dois, três exemplos
> do resultado que quer, e pede o resto igual.
>
> A regra pra decidir é essa: se descrever o formato que você quer está ficando
> mais difícil do que dar um exemplo dele, para de descrever e dá o exemplo."

---

### ⏱ 2:00 — DEMO: FEW-SHOT · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1** (zero-shot, títulos de anúncio):
- Deixe gerar. Comente: "veio ok, mas cada título com uma cara."

Cole o **Prompt 2** (mesmo pedido, com dois exemplos):
- `[TELA: destaque]` aponte os dois exemplos dentro do prompt.
- Quando gerar, mostre: mesmo padrão de estrutura, mesma ordem dos elementos,
  mesmo comprimento.

> **Fala literal:**
> "Eu não expliquei nenhuma regra. Não falei 'comece pelo produto, depois a
> especificação, depois o diferencial'. Eu mostrei duas vezes e ele extraiu a
> regra sozinho. Isso é few-shot."

Contexto de aplicação (rápido, sem virar aula de e-commerce):
- Serve pra qualquer coisa repetitiva com padrão: título de anúncio, resposta de
  atendimento, descrição de card de tarefa, mensagem de commit.

---

### ⏱ 4:00 — CHAIN OF THOUGHT · `[TELA: claude.ai]` · **fala livre**

> **Fala literal — o setup:**
> "Essa é a técnica que mais parece superstição e mais funciona. Chamam de
> cadeia de raciocínio. Na prática você pede: 'pense passo a passo antes de
> responder'."

Cole o **Prompt 3** (problema de precificação, sem CoT):
- Deixe responder. **Não diga se está certo ou errado ainda.**

Cole o **Prompt 4** (mesmo problema, com "pense passo a passo"):
- Mostre a diferença: ele decompõe, mostra as contas, e só então conclui.

> **Fala literal:**
> "Duas coisas acontecem aqui. A primeira é que ele acerta mais, porque
> raciocinar em etapas reduz erro. A segunda, e essa é a que importa pra você:
> agora você consegue **auditar**. Se o resultado veio estranho, você olha em
> qual passo ele torceu — em vez de só desconfiar do número final."

⚠️ Se as duas respostas derem o mesmo resultado, veja o Plano B.

---

### ⏱ 6:00 — ROLE PROMPTING · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 5** (mesmo texto avaliado por três papéis diferentes):

- Mostre que o conteúdo avaliado é o mesmo, mas cada papel enxerga outra coisa:
  o advogado vê risco, o vendedor vê objeção, o editor vê clareza.

> **Fala literal:**
> "Papel não é fantasia. Quando você diz 'você é um revisor jurídico', você não
> está pedindo pra ele fingir — você está dizendo qual recorte da resposta te
> interessa. É um filtro, não um teatro.
>
> E o uso mais forte disso não é pedir um papel. É pedir três, sobre a mesma
> coisa, e comparar. Você acabou de montar um comitê de revisão em quarenta
> segundos."

---

### ⏱ 7:45 — QUANDO USAR CADA UMA · `[SLIDE 4]` · **fala literal**

> "Resumo pra colar na parede:
>
> Formato difícil de explicar? Few-shot — mostra exemplos.
> Conta, lógica ou decisão com muitos critérios? Cadeia de raciocínio — pede
> passo a passo.
> Precisa de um olhar especializado? Papel — e de preferência mais de um.
> Resto? Zero-shot com os cinco blocos da aula anterior."

---

### ⏱ 8:20 — FECHO · `[SLIDE 4]` · **fala literal**

> "Essas quatro técnicas se combinam. Um prompt com contexto, tarefa, formato,
> dois exemplos, um papel definido e um 'pense passo a passo' não é exagero — é
> segunda-feira.
>
> Só que repara numa coisa: tudo que a gente escreveu hoje, você vai ter que
> escrever de novo amanhã. E depois de amanhã. Toda vez.
>
> Isso tem solução, e ela chama Projetos. Próxima aula."

---

## Prompts para copiar e colar

**Prompt 1 — zero-shot**

```
Escreva 5 títulos de anúncio para uma capa de celular de silicone,
compatível com iPhone 15, disponível em 6 cores.
```

**Prompt 2 — few-shot**

```
Escreva 5 títulos de anúncio para uma capa de celular de silicone,
compatível com iPhone 15, disponível em 6 cores.

Siga exatamente o padrão destes exemplos:

Exemplo 1: "Fone Bluetooth 5.3 TWS - Cancelamento de Ruído - 30h Bateria"
Exemplo 2: "Carregador Turbo 20W USB-C - Compatível iPhone e Android - Certificado"

Padrão a seguir: [Produto] [Especificação principal] - [Diferencial] - [Benefício mensurável]
```

**Prompt 3 — sem cadeia de raciocínio**

```
Compro um produto por R$ 42,00. O marketplace cobra 16% de comissão sobre
o preço de venda, mais R$ 6,00 fixos por unidade vendida. Quero margem
líquida de 25% sobre o preço de venda. Por quanto devo vender?
```

**Prompt 4 — com cadeia de raciocínio**

```
Mesma pergunta, mas pense passo a passo antes de responder.
Mostre cada etapa do cálculo, identifique a fórmula que está usando,
e só no final apresente o preço. Depois confira o resultado substituindo
o valor encontrado de volta na conta.
```

**Prompt 5 — role prompting múltiplo**

```
Avalie o texto abaixo três vezes, assumindo um papel diferente em cada uma.

TEXTO:
"Garantimos que nosso software elimina 100% dos erros de digitação da sua
equipe. Resultado imediato desde o primeiro dia, sem necessidade de
treinamento. Satisfação garantida ou seu dinheiro de volta em 90 dias."

Papel 1 — Advogado especializado em direito do consumidor: quais promessas
geram risco jurídico?

Papel 2 — Especialista em vendas B2B: quais objeções esse texto cria no
comprador?

Papel 3 — Editor de conteúdo: o que está mal escrito ou impreciso?

Responda em 3 blocos separados, no máximo 4 bullets cada.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| **Prompts 3 e 4 deram o mesmo resultado** | Provável — os modelos atuais já raciocinam bastante sozinhos. Vire o argumento: *"Olha só, ele acertou nos dois. Mas repara na diferença que importa: no segundo eu consigo conferir a conta. O ganho de CoT hoje é menos acerto e mais auditabilidade."* Esse é um argumento melhor e mais honesto que o original. |
| Few-shot não seguiu o padrão | Adicione: *"Siga o padrão dos exemplos com rigor, inclusive na ordem dos elementos e no uso dos hífens."* E comente: "às vezes precisa insistir — exemplo é sugestão forte, não lei." |
| Os três papéis ficaram parecidos | Peça: *"Onde os três papéis discordam entre si?"* Isso força o contraste e ainda rende um momento bom. |
| A conta do Prompt 3 deu errado | **Ótimo material.** Mostre o erro, rode o Prompt 4 e mostre a correção. É a demonstração perfeita da técnica. |
| Aula passou de 10 min | Corte o Prompt 1 (zero-shot) e vá direto ao few-shot, explicando o contraste em vez de demonstrar. |

---

## Notas de edição

- `⏱ 2:00` — no few-shot, **destaque em cor** nos dois exemplos dentro do prompt,
  para o aluno ver o que mudou entre o Prompt 1 e o 2.
- `⏱ 4:00–6:00` — a comparação sem CoT / com CoT é o pico da aula: **tela
  dividida** com as duas respostas.
- `⏱ 6:00` — nos três papéis, **rótulo em tela** aparecendo junto de cada bloco
  ("ADVOGADO", "VENDAS", "EDITOR").
- `⏱ 7:45` — o resumo das quatro técnicas vira **card fixo**, ideal para o aluno
  printar. Deixe 4 segundos parado.
- **Título sugerido:** "4 técnicas de prompting que resolvem 20% dos casos difíceis"
- **Thumbnail:** as quatro técnicas em quadrantes.
