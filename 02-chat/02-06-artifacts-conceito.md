# 02.06 — Artifacts: conteúdo que ganha vida

| | |
|---|---|
| **Duração alvo** | 7 min |
| **Slides** | 7 (blocos "O que são" e "Tipos") |
| **Material base** | `modulos/02-chat/README.md` § 2.4 |
| **Arquivo de vídeo** | `M02-A06-artifacts-conceito.mp4` |

---

## Preparação (antes do REC)

- [ ] Deck no **slide 7**
- [ ] Conversa **nova e vazia**, **fora** do Projeto Revisor
      (dentro do Projeto, as instruções de revisão atrapalham a demo)
- [ ] Prompts 1 e 2 copiados
- [ ] Janela do navegador larga o bastante para o painel lateral abrir bem

---

## Mapa do vídeo

| Bloco | ⏱ | Tela |
|-------|---|------|
| Gancho | 0:00 | Slide 7 |
| Demo instantânea | 0:40 | Tela |
| O que é um Artifact | 2:30 | Slide 7 |
| Os tipos que valem a pena | 3:40 | Slide 7 |
| Quando NÃO vira artifact | 5:30 | Tela |
| Fecho | 6:20 | Slide 7 |

---

## Roteiro

### ⏱ 0:00 — GANCHO · `[SLIDE 7]` · **fala literal**

> "Até agora tudo que a gente fez com o Claude foi texto. Bom texto, texto
> estruturado — mas texto.
>
> Essa aula é sobre a hora em que ele para de escrever sobre a coisa e passa a
> **entregar a coisa**. Um diagrama que você olha. Uma página que abre. Um
> dashboard que responde ao clique.
>
> Isso chama Artifact, e eu vou te mostrar um em quarenta segundos."

---

### ⏱ 0:40 — DEMO INSTANTÂNEA · `[TELA: claude.ai]` · **fala livre**

Cole o **Prompt 1** (fluxograma em Mermaid). Enquanto gera:

- Aponte o painel lateral abrindo sozinho.
- Aponte que ele desenha **enquanto** escreve — não precisa esperar terminar.

> **Fala literal, quando o diagrama aparecer:**
> "Repara no que aconteceu. Eu não recebi o código de um diagrama pra eu colar em
> algum lugar. Eu recebi o diagrama. Ele está ali, renderizado, pronto."

Mostre rapidamente:
- O painel **ocupa o lado direito**, a conversa continua na esquerda.
- Dá para **expandir** o painel para tela cheia.
- Dá para **baixar** o resultado.

⚠️ Se o painel não abrir sozinho, veja o Plano B.

---

### ⏱ 2:30 — O QUE É UM ARTIFACT · `[SLIDE 7]` · **fala literal**

> "Definição curta: Artifact é um conteúdo que o Claude gera fora da conversa,
> numa janela própria, e que fica **vivo** — você vê renderizado e itera em cima.
>
> Três características que importam:
>
> Primeira: ele é **renderizado**, não descrito. Se é uma página, ela abre. Se é
> um gráfico, ele desenha.
>
> Segunda: ele é **iterável**. Você não recomeça — você diz 'muda a cor', 'troca
> os dados', 'adiciona uma coluna', e ele altera o mesmo artifact.
>
> Terceira: ele é **destacável**. Sai da conversa. Você baixa, publica, manda o
> link pra alguém que nem tem conta no Claude — e isso é a aula 08."

---

### ⏱ 3:40 — OS TIPOS QUE VALEM A PENA · `[SLIDE 7]` · **fala livre**

Percorra a tabela do slide. **10 a 15 segundos cada** — não aprofunde, cada tipo
merecia um curso.

| Tipo | Fale isso |
|------|-----------|
| **Página web** | Landing page, formulário, protótipo. Você valida a ideia antes de chamar o time de front-end. |
| **Dashboard** | Métricas, KPIs, gráfico. É a próxima aula inteira. |
| **Diagrama** | Fluxograma, arquitetura, processo. O que a gente acabou de fazer. |
| **Visualização de dados** | Barras, linha, pizza — a partir de dados que você cola ou sobe. |
| **Documento** | Markdown formatado, tabelas longas, relatório que você exporta. |
| **Jogo / interativo** | Parece brincadeira, mas é o melhor jeito de demonstrar uma mecânica ou ensinar um conceito. |

> **Fala literal:**
> "O padrão é esse: sempre que o resultado do seu pedido é uma **coisa** e não
> uma explicação sobre a coisa, você quer um artifact."

---

### ⏱ 5:30 — QUANDO NÃO VIRA ARTIFACT · `[TELA: claude.ai]` · **fala livre**

> **Fala literal — a expectativa que precisa ser calibrada:**
> "E agora o que ninguém te conta: nem todo pedido vira artifact. Ele decide
> sozinho, e a decisão é mais ou menos assim — conteúdo curto e conversacional
> fica no chat; conteúdo longo, estruturado e que você vai reaproveitar vira
> artifact.
>
> Só que você não fica refém disso."

Cole o **Prompt 2** — pedindo explicitamente um artifact.

- Mostre que pedir funciona.
- > "Se você quer artifact, pede artifact. 'Crie como um artifact', 'gere uma
  > página HTML completa'. Ele obedece."

---

### ⏱ 6:20 — FECHO · `[SLIDE 7]` · **fala literal**

> "Artifact é conteúdo renderizado, iterável e destacável. Serve pra quando você
> quer a coisa pronta, não a descrição dela.
>
> Na próxima aula a gente pega o tipo mais útil de todos pra quem trabalha com
> número — dashboard — e constrói um do zero, com dados de uma loja de verdade. E
> depois a gente publica e manda o link pra alguém.
>
> Essas duas próximas aulas são sequência direta. Se puder, assiste as duas
> seguidas. Te vejo lá."

---

## Prompts para copiar e colar

**Prompt 1 — o artifact instantâneo**

```
Crie um fluxograma em Mermaid do processo de atendimento a um chamado de
suporte, do momento em que o cliente abre o ticket até o encerramento.

Inclua: triagem por prioridade, dois níveis de atendimento, o caminho de
escalonamento e o ponto onde o cliente confirma a solução.
```

**Prompt 2 — forçando o artifact**

```
Crie um artifact com um checklist visual em HTML para revisão de um
comunicado interno antes do envio. 8 itens, com checkbox clicável,
contador de itens marcados e visual limpo.
```

---

## Plano B

| Se acontecer | O que fazer |
|--------------|-------------|
| O painel lateral não abriu | Confira se Artifacts está ativado nas configurações da conta. Ative **antes** de gravar. Se ainda assim não abrir, peça explicitamente: *"gere isso como um artifact"*. |
| O Mermaid deu erro de sintaxe | Peça: *"O diagrama deu erro de renderização. Corrija a sintaxe do Mermaid e gere de novo."* Grave a correção — mostrar que dá pra consertar em uma frase é conteúdo útil. |
| A janela está estreita e o painel espremeu | Pare, ajuste a janela, regrave o bloco. Painel espremido arruína a demo no celular. |
| O Prompt 2 não gerou artifact | Reforce: *"Gere como um artifact HTML completo e autocontido."* Se persistir, use o dashboard da próxima aula como exemplo e corte esse bloco. |
| Passou de 8 min | Corte metade dos tipos na tabela (⏱ 3:40). Mantenha página, dashboard e diagrama. |

---

## Notas de edição

- `⏱ 0:40–2:30` — o momento em que o painel abre é **o** momento da aula.
  Considere **repetir o clipe em câmera lenta** por 2s, com destaque na borda do
  painel.
- `⏱ 2:30` — as três características (renderizado / iterável / destacável) entram
  como **três cards animados**.
- `⏱ 3:40` — a tabela de tipos pede **miniatura real** de cada um, se houver
  material de arquivo. Se não houver, o texto do slide basta.
- `⏱ 5:30` — a fala "se você quer artifact, pede artifact" vira **card**.
- Corte todas as esperas de geração — esta aula tem duas.
- **Título sugerido:** "Artifacts: quando o Claude entrega a coisa pronta"
- **Thumbnail:** split da tela com a conversa à esquerda e o diagrama renderizado à direita.
