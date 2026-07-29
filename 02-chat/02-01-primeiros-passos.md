# 02.01 — Primeiros passos no Claude

| | |
|---|---|
| **Duração alvo** | 8 min |
| **Slides** | 1 (título) → 2 |
| **Material base** | `modulos/02-chat/README.md` § 2.1 |
| **Arquivo de vídeo** | `M02-A01-primeiros-passos.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck `02-chat.html` aberto em tela cheia no **slide 1**
- [ ] Janela do navegador limpa, `claude.ai` aberto e **deslogado** em uma aba
- [ ] Segunda aba com `claude.ai` **logado**, conversa nova, histórico lateral sem títulos sensíveis
- [ ] Página de planos (`claude.ai/settings/billing` ou a página pública de pricing) aberta em terceira aba
- [ ] Notificações desligadas

⚠️ **Confira no dia:** nomes de plano e de modelo mudam. Abra a página de planos
antes de gravar e fale o que estiver lá.

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 1 |
| Onde acessar e os planos | 0:30 | Slide 2 → tela |
| Tour da interface | 2:30 | Tela |
| Primeira mensagem | 5:00 | Tela |
| O que ele faz e o que não faz | 6:30 | Slide 2 |
| Fecho | 7:30 | Slide 2 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 1]` · **fala literal**

> "Se você já usou o Claude e teve a sensação de que ele respondeu meio genérico,
> meio raso — o problema quase nunca é o modelo. É que ninguém nunca mostrou como
> a ferramenta funciona por dentro.
>
> Nesse módulo a gente resolve isso. E nos próximos oito minutos você vai entender
> a interface inteira: onde fica cada coisa, o que muda entre os planos, e o que
> o Claude consegue e o que ele não consegue fazer. Vamos começar."

---

### ⏱ 0:30 — ONDE ACESSAR E OS PLANOS · `[SLIDE 2]` · **fala livre**

- O endereço é **claude.ai**. Funciona em qualquer navegador, sem instalar nada.
- Existe também aplicativo de desktop e de celular — mesma conta, mesmas conversas.
- Criar conta: e-mail ou login social, leva menos de um minuto.

`[TELA: página de planos]`

- **Free** — dá para conhecer a ferramenta. Tem limite de mensagens por período e
  fica sem alguns recursos, entre eles os Projetos, que a gente vê na aula 04.
- **Pro** — o plano de quem usa no trabalho. Libera Projetos, limites bem maiores
  e acesso aos modelos mais capazes.
- **Max** — mesma coisa do Pro com um teto de uso muito mais alto. Faz sentido
  para quem passa o dia dentro da ferramenta.
- **Team e Enterprise** — quando a empresa inteira usa: cobrança única,
  administração de usuários e controles de dados.

> **Fala literal — recomendação:**
> "Para acompanhar esse curso inteiro, o Pro já resolve. Os únicos momentos em
> que o plano gratuito vai te travar são os Projetos e o volume de mensagens
> quando a gente entrar nos exercícios mais longos."

⚠️ **Sobre limite:** não prometa número exato de mensagens. Diga "tem limite por
janela de tempo e ele varia" — os números mudam.

---

### ⏱ 2:30 — TOUR DA INTERFACE · `[TELA: claude.ai]` · **fala livre**

Percorra na ordem, apontando cada área. Não corra: é o mapa mental do aluno.

1. **Campo central de mensagem** — onde tudo acontece. Aponte o clipe de anexo
   (arquivos) e o botão de enviar.
2. **Barra lateral esquerda** — histórico de conversas. Toda conversa fica salva
   e pesquisável. Mostre a busca.
3. **Botão de nova conversa** — e o ponto importante: `[TELA: destaque]`
   > **Fala literal:**
   > "Cada conversa é um contexto separado. O Claude não leva o que foi dito
   > numa conversa para a outra. Isso vai importar muito daqui a duas aulas."
4. **Projetos** — mostre onde fica, mas **não entre**.
   > "Isso aqui é o recurso que mais muda a vida de quem usa o Claude no
   > trabalho, e ele tem duas aulas só pra ele. Deixa quieto por enquanto."
5. **Seletor de modelo** — mostre onde troca.
   - Explique o trade-off, não os nomes: modelo mais capaz = melhor raciocínio,
     mais lento; modelo mais rápido = tarefa simples, resposta imediata.
   - > "Na dúvida, deixa no padrão. Ele é o equilíbrio para o dia a dia."
6. **Configurações** — idioma, aparência e, principalmente, as
   **preferências/instruções gerais**, que valem para todas as conversas.

---

### ⏱ 5:00 — PRIMEIRA MENSAGEM · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1**. Enquanto ele responde, narre — não fique em silêncio:

- Repare que ele não devolve uma parede de texto: ele estrutura.
- A resposta aparece aos poucos, você já pode ler enquanto ele escreve.
- Se ficar ruim, dá para parar a geração no meio.

Quando terminar, mostre os controles abaixo da resposta:
- **Copiar**, **regerar** e — o mais útil — **editar a sua mensagem** e mandar de novo.

> **Fala literal:**
> "Guarda esse botão de editar. Conversar bem com o Claude é muito mais reescrever
> o seu pedido do que discutir com a resposta dele."

---

### ⏱ 6:30 — O QUE ELE FAZ E O QUE NÃO FAZ · `[SLIDE 2]` · **fala literal**

> "Antes de fechar, três limites que evitam frustração.
>
> Primeiro: o conhecimento dele tem uma data de corte. Ele não sabe o que
> aconteceu ontem, a não ser que você conte, anexe um arquivo ou ele busque na web.
>
> Segundo: ele erra com confiança. Ele pode inventar um número, uma citação, um
> nome de função — e falar com a maior tranquilidade. Isso tem nome, chama
> alucinação, e a gente volta nesse assunto na última aula do módulo.
>
> Terceiro: ele não sabe nada sobre você. Não sabe onde você trabalha, o que você
> vende, quem é seu cliente. Tudo que ele sabe do seu contexto é o que você
> escreveu. E é exatamente por isso que a próxima aula é sobre como escrever
> direito o que você quer."

---

### ⏱ 7:30 — FECHO · `[SLIDE 2]` · **fala literal**

> "Interface mapeada. Você já sabe onde fica cada coisa e o que esperar da
> ferramenta.
>
> Só que saber onde clicar é a parte fácil. A diferença entre quem tira valor do
> Claude e quem acha que ele é 'meio genérico' está em uma coisa só: como você
> pede. É a próxima aula. Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — primeira mensagem**

```
Explique em 3 parágrafos curtos o que é um modelo de linguagem,
como se eu fosse alguém que trabalha com gestão e nunca estudou tecnologia.
Sem jargão. No final, dê um exemplo do dia a dia de escritório.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| A interface está diferente do roteiro | Narre o que está na tela. A estrutura é a mesma: conversa, histórico, projetos, modelo, configurações. Não peça desculpa pela diferença. |
| Resposta demorou mais de 15s | Continue narrando o que espera ver. Marque `[CORTE]` e a edição corta a espera. |
| Nome de plano mudou | Fale o que está na página aberta. Nunca leia do roteiro sem conferir. |
| Apareceu banner de novidade/pop-up | Feche antes de continuar. Se aparecer no meio, feche naturalmente e siga — não comente. |
| Você travou na fala do gancho | Regrave só o gancho. São 30s, é mais barato que refazer o vídeo. |

---

## Notas de edição

- **Corte toda espera de geração acima de 3s.** Esta aula tem uma só, na
  primeira mensagem.
- `⏱ 2:30–5:00` — o tour pede **zoom de ~130%** em cada elemento apontado.
  Sem zoom, o aluno no celular não enxerga a barra lateral.
- `⏱ 3:20` — na fala "cada conversa é um contexto separado", entra **card de
  texto** na tela: *"1 conversa = 1 contexto"*.
- `⏱ 6:30` — os três limites pedem **três bullets animados** entrando um a um,
  sincronizados com a fala.
- **Título sugerido:** "Claude do zero: a interface inteira em 8 minutos"
- **Thumbnail:** print da tela inicial do Claude com a barra lateral destacada.
