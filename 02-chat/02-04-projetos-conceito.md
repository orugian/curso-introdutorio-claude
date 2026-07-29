# 02.04 — Projetos: o que são e quando usar

| | |
|---|---|
| **Duração alvo** | 7 min |
| **Slides** | 6 (metade de cima — "O que é" e "Quando usar") |
| **Material base** | `modulos/02-chat/README.md` § 2.3 |
| **Arquivo de vídeo** | `M02-A04-projetos-conceito.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck no **slide 6**
- [ ] Claude aberto, com **pelo menos um Projeto já existente** na conta (não
      precisa ser bonito — é só para a tela de Projetos não estar vazia)
- [ ] ⚠️ Requer plano **Pro ou Max**. Se estiver em conta gratuita, o menu de
      Projetos não aparece.

> **Esta é a única aula conceitual "pura" do módulo.** Sem demo longa. O aluno
> precisa entender *por que* Projetos existem antes de criar um — senão ele cria
> um Projeto e continua repetindo instrução em cada chat.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho — o problema | 0:00 | Slide 6 |
| O que é um Projeto | 1:00 | Slide 6 → tela |
| As duas peças | 2:15 | Tela |
| Projeto vs chat solto | 4:00 | Slide 6 |
| Três exemplos reais | 5:15 | Slide 6 |
| Fecho | 6:20 | Slide 6 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 6]` · **fala literal**

> "Se você aplicou o que a gente viu nas duas últimas aulas, você já esbarrou
> num problema chato.
>
> Você montou um prompt bom. Contexto, tarefa, formato, tom, restrições. Funcionou
> lindamente. Aí no dia seguinte você precisa da mesma coisa — e tem que escrever
> tudo de novo. E de novo. E toda vez que você tem preguiça e escreve a versão
> curta, a resposta piora.
>
> Projetos existem exatamente pra isso. Em sete minutos você vai entender o que
> são, o que colocar dentro, e — mais importante — quando **não** usar."

---

### ⏱ 1:00 — O QUE É UM PROJETO · `[SLIDE 6]` · **fala literal**

> "Um Projeto é um espaço isolado dentro do Claude com duas coisas: instruções
> fixas e uma base de conhecimento.
>
> Instruções fixas são o seu prompt permanente. Tudo que você escreveria toda vez,
> você escreve uma vez só ali — e ele passa a valer em todas as conversas daquele
> Projeto, automaticamente.
>
> Base de conhecimento são os arquivos que ele consulta sempre. Seu manual de
> marca, sua política de trocas, sua tabela de preços, seu glossário.
>
> Junta os dois e você deixa de ter um assistente genérico. Você passa a ter um
> assistente que já sabe onde trabalha."

`[TELA: claude.ai]` — abra a área de Projetos, mostre a lista.

- Mostre que cada Projeto tem suas próprias conversas dentro dele.
- > **Fala literal:**
  > "Repara: as conversas ficam dentro do Projeto. Isso organiza sua cabeça
  > também, não só a do Claude."

---

### ⏱ 2:15 — AS DUAS PEÇAS · `[TELA: destaque]` · **fala livre**

Entre em um Projeto existente e mostre os dois campos, sem preencher nada — a
criação é a próxima aula.

**Instruções customizadas:**
- É onde moram os cinco blocos da aula 02, agora permanentes.
- Regra prática: se você digitou a mesma frase em três conversas diferentes, ela
  pertence às instruções.

**Base de conhecimento:**
- Aceita PDF, DOCX, TXT, Markdown, planilha, código.
- > **Fala literal — o alerta que evita o erro mais comum:**
  > "E aqui vai o aviso que vale o preço da aula: a base de conhecimento é
  > consultada **a cada conversa**. Ela não é um HD. Não é um lugar pra jogar
  > tudo que você tem 'por precaução'.
  >
  > Base enxuta e curada funciona melhor que base gigante. Se você subir
  > quarenta arquivos, você não deixou ele mais inteligente — você deixou o sinal
  > mais fraco no meio do ruído. Suba o que ele **precisa**, não o que você **tem**."

---

### ⏱ 4:00 — PROJETO vs CHAT SOLTO · `[SLIDE 6]` · **fala literal**

Percorra a tabela do slide:

> "Tarefa pontual, que você faz uma vez e nunca mais? Chat normal. Não crie
> Projeto pra isso — você vai acabar com trinta Projetos mortos.
>
> Trabalho recorrente, com o mesmo contexto toda vez? Projeto.
>
> Precisa de instruções fixas? Projeto.
>
> Precisa que ele consulte documentos seus? Projeto, obrigatoriamente.
>
> Conversa exploratória, pensando alto, testando ideia? Chat normal — e aqui tem
> um detalhe: dentro de um Projeto as instruções fixas **puxam** a resposta para
> aquele contexto. Se você quer explorar livre, sai do Projeto."

---

### ⏱ 5:15 — TRÊS EXEMPLOS REAIS · `[SLIDE 6]` · **fala livre**

Três contextos diferentes, 20 segundos cada. Não aprofunde — é para o aluno
enxergar o próprio caso em um deles.

1. **Jurídico — "Revisor de Contratos".** Instruções: sempre apontar cláusula de
   risco, sempre citar o artigo. Base: modelos de contrato aprovados, política
   interna de contratação.
2. **Loja em marketplace — "Minha Loja".** Instruções: nicho, faixa de preço,
   tom da marca, margem mínima. Base: tabela de custos, política de trocas,
   descrições que já performaram bem.
3. **Desenvolvimento — "API de Pagamentos".** Instruções: linguagem, padrões de
   código, o que nunca fazer. Base: documentação da API, exemplos de endpoint.

> **Fala literal:**
> "Três áreas que não têm nada a ver uma com a outra. A estrutura é idêntica:
> quem eu sou, como responder, e o que consultar."

---

### ⏱ 6:20 — FECHO · `[SLIDE 6]` · **fala literal**

> "Resumindo: Projeto é instrução fixa mais base de conhecimento, num espaço
> isolado. Use para trabalho recorrente. Não use para pergunta de uma vez só. E
> mantenha a base enxuta.
>
> Na próxima aula a gente sai da teoria e cria um do zero — instruções, upload de
> arquivo e teste com um documento real. Separa dez minutos, porque essa você vai
> querer fazer junto comigo."

---

## Prompts para copiar e colar

*Esta aula não tem demo de prompt.* Se você quiser um respiro entre os blocos,
este pergunta ao próprio Claude — funciona bem como fecho alternativo:

```
Liste 5 tarefas recorrentes do meu trabalho que fariam sentido virar um
Projeto no Claude, e para cada uma diga o que entraria nas instruções fixas
e o que entraria na base de conhecimento.
Trabalho como [SEU CARGO] em [SEU CONTEXTO].
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| A conta não mostra Projetos | É plano gratuito. Troque para a conta Pro **antes** de gravar. Não dá para demonstrar sem. |
| Não há nenhum Projeto na conta | Crie um vazio chamado "Exemplo" 5 min antes de gravar, só para a lista não aparecer vazia. |
| O nome do recurso mudou na interface | Fale o nome que está na tela. O conceito — instrução fixa + base — não muda. |
| Aula ficou curta demais (< 6 min) | Adicione o prompt acima como demo final. Rende 1 min e fecha bem. |
| Aula ficou longa (> 8 min) | Corte o exemplo 3 (desenvolvimento). Jurídico e loja já cobrem o contraste. |

---

## Notas de edição

- Esta é a aula com **menos tela e mais slide** do módulo. Se ficar monótona,
  compense com movimento: entre no Projeto, role, volte ao slide.
- `⏱ 2:15` — o alerta sobre base enxuta merece **card em tela cheia**:
  *"Base de conhecimento não é HD. É a mesa de trabalho."*
- `⏱ 4:00` — a tabela Projeto vs chat solto entra **linha por linha**,
  sincronizada com a fala.
- `⏱ 5:15` — os três exemplos pedem **ícone/rótulo** distinto cada um, para
  reforçar que são áreas diferentes.
- **Título sugerido:** "Pare de repetir o mesmo prompt: entenda os Projetos"
- **Thumbnail:** um prompt longo repetido 3× com um "✕", e ao lado o ícone de Projeto.
