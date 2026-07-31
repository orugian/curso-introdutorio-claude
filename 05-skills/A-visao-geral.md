# Skills · Vídeo A — Visão geral

**Alvo:** 8 min · **Slides:** 1 a 4 e 7 do deck `05-skills.html`

---

## Preparação

- [ ] Deck aberto no slide 1
- [ ] Claude aberto com a área de Skills visível
- [ ] [`recursos/exemplo-SKILL.md`](../recursos/exemplo-SKILL.md) aberto no
      editor, fonte 16pt ou maior (é a mesma skill que você escreve no vídeo B)
- [ ] **Skill da demonstração escolhida e ensaiada** — veja abaixo

### Qual skill usar na demonstração

Use uma **skill de criação de documento** (apresentação ou planilha): ela ativa
sozinha a partir do pedido, que é o ponto da cena, e o resultado é visível.

**Ensaie antes de gravar** com este prompt:

```
Monta uma apresentação de 5 slides explicando para a equipe comercial
o que muda com a adoção de IA no atendimento ao cliente.
```

Alternativa, se essa não ativar:

```
Gera uma planilha de controle de horas por projeto, com uma aba de
lançamentos e uma aba de resumo mensal por colaborador.
```

Se nenhuma ativar sozinha, **pule a demonstração** e vá do slide 3 direto para
o slide 4. Chamar a skill pelo nome destrói o argumento da cena, que é
justamente ela entrar sem ser chamada.

---

## Roteiro

### `[SLIDE 1]` — Abertura · **fala literal**

> "Nos módulos anteriores você aprendeu a pedir bem e a automatizar. Esse é
> sobre especializar.
>
> Skill é o jeito de ensinar ao Claude como **a sua empresa** faz uma coisa — e
> ele passar a fazer daquele jeito, sem você explicar de novo.
>
> Oito minutos de visão geral. No próximo vídeo a gente cria uma do zero."

---

### `[SLIDE 2]` — O que é uma Skill · ~2 min

- **O que é:** um conjunto de instruções reutilizáveis que o Claude carrega quando o assunto aparece.
- **Pra que serve:** transformar ele em especialista num domínio seu — o seu processo, o seu padrão, o seu formato.
- A diferença que confunde todo mundo:

| | O que é | Quando usar |
|---|---|---|
| **Prompt** | Um pedido, uma vez | Tarefa pontual |
| **Projeto** | Contexto fixo num espaço | Trabalho recorrente, no chat |
| **Skill** | Instrução que ele carrega sozinho quando precisa | Um jeito de fazer que vale em qualquer conversa |

> A diferença prática pro Projeto: no Projeto você entra no espaço. A skill vem
> até você quando o assunto aparece.

---

### `[SLIDE 3]` — Skills prontas · ~1min30

- `[TELA]` mostre a área de Skills e o que já vem disponível.
- **Exemplo** — acione uma skill instalada e mostre ela mudando o comportamento da resposta.
- > "Repara que eu não expliquei nada. Ela reconheceu o assunto e entrou sozinha."

---

### `[SLIDE 4]` — Como uma Skill é feita por dentro · ~2 min

`[TELA]` abra um `SKILL.md` no editor. Mostre as três partes:

1. **Nome e descrição** (o cabeçalho) — é o que faz o Claude saber **quando** usar.
   > "A descrição é a parte mais importante e a que mais gente escreve mal. Ela não descreve a skill — ela descreve o momento de usá-la."
2. **Quando usar** — os gatilhos, em palavras.
3. **Instruções** — o passo a passo do que fazer.

- Cite: dá pra anexar arquivos de referência e scripts, mas isso é assunto avançado.

---

### `[SLIDE 7]` — Onde isso chega · ~1min30

- Skill + ferramentas conectadas + agendamento = **agente**: roda sozinho e entrega resultado.
- Exemplo em uma frase: uma skill de relatório, conectada à sua planilha, agendada toda segunda.
- > "Não vamos construir isso agora. Só quero que você saiba que o caminho existe e que ele começa exatamente onde a gente vai começar no próximo vídeo."

---

### `[SLIDE 2]` — Fecho · **fala literal**

> "Resumindo: skill é instrução reutilizável que o Claude carrega sozinho quando
> o assunto aparece. Ela tem nome, descrição, gatilho e passo a passo.
>
> E o conselho que vale mais que o resto: comece pela tarefa que você mais
> explica. Aquela que toda vez você repete do zero. Essa é a sua primeira skill.
>
> No próximo vídeo a gente cria ela. Te vejo lá."

---

## Plano B

- **Nenhuma skill instalada na conta?** Instale uma antes de gravar. Sem
  demonstração de skill funcionando, o vídeo fica abstrato demais.
- **A skill não ativou sozinha?** Chame explicitamente pelo nome e comente:
  *"quando a descrição não é clara, ele não reconhece o momento — e é por isso
  que a descrição importa tanto"*. Vira um bom argumento.
- **Interface diferente?** Fale o que está na tela.

---

## Edição

- A tabela Prompt / Projeto / Skill entra **linha por linha** — é a comparação que o aluno vai printar.
- Zoom no `SKILL.md` ao apontar cada parte; texto de editor não se lê no celular sem zoom.
- A fala sobre a descrição ("descreve o momento de usá-la") merece **card em tela**.
