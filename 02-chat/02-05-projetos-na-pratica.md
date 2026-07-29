# 02.05 — Criando um Projeto na prática

| | |
|---|---|
| **Duração alvo** | 10 min |
| **Slides** | 5 (bloco de instruções) → 11 → 12 |
| **Material base** | `modulos/02-chat/README.md` § 2.3 + "Modelo de Projeto" |
| **Arquivo de vídeo** | `M02-A05-projetos-na-pratica.mp4` |

> **A aula mais longa do módulo, e a mais importante.** É aqui que o aluno sai
> com algo construído. Não corra.

---

## Preparação (antes do REC)

- [ ] Deck no **slide 5**
- [ ] Plano **Pro ou Max** ativo
- [ ] **`guia-de-estilo-tiops.pdf` já exportado** e na pasta de Downloads
      (fonte: [`recursos/guia-de-estilo-tiops.md`](../recursos/guia-de-estilo-tiops.md))
- [ ] Um **texto ruim de propósito** para o teste final — use o Texto de Teste
      no fim deste roteiro, salvo em bloco de notas
- [ ] Instruções customizadas copiadas (você vai colar, não digitar)
- [ ] Nenhum Projeto chamado "Revisor de Conteúdo" na conta — se existir, apague
      antes, senão a criação fica confusa na tela

⚠️ **Não apague este Projeto depois de gravar.** Ele é reutilizado na aula 02.10.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 5 |
| Criando o Projeto | 0:40 | Tela |
| Escrevendo as instruções | 1:40 | Slide 5 → tela |
| Base de conhecimento | 4:30 | Slide 12 → tela |
| Teste real | 6:15 | Tela |
| O ajuste fino | 8:15 | Tela |
| Fecho | 9:15 | Slide 5 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 5]` · **fala literal**

> "Aula prática. Nos próximos dez minutos a gente cria um Projeto do zero,
> completo: instruções fixas, upload de documento na base de conhecimento e teste
> com um texto de verdade.
>
> O Projeto vai se chamar Revisor de Conteúdo, e no final dele você joga qualquer
> documento lá dentro e recebe uma revisão no padrão da sua empresa — sem
> explicar nada, toda vez.
>
> Abre o Claude do seu lado e faz comigo. Essa aqui não funciona só assistindo."

---

### ⏱ 0:40 — CRIANDO O PROJETO · `[TELA: claude.ai]` · **fala livre**

- Área de Projetos → criar novo.
- **Nome:** `Revisor de Conteúdo`
- **Descrição:** `Revisa documentos corporativos no padrão de redação da empresa`

> **Fala literal — sobre a descrição:**
> "A descrição é pra você, não pra ele. Daqui a seis meses, com doze Projetos na
> conta, ela é o que te faz lembrar pra que serve esse aqui. Escreve como se
> fosse pra outra pessoa."

---

### ⏱ 1:40 — ESCREVENDO AS INSTRUÇÕES · `[SLIDE 5]` → `[TELA]` · **fala livre**

Mostre o slide 5 por ~15s, depois vá para a tela e **cole** as instruções
(Instruções abaixo). Enquanto cola, dissecar linha a linha:

1. **A definição de papel** — "Você é um revisor sênior de conteúdo corporativo."
   > Aquele role prompting da aula 03, agora permanente.

2. **O formato fixo** — sempre 3 seções: Problemas → Sugestão → Nota.
   > "Formato fixo é o que faz a saída ser comparável. Você consegue olhar dez
   > revisões e bater o olho, porque todas têm a mesma forma."

3. **A regra anti-bajulação** — "Se o texto estiver bom, diga que está bom."
   > **Fala literal — o ponto alto do bloco:**
   > "Essa linha aqui é a mais importante do Projeto inteiro. Modelo de linguagem
   > tem tendência a te dar o que você pediu. Você pediu problemas? Ele acha
   > problemas. Mesmo que não tenha.
   >
   > Escrever explicitamente 'não invente problema' muda o comportamento. Sempre
   > que você criar um Projeto avaliativo, coloca uma linha dessas."

4. **A restrição de tom** — não transformar casual em formal sem motivo.
   > "Restrições, de novo. Elas valem tanto aqui quanto no prompt avulso."

---

### ⏱ 4:30 — BASE DE CONHECIMENTO · `[SLIDE 12]` → `[TELA]` · **fala livre**

Mostre o slide 12 (a lista dos três arquivos) e depois faça o upload real do
`guia-de-estilo-tiops.pdf`.

- Arraste o arquivo para a área de base de conhecimento.
- Mostre o arquivo aparecendo na lista, com o indicador de espaço ocupado.

> **Fala literal:**
> "Um arquivo. Não três, não dez. Eu subi o manual de redação porque é ele que
> define o que 'certo' significa nessa empresa.
>
> Se eu subisse junto o organograma, o plano de metas e a apresentação
> institucional, eu não teria melhorado a revisão — eu teria diluído o manual no
> meio de coisa que não tem nada a ver com revisar texto."

Aponte o indicador de capacidade:
- Existe um limite de tamanho da base, e ele é visível ali.
- Regra: quando encher, a resposta não é aumentar o plano. É **curar** o que está lá.

---

### ⏱ 6:15 — TESTE REAL · `[TELA: claude.ai]` · **fala livre**

Abra uma conversa **dentro** do Projeto. Cole o **Texto de Teste** com o pedido
mínimo: `Revise este comunicado.`

> **Fala literal — antes de enviar:**
> "Presta atenção no tamanho do que eu vou pedir. Duas palavras: 'revise este'.
> Sem contexto, sem formato, sem tom. Tudo isso já está no Projeto."

Quando responder, confira em voz alta, item por item:
- [ ] Veio nas três seções? (Problemas → Sugestão → Nota)
- [ ] Ele citou o manual da base de conhecimento?
- [ ] O tom da crítica está construtivo, como pedido?

> **Fala literal:**
> "É esse o ganho. O prompt que eu escrevi tem duas palavras e a resposta tem a
> qualidade de um prompt de vinte linhas. Multiplica isso por todo dia útil do ano."

---

### ⏱ 8:15 — O AJUSTE FINO · `[TELA: destaque]` · **fala livre**

> **Fala literal — o hábito que o aluno precisa levar:**
> "E agora a parte que quase ninguém faz: Projeto não nasce pronto. Ele é
> calibrado."

Volte às instruções e **adicione uma linha ao vivo**, à frente do aluno:

```
- Ao final, liste em uma linha qual regra do guia de estilo foi mais violada.
```

- Salve, volte à conversa, rode o mesmo teste de novo.
- Mostre a resposta já obedecendo a regra nova.

> **Fala literal:**
> "Rodou, não gostou de alguma coisa, volta e escreve a regra. É assim que
> funciona. Meus Projetos que mais uso foram ajustados umas dez vezes cada. Os que
> eu criei e nunca mais toquei são justamente os que eu não uso."

---

### ⏱ 9:15 — FECHO · `[SLIDE 5]` · **fala literal**

> "Pronto: Projeto criado, instruções escritas, documento na base, testado e
> ajustado.
>
> Seu exercício é criar um Projeto do **seu** trabalho. Não copia o meu — o meu
> revisa texto corporativo, e talvez você nem revise texto. Pensa numa coisa que
> você faz toda semana explicando o mesmo contexto, e transforma aquilo num
> Projeto.
>
> Na próxima aula a gente muda de assunto e vai pra parte que impressiona: fazer
> o Claude gerar coisas que **funcionam** na tela — dashboards, páginas,
> diagramas. Chama Artifacts. Te vejo lá."

---

## Instruções customizadas (para colar no Projeto)

```
Você é um revisor sênior de conteúdo corporativo. Seu trabalho é revisar
documentos, e-mails, apresentações e relatórios.

Regras:
- Sempre responda em 3 seções: Problemas → Sugestão → Nota
- Tom profissional e construtivo
- Se o texto estiver bom, diga que está bom (não invente problemas)
- Priorize clareza: se uma frase pode ser mais curta, sugira como
- Respeite o tom original (não transforme casual em formal sem motivo)
- Use o guia de estilo da base de conhecimento como referência de padrão
- A nota vai de 1 a 10 e sempre vem com uma justificativa de no máximo 2 linhas
```

**Linha adicionada no ajuste fino (⏱ 8:15):**

```
- Ao final, liste em uma linha qual regra do guia de estilo foi mais violada.
```

---

## Texto de Teste (para colar na conversa)

```
Revise este comunicado.

---

Prezados colaboradores,

Vimos por meio desta informar que a partir do dia 15 do corrente mês
estaremos implementando de forma gradual e progressiva um novo procedimento
no que tange ao processo de solicitação de férias, o qual passará a ser
realizado exclusivamente através do sistema, sendo certo que solicitações
realizadas por e-mail não mais serão consideradas válidas a partir da
referida data.

Salientamos que é de suma importância que todos tomem ciência da presente
comunicação, tendo em vista que o não cumprimento poderá acarretar em
atrasos no processamento das respectivas solicitações.

Atenciosamente,
Departamento de Recursos Humanos
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| O upload do PDF falhou | Tenha o **mesmo conteúdo em `.md` ou `.txt`** na pasta como reserva. Suba esse e comente: "aceita vários formatos". |
| Ele não seguiu as 3 seções | **Mostre e corrija ao vivo** — é o melhor conteúdo possível para o bloco de ajuste fino. Reforce a instrução com "SEMPRE responda em exatamente 3 seções, nesta ordem" e rode de novo. |
| Ele não citou o guia de estilo | Pergunte na conversa: *"Qual regra do guia de estilo esse texto violou?"* Se ele responder citando o documento, a base está funcionando — mostre isso. |
| O Projeto não salvou as instruções | Recarregue a página e confira antes de seguir. Se persistir, marque `[CORTE]` e refaça o bloco. |
| Passou de 11 min | Corte o bloco de ajuste fino (⏱ 8:15) e transforme em recado no fecho: "volte e ajuste as instruções sempre que a resposta não te agradar". |
| A resposta veio boa demais e sem críticas | Perfeito para demonstrar a regra anti-bajulação: *"Ele não inventou problema onde não tem. É o que a instrução pediu."* |

---

## Notas de edição

- **Aula mais longa do módulo.** Vale colocar **capítulos** na plataforma:
  Criando / Instruções / Base / Teste / Ajuste.
- `⏱ 1:40–4:30` — quando cada linha das instruções for citada, **destaque a
  linha correspondente** na tela. Sem isso o aluno perde o fio.
- `⏱ 3:00` — a fala sobre "não invente problemas" pede **card em tela cheia**.
  É o insight mais transferível da aula.
- `⏱ 4:30` — o upload precisa aparecer **de verdade** (arrastar → aparecer na
  lista). Não corte esse trecho, ele dá confiança ao aluno.
- `⏱ 6:15` — deixe o prompt de duas palavras **grande na tela** por 2s antes de
  enviar. O contraste com a resposta é o argumento da aula.
- `⏱ 8:15` — na edição ao vivo das instruções, use **antes/depois** da resposta.
- **Título sugerido:** "Criando seu primeiro Projeto no Claude (do zero ao teste)"
- **Thumbnail:** tela do Projeto com instruções + arquivo na base.
