# 02.09 — Upload e análise de arquivos

| | |
|---|---|
| **Duração alvo** | 9 min |
| **Slides** | 8 |
| **Material base** | `modulos/02-chat/README.md` § 2.5 |
| **Arquivo de vídeo** | `M02-A09-upload-e-analise.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck no **slide 8**
- [ ] [`recursos/vendas-exemplo.csv`](../recursos/vendas-exemplo.csv) baixado na pasta de Downloads
- [ ] **Abra o CSV antes** e leia — você precisa saber o que tem lá dentro para
      reagir bem à análise
- [ ] Um **PDF qualquer não sensível** para o segundo exemplo (um manual público,
      uma nota técnica — nada de contrato ou documento interno)
- [ ] Uma **imagem de gráfico** (print de um gráfico de qualquer relatório
      público) para o exemplo de visão
- [ ] Conversa nova, fora de Projeto
- [ ] Pasta de Downloads **limpa na tela** — o seletor de arquivos vai aparecer no vídeo

⚠️ **Privacidade:** o seletor de arquivos do Windows expõe sua pasta inteira.
Limpe ou crie uma pasta `demo-curso` só com os três arquivos e navegue nela.

**O que tem no CSV:** 52 pedidos de uma loja de acessórios de celular, entre
junho e julho de 2026, nos canais Mercado Livre e Shopee. Há padrões plantados
de propósito: um produto em crescimento, um em queda forte, um de alto volume e
margem baixa, e diferença clara de ticket médio entre os canais.

### 🔑 Gabarito — confira a resposta dele ao vivo

Números conferidos diretamente no arquivo. **Leia antes de gravar.**

| Métrica | Valor correto |
|---------|---------------|
| Pedidos | 52 |
| Receita total | R$ 8.105,20 |
| Ticket médio geral | R$ 155,87 |
| Mercado Livre | 31 pedidos · R$ 6.044,20 · ticket **R$ 194,97** |
| Shopee | 21 pedidos · R$ 2.061,00 · ticket **R$ 98,14** |
| Junho | R$ 3.109,90 · 25 pedidos |
| Julho | R$ 4.995,30 · 27 pedidos |

**Campeão de receita:** Fone Bluetooth TWS Pro — R$ 3.987,90
**Campeão de unidades:** Cabo USB-C 1m — 50 unidades (só R$ 1.285,00 de receita)

> São **produtos diferentes**, de propósito. É exatamente o item 2 do Prompt 1.
> Se ele responder "o campeão é X" sem notar a diferença, você tem um ótimo
> momento de aula: peça a quebra por unidade e por receita.

**Evolução em unidades (junho → julho):**

| Produto | Jun | Jul | Leitura |
|---------|-----|-----|---------|
| Capa Silicone iPhone 14 | 21 | **2** | 🔻 queda de ~90% — é o alerta |
| Fone Bluetooth TWS Pro | 5 | **16** | 🔺 triplicou — é o crescimento |
| Suporte Veicular | 0 | 8 | produto novo, só em julho |
| Cabo USB-C | 23 | 27 | estável, alto volume |
| Película | 7 | 9 | estável |
| Carregador 20W | 5 | 5 | estável |

⚠️ **Nenhum destes números aparece pronto na planilha** — todos exigem soma e
agrupamento. É por isso que servem para testar se ele calculou ou chutou.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 8 |
| Os formatos | 0:40 | Slide 8 |
| Demo 1 — planilha | 1:40 | Tela |
| A pergunta que muda tudo | 4:15 | Tela |
| Demo 2 — PDF | 5:45 | Tela |
| Demo 3 — imagem | 7:00 | Tela |
| Limites e cuidados | 7:50 | Slide 8 |
| Fecho | 8:30 | Slide 8 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 8]` · **fala literal**

> "Todo dado que a gente usou até agora nesse módulo foi inventado. Serviu pra
> aprender o mecanismo.
>
> Nessa aula acabou a brincadeira: eu vou subir uma planilha de vendas de verdade,
> um PDF e uma imagem, e a gente vai ver o Claude ler os três.
>
> E no meio do caminho eu vou te mostrar a pergunta que separa quem usa isso
> direito de quem só pede 'resuma esse arquivo'."

---

### ⏱ 0:40 — OS FORMATOS · `[SLIDE 8]` · **fala literal**

> "Rápido, o que entra:
>
> **Documento** — PDF, Word, texto puro, Markdown.
> **Planilha** — Excel e CSV.
> **Imagem** — foto, print, gráfico, diagrama. Ele enxerga de verdade.
> **Código** — arquivo de qualquer linguagem.
>
> Dá pra subir mais de um de uma vez e pedir comparação entre eles. E o mesmo
> arquivo pode ir pra conversa avulsa, que vale só ali, ou pra base de
> conhecimento de um Projeto, que vale sempre — a diferença que a gente viu na
> aula 04."

---

### ⏱ 1:40 — DEMO 1: PLANILHA · `[TELA: claude.ai]` · **fala livre**

Anexe o `vendas-exemplo.csv` e cole o **Prompt 1**.

Antes de enviar:
> **Fala literal:**
> "Repara no prompt: eu não pedi 'analise essa planilha'. Eu disse quem eu sou, o
> que a planilha é, e exatamente quais quatro perguntas eu quero respondidas. Os
> cinco blocos da aula 02, aplicados a arquivo."

Quando responder, **confira em voz alta contra o que você viu no CSV**:
- Ele achou o produto campeão?
- Ele achou a queda?
- Os números batem?

> **Fala literal — o hábito que precisa ficar:**
> "E olha o que eu estou fazendo agora, que é a parte que quase ninguém faz: eu
> estou **conferindo**. Eu abri essa planilha antes. Eu sei o que tem lá.
>
> Ele acertou aqui. Mas se ele errasse, e ele pode errar, quem ia perceber era eu
> — não ele."

---

### ⏱ 4:15 — A PERGUNTA QUE MUDA TUDO · `[TELA]` · **fala livre**

Cole o **Prompt 2**.

> **Fala literal — o setup:**
> "Agora o pulo do gato. Em vez de perguntar 'o que aconteceu', que é olhar pra
> trás, eu vou perguntar 'o que eu faço com isso' — e, principalmente, vou pedir
> pra ele me dizer **o que ele não consegue saber com esses dados**."

Quando responder:
- Mostre que ele aponta as limitações (não tem custo, não tem tráfego, não tem
  devolução, o recorte é curto).

> **Fala literal:**
> "Isso vale ouro. Ele acabou de te dizer quais colunas faltam na sua planilha
> pra você tomar decisão melhor. Você pediu análise e recebeu de brinde um
> diagnóstico do seu próprio dado."

---

### ⏱ 5:45 — DEMO 2: PDF · `[TELA]` · **fala livre**

Anexe o PDF e cole o **Prompt 3**.

- Mostre que ele localiza informação específica, não só resume.
- Peça a página/trecho de onde tirou.

> **Fala literal:**
> "Pedir a origem da informação deveria ser automático pra você. Sempre que a
> resposta vem de um documento, pergunta de onde saiu. Leva dois segundos e te
> dá o que conferir."

---

### ⏱ 7:00 — DEMO 3: IMAGEM · `[TELA]` · **fala livre**

Anexe a imagem do gráfico e cole o **Prompt 4**.

- Mostre que ele lê os eixos, os valores e a tendência.
- Usos: print de relatório que você não tem em planilha, foto de quadro branco,
  captura de tela de sistema que não exporta.

> **Fala literal:**
> "Isso resolve um problema real e chato: o dado que existe, mas não está em
> formato de dado. Print de relatório, foto de whiteboard, tela de sistema
> legado que não exporta nada. Vira análise."

---

### ⏱ 7:50 — LIMITES E CUIDADOS · `[SLIDE 8]` · **fala literal**

> "Três coisas antes de fechar.
>
> **Uma: arquivo grande consome contexto.** Planilha de cinquenta mil linhas não
> é o melhor uso disso. Filtra antes, sobe o recorte que interessa.
>
> **Duas: PDF escaneado é imagem, não texto.** Se o documento é um scan torto de
> fotocópia, a leitura piora. Vale conferir com mais rigor.
>
> **Três, e essa é a séria: pensa antes no que você está subindo.** Dado de
> cliente, informação sigilosa, documento sob acordo de confidencialidade — isso
> é decisão da sua empresa, não sua, e as regras mudam conforme o plano e o
> contrato. Se tiver dúvida, pergunta pra quem cuida disso aí antes de anexar."

---

### ⏱ 8:30 — FECHO · `[SLIDE 8]` · **fala literal**

> "Planilha, documento e imagem — os três lidos, os três analisados.
>
> E o que fica: prompt específico em vez de 'resume aí', pergunta o que ele
> **não** consegue saber, e confere o que ele afirmou.
>
> Falta uma aula pra fechar o módulo. E ela é a que eu mais gosto, porque é a que
> vai te poupar mais tempo: os erros que todo mundo comete com IA, e o que fazer
> quando ele te responde com toda a confiança do mundo uma coisa que não é
> verdade. Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — análise da planilha**

```
Sou o responsável por uma loja de acessórios para celular que vende no
Mercado Livre e na Shopee. A planilha anexa tem os pedidos dos últimos
dois meses.

Analise e responda em 4 blocos curtos:

1. Panorama: receita total, número de pedidos, ticket médio — no total e
   quebrado por canal.
2. Campeão: qual produto mais gerou receita e qual mais vendeu em unidades
   (se forem diferentes, explique por quê).
3. Alerta: qual produto está caindo de um mês para o outro, e quanto.
4. Diferença entre canais: o que muda entre Mercado Livre e Shopee.

Formato: tabela onde couber, texto curto onde não couber.
Valores em R$ com 2 casas decimais.
```

**Prompt 2 — a pergunta que muda tudo**

```
Agora vire o jogo.

a) Com base só nesses dados, quais são as 3 ações que você recomendaria
   para o próximo mês? Ordene por impacto esperado.

b) Igualmente importante: o que você NÃO consegue afirmar com esses dados?
   Liste quais informações estão faltando para eu tomar uma decisão melhor,
   e diga qual coluna eu teria que passar a registrar para cada uma.
```

**Prompt 3 — leitura de PDF**

```
Do documento anexo, extraia:
1. Do que ele trata, em 2 linhas
2. Os 5 pontos mais relevantes para quem precisa aplicar isso na prática
3. Qualquer prazo, número ou valor citado

Para cada item, indique de qual página ou seção você tirou a informação.
Se algo não estiver no documento, diga que não está — não complete.
```

**Prompt 4 — leitura de imagem**

```
Descreva o gráfico da imagem anexa: o que ele mede, qual o período,
quais os valores aproximados de cada ponto e qual a tendência.

Depois me diga: qual a informação mais importante desse gráfico e o que
alguém que olhasse rápido demais poderia interpretar errado?
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| Ele errou um número da planilha | **O melhor momento possível da aula.** Mostre o erro, mostre a conferência, e diga: *"É por isso que eu abro o arquivo antes. Ele lê muito bem e erra às vezes — as duas coisas são verdade."* |
| A análise veio rasa | Peça o recorte específico: *"Me dá a receita mês a mês por canal, em tabela."* Aproveite para reforçar: pedido específico gera resposta específica. |
| O upload falhou | Confira o tamanho e o formato. Tenha o **mesmo CSV em `.xlsx`** como reserva. |
| O PDF é escaneado e ele não leu bem | **Use a favor** — é exatamente o limite que você ia explicar no bloco de ⏱ 7:50. Antecipe o argumento. |
| Você não tem imagem de gráfico | Tire um print de qualquer gráfico do dashboard da aula 07 e use. Funciona e ainda dá continuidade. |
| Passou de 10 min | Corte a demo de PDF (⏱ 5:45). Planilha e imagem são as mais fortes. |

---

## Notas de edição

- ⚠️ **Revisar o vídeo inteiro procurando vazamento de dado.** Esta é a aula com
  mais risco: seletor de arquivos, nomes de arquivo, conteúdo de documento.
  Borre o que precisar.
- `⏱ 1:40` — o gesto de **arrastar o arquivo** para o chat merece aparecer
  inteiro. É a mecânica que o aluno vai repetir.
- `⏱ 3:20` — a conferência dos números pede **destaque simultâneo**: a resposta
  do Claude de um lado, a planilha aberta do outro. É o hábito que a aula ensina.
- `⏱ 4:15` — a fala "o que você NÃO consegue afirmar" vira **card em tela cheia**.
  É o insight mais original do módulo.
- `⏱ 7:50` — os três limites entram como **três bullets animados**.
- **Título sugerido:** "Suba planilha, PDF e imagem: o Claude lendo dado de verdade"
- **Thumbnail:** ícones de CSV, PDF e imagem convergindo para a tela do Claude.
