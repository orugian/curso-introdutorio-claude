# Skills · Vídeo B — Mão na massa

**Alvo:** 9 min · **Slides:** 11 (template) do deck `05-skills.html`

Uma skill do zero: **revisor de comunicado interno.**

---

## Preparação

- [ ] Editor de texto aberto (VS Code ou similar), fonte grande
- [ ] Claude aberto na área de Skills
- [ ] Texto de teste copiado em bloco de notas
- [ ] Ensaie a criação uma vez antes — você precisa saber onde salvar a skill na sua conta

---

## Roteiro

### Abertura · **fala literal**

> "Vamos criar uma skill do zero. Ela vai revisar comunicado interno no padrão
> da empresa, e depois disso eu nunca mais preciso explicar esse padrão.
>
> Três passos: escrever, instalar e testar. E no final eu mostro o passo que
> quase todo mundo pula, que é ajustar."

---

### 1. Escrevendo `[TELA: editor]` · ~3min30

Escreva o `SKILL.md` (conteúdo abaixo) na tela, comentando cada parte:

- **name** — curto, sem espaço.
- **description** — > "Aqui está o segredo. Eu não escrevi 'revisa textos'. Eu escrevi *quando* usar: 'quando o usuário pedir revisão de comunicado, e-mail ou aviso interno'. É isso que faz ele reconhecer o momento."
- **Quando usar** — os gatilhos em palavras simples.
- **Instruções** — passo a passo numerado, do jeito que você explicaria pra alguém novo.
- **O que evitar** — > "Sempre coloque essa seção. É onde você registra o erro que você já cansou de corrigir."

---

### 2. Instalando `[TELA]` · ~1min30

- Salve e adicione a skill na sua conta.
- Mostre ela aparecendo na lista de skills disponíveis.

---

### 3. Testando `[TELA]` · ~2 min

- Conversa nova. Cole o **Texto de teste** com um pedido simples: *"revisa esse comunicado"*.
- Mostre a skill sendo acionada **sem você chamar pelo nome**.
- Confira: veio no formato que a skill definiu?
- > "Eu não disse qual formato eu queria. A skill disse por mim."

---

### 4. Ajustando `[TELA]` · ~1min30

- Volte ao arquivo e **adicione uma linha ao vivo**:
  ```
  - Sempre sugira um assunto de e-mail melhor que o atual.
  ```
- Salve, recarregue, rode o mesmo teste.
- > "Skill não nasce pronta. Rodou, não gostou, volta e escreve a regra. As minhas que mais uso foram ajustadas umas dez vezes."

---

### Fecho · **fala literal**

> "Pronto: skill escrita, instalada, testada e ajustada. E ela vale pra qualquer
> conversa daqui pra frente.
>
> Seu exercício: pegue a tarefa que você mais explica no trabalho e transforme
> ela numa skill. Não precisa ficar bonita — precisa funcionar e ser ajustada
> depois.
>
> Com isso a gente fecha esses três módulos: conversar, automatizar e
> especializar. É o essencial pra você sair usando o Claude de verdade. Valeu!"

---

## O arquivo SKILL.md

```yaml
---
name: revisor-comunicado
description: Use quando o usuário pedir revisão de um comunicado interno,
  e-mail corporativo, aviso ou circular antes do envio.
---

# Revisor de Comunicado Interno

## Quando usar
- O usuário colou um texto e pediu revisão, ajuste ou opinião
- O texto é uma comunicação interna: comunicado, e-mail, aviso, circular

## Instruções

1. Verifique se o texto responde a três perguntas, nesta ordem:
   o que muda, a partir de quando, e o que o leitor precisa fazer.
2. Aponte todo jargão desnecessário: "vimos por meio desta",
   "no que tange a", "sendo certo que", "do corrente mês".
3. Verifique se as datas estão por extenso e se há bloco de próximos passos.
4. Responda sempre em 3 seções, nesta ordem:
   - **Problemas** (no máximo 5, os mais importantes)
   - **Sugestão** (o texto reescrito, pronto para enviar)
   - **Nota** (1 a 10, com justificativa de 1 linha)

## O que evitar
- Não invente problema. Se o texto está bom, diga que está bom.
- Não mude o tom original sem motivo.
- Não deixe o texto reescrito mais longo que o original.
```

**Linha adicionada no ajuste (item 4):**
```
- Sempre sugira um assunto de e-mail melhor que o atual.
```

---

## Texto de teste

```
Revisa esse comunicado.

Prezados, vimos por meio desta informar que no que tange ao estacionamento
do prédio, a partir do dia 20 do corrente mês as vagas passarão a ser
rotativas, sendo certo que a não observância poderá acarretar em remoção
do veículo.
```

---

## Plano B

- **A skill não ativou sozinha?** Chame pelo nome e comente: *"quando ela não
  entra sozinha, o problema está na descrição — ela precisa dizer o momento de
  usar, não o que a skill faz"*. Ajuste a descrição ao vivo: é o melhor
  conteúdo possível para este vídeo.
- **Deu erro no formato do arquivo?** Confira o bloco `---` do cabeçalho.
  Mostre o erro e a correção — vai acontecer com o aluno também.
- **Passou de 10 min?** Corte o item 4 e mencione no fecho que skill se ajusta com o uso.

---

## Edição

- O editor precisa de **fonte grande**. Escreva com no mínimo 16pt.
- Ao comentar a `description`, **destaque a linha** na tela.
- O momento da skill ativando sozinha é o clímax: mostre inteiro.
- Este é o último vídeo dos três módulos — o fecho merece uma recapitulação
  visual dos três temas.
