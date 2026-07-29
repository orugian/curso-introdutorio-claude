# 02.10 — Boas práticas, armadilhas e alucinação

| | |
|---|---|
| **Duração alvo** | 9 min |
| **Slides** | 9 → 10 (exercícios) |
| **Material base** | `modulos/02-chat/README.md` § 2.6 |
| **Arquivo de vídeo** | `M02-A10-boas-praticas.mp4` |

> **Aula de fechamento do módulo.** Consolida tudo e entrega os exercícios.
> É a que o aluno mais revê depois — vale caprichar na densidade.

---

## Preparação (antes do REC)

- [ ] Deck no **slide 9**
- [ ] Conversa nova para a demo de alucinação
- [ ] Projeto **"Revisor de Conteúdo" ainda existindo** na conta (aula 02.05)
- [ ] Prompts 1 a 3 copiados
- [ ] ⚠️ **Teste o Prompt 1 antes de gravar.** O comportamento de alucinação
      varia — você precisa saber o que vai aparecer na sua tela hoje.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 9 |
| Os 6 hábitos que funcionam | 0:40 | Slide 9 |
| As 5 armadilhas | 3:00 | Slide 9 |
| Alucinação — demonstração | 4:45 | Tela |
| Como se proteger | 6:45 | Slide 9 |
| Exercícios do módulo | 7:45 | Slide 10 |
| Fecho do módulo | 8:30 | Slide 10 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 9]` · **fala literal**

> "Última aula do módulo. E ela é diferente das outras: aqui não tem recurso
> novo. Tem o que ninguém te conta até você já ter quebrado a cara sozinho.
>
> Seis hábitos que funcionam, cinco armadilhas que pegam todo mundo, e no meio
> disso eu vou fazer o Claude errar na sua frente — de propósito — pra você ver
> exatamente com que cara o erro chega."

---

### ⏱ 0:40 — OS 6 HÁBITOS · `[SLIDE 9]` · **fala literal**

Ritmo firme, ~20 segundos cada. O aluno já viu tudo isso no módulo — aqui é
consolidação, não ensino.

> "**Um: seja específico.** 'Melhore isso' não é pedido. 'Reescreva com tom formal
> em três parágrafos, cortando o jargão' é pedido. Quanto mais específico, menos
> rodada.
>
> **Dois: dê exemplo.** Sempre que descrever o formato ficar mais difícil que
> mostrá-lo, mostre. É o few-shot da aula 03.
>
> **Três: divida tarefa grande.** Um pedido com sete entregas dentro vira sete
> respostas medianas. Um pedido por vez vira sete respostas boas.
>
> **Quatro: deixe ele perguntar.** Esse é o mais subutilizado de todos. Terminar
> o prompt com 'me faça as perguntas que faltam antes de responder' muda o jogo
> em tarefa complexa. Ele pergunta o que você esqueceu de contar.
>
> **Cinco: use Projetos.** Se você está repetindo contexto, você está perdendo
> tempo. Aula 04 e 05.
>
> **Seis: itere sempre.** Primeira versão é rascunho. Sempre. Sem exceção."

---

### ⏱ 3:00 — AS 5 ARMADILHAS · `[SLIDE 9]` · **fala literal**

> "Agora o outro lado.
>
> **Pergunta aberta demais.** 'Me ajuda com tudo' devolve nada. Você já viu isso
> na aula 02.
>
> **Achar que ele te conhece.** Ele não sabe o seu cargo, sua empresa, seu
> cliente, seu produto. Tudo que ele sabe é o que está escrito ali. Toda vez que
> a resposta vier genérica, a pergunta é: o que eu deixei de contar?
>
> **Confiar sem conferir.** Vamos falar disso em um minuto.
>
> **Ignorar o tamanho da conversa.** Conversa muito longa começa a perder o começo.
> Se você está há duas horas no mesmo chat e ele passou a esquecer coisa que você
> disse, não insista — abre uma conversa nova e recoloca o essencial.
>
> **Entupir a base de conhecimento.** Quarenta arquivos não deixam ele mais
> inteligente. Deixam o sinal mais fraco."

---

### ⏱ 4:45 — ALUCINAÇÃO · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1** — pede dado específico e verificável, do tipo que costuma
sair errado ou desatualizado.

> **Fala literal — o setup:**
> "Presta atenção não no que ele vai responder. Presta atenção em **como** ele vai
> responder."

Quando responder:
- Se veio com número/afirmação categórica: mostre e questione.
- Se veio com ressalva ("não tenho como confirmar"): **isso também é ótimo** —
  mostre que ressalva é o comportamento correto.

> **Fala literal — a definição:**
> "Alucinação é isso: ele produzir uma informação que soa perfeitamente
> plausível e não é verdadeira.
>
> E aqui está o ponto que eu preciso que você entenda: ele **não está mentindo**.
> Mentir exige saber a verdade e escolher outra coisa. Ele não sabe. Ele está
> completando o padrão mais provável — e às vezes o padrão mais provável não é o
> fato.
>
> Por isso o erro não vem com cara de erro. Vem com a mesma fluência, a mesma
> segurança e a mesma formatação bonita da resposta certa. Não existe sinal
> visual. Essa é a parte perigosa."

Agora cole o **Prompt 2** — pedindo o nível de confiança:

- Mostre ele separando o que é sólido do que é estimativa.

> **Fala literal:**
> "Olha que simples. Eu pedi pra ele marcar o que é certeza e o que é estimativa,
> e ele marcou. Ele **consegue** sinalizar. Ele só não faz por padrão, porque
> você não pediu."

---

### ⏱ 6:45 — COMO SE PROTEGER · `[SLIDE 9]` · **fala literal**

> "Quatro defesas, em ordem de esforço:
>
> **Uma: peça a origem.** 'De onde veio essa informação?' Se ele não souber dizer,
> já é o sinal.
>
> **Duas: peça o nível de confiança.** Foi o que a gente acabou de fazer.
>
> **Três: dê a fonte você.** Anexa o documento, cola o dado. Ele lendo o seu
> arquivo erra muito menos do que ele lembrando de memória. É a aula 09 inteira.
>
> **Quatro, e essa é a regra que fecha o módulo:** número, data, nome próprio,
> citação e valor legal — **sempre confere**. Sempre. Não importa quão certo
> pareceu.
>
> Escreve isso: quanto mais específica e verificável a informação, mais rigor
> você aplica. Texto, estrutura e ideia ele faz muito bem sozinho. Fato pontual
> você confere."

---

### ⏱ 7:45 — EXERCÍCIOS · `[SLIDE 10]` · **fala livre**

Percorra a lista do slide 10, dando o **porquê** de cada um — a lista sozinha o
aluno lê:

1. **5 prompts com os cinco blocos** → fixa a estrutura por repetição.
2. **Um Projeto seu** → o de maior retorno. Que seja do trabalho de verdade.
3. **Um Artifact iterado 3 vezes** → o método importa mais que o resultado.
4. **Publicar e compartilhar** → só entende quando manda pra alguém e a pessoa abre.
5. **Subir um arquivo e extrair informação** → e conferir o que ele afirmou.
6. **Chain of Thought num problema seu** → escolha um que envolva conta ou critério.
7. **O mesmo conteúdo em 3 personas** → o exercício que mais ensina sobre tom.

> **Fala literal:**
> "Se você só tiver tempo pra um, faz o dois. O Projeto é o que continua rendendo
> depois que o curso acaba."

---

### ⏱ 8:30 — FECHO DO MÓDULO · `[SLIDE 10]` · **fala literal**

> "Fim do módulo de Chat. Recapitulando o que você tem agora: a estrutura de
> cinco blocos, quatro técnicas de prompting, Projetos com base de conhecimento,
> Artifacts publicáveis, análise de arquivo e o rigor pra não engolir o que ele
> te fala.
>
> Isso já é mais do que a maioria das pessoas que usa IA todo dia.
>
> Só que tudo que a gente fez até aqui tem uma limitação: **você precisa estar na
> frente do computador**. Você pede, ele responde. Você pede de novo.
>
> No próximo módulo isso muda. A gente entra no Cowork, e a pergunta passa a ser
> outra: e se ele fizesse sozinho, no horário certo, sem você pedir? Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — provocando o limite**

```
Quais foram as 3 mudanças mais recentes nas regras de comissão do
Mercado Livre para vendedores no Brasil? Para cada uma, informe a data
em que entrou em vigor e o percentual antes e depois.
```

*(Pergunta deliberadamente específica, verificável e sensível a data — o tipo
que expõe tanto desatualização quanto alucinação. Substitua pelo domínio que
você conhece bem, para conseguir avaliar a resposta ao vivo.)*

**Prompt 2 — pedindo nível de confiança**

```
Refaça a resposta anterior classificando cada afirmação em três níveis:

[ALTA] — tenho confiança de que é verdade
[MÉDIA] — é provável, mas eu não confirmaria sem checar
[BAIXA] — é estimativa ou inferência minha

E ao final, liste explicitamente o que você NÃO sabe sobre esse assunto
e onde eu deveria verificar.
```

**Prompt 3 — o hábito de deixar ele perguntar** *(opcional, se sobrar tempo)*

```
Preciso montar um plano de comunicação para uma mudança interna na empresa.

Antes de escrever qualquer coisa, me faça as 5 perguntas cujas respostas
mais mudariam o plano. Não responda nada além das perguntas.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| **Ele não alucinou — respondeu com ressalvas corretas** | Cenário provável e **totalmente aproveitável**. Diga: *"Olha o comportamento certo: ele avisou que não tem como confirmar. É isso que você quer ver. E é justamente por isso que a resposta sem ressalva merece atenção."* O ponto da aula se mantém. |
| Ele alucinou feio | Ouro. Mostre com calma, aponte a fluência da resposta errada e siga direto para o Prompt 2. |
| Você não sabe avaliar se a resposta está certa | **Troque a pergunta antes de gravar** por algo do seu domínio, onde você consiga julgar ao vivo. Não demonstre alucinação num assunto que você não domina. |
| O Prompt 2 não separou os níveis | Reforce: *"Marque cada afirmação individualmente com a etiqueta."* Se não obedecer, comente que instrução de formato às vezes exige insistência — e isso também é aprendizado. |
| Passou de 10 min | Corte o Prompt 3 e reduza os exercícios (⏱ 7:45) a "estão listados abaixo do vídeo, e o mais importante é o número 2". |

---

## Notas de edição

- **Aula mais "de slide" do módulo.** Compense com ritmo: os hábitos e armadilhas
  pedem **animação item a item**, nunca lista parada.
- `⏱ 0:40` e `⏱ 3:00` — considere **numeração grande na tela** (1 de 6, 2 de 6…).
  Ajuda o aluno a se localizar e melhora retenção.
- `⏱ 5:15` — a definição de alucinação ("ele não está mentindo — ele está
  completando um padrão") merece **card em tela cheia**. É o conceito mais citado
  do módulo inteiro.
- `⏱ 6:45` — as quatro defesas viram **card final**, o que o aluno vai printar.
  Deixe 5 segundos parado.
- `⏱ 8:30` — o fecho do módulo pede **recapitulação visual**: os 6 temas do
  módulo aparecendo em sequência rápida durante a fala.
- O gancho para o Cowork ("e se ele fizesse sozinho?") é a ponte para o próximo
  módulo. **Não corte.**
- **Título sugerido:** "As armadilhas da IA: o que fazer quando o Claude erra com confiança"
- **Thumbnail:** uma resposta bonita e bem formatada com um "?" grande em cima.
