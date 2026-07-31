# Script — Skills · Vídeo B: Mão na massa

**Duração estimada:** 9 min · **Deck:** `05-skills.html`
**Roteiro de apoio:** [`05-skills/B-mao-na-massa.md`](../05-skills/B-mao-na-massa.md)

### Telas usadas, na ordem

| # | Passagem | Tela |
|---|----------|------|
| 1 | Abertura | SLIDE 11 — "Template de Skill" |
| 2 | O cabeçalho | EDITOR — arquivo novo, fonte grande |
| 3 | A descrição | EDITOR + ZOOM |
| 4 | Quando usar | EDITOR |
| 5 | As instruções | EDITOR |
| 6 | O que evitar | EDITOR + ZOOM |
| 7 | Instalando | TELA — área de Skills |
| 8 | Testando | TELA — conversa nova |
| 9 | Ajustando | EDITOR → TELA |
| 10 | Fecho | SLIDE 11 |

---

## 1 · Abertura
**🖥️ SLIDE 11** — "Template de Skill" &nbsp;&nbsp; ⏱️ 0:00 – 0:30

> Vamos criar uma skill do zero.
>
> A nossa vai revisar comunicado interno no padrão da empresa. Depois que ela existir, eu nunca mais preciso explicar esse padrão pro Claude.
>
> São três passos: escrever, instalar e testar. E no final eu mostro o quarto, que quase todo mundo pula e é o que faz a skill ficar boa de verdade.
>
> Vamos escrever.

---

## 2 · O cabeçalho
**🖥️ EDITOR** — arquivo novo, fonte grande &nbsp;&nbsp; ⏱️ 0:30 – 1:20

> ### ✍️ Texto desta cena — **digite**
>
> ```yaml
> ---
> name: revisor-comunicado
> description: Use quando o usuário pedir revisão de um comunicado interno,
>   e-mail corporativo, aviso ou circular antes do envio.
> ```
>
> São só 4 linhas — **digite mesmo**, o aluno precisa ver nascendo. O `---` de
> fechamento vem no fim da cena 3.
>
> ⚠️ A quebra da segunda linha da `description` precisa de **2 espaços de
> indentação**, senão o YAML não valida.

> **[cria o arquivo SKILL.md]** Arquivo novo, chamado SKILL ponto MD.
>
> **[escreve os três tracinhos e o name]** Começa com esses três tracinhos, que abrem o cabeçalho.
>
> Primeiro campo, o nome: "revisor-comunicado". Curto, minúsculo, sem espaço, sem acento. Ele é o identificador — não precisa ser bonito, precisa ser único.
>
> **[escreve a linha da descrição]** E o segundo campo é a descrição. Essa aqui merece parágrafo próprio.

---

## 3 · A descrição
**🖥️ EDITOR + ZOOM** — linha `description` &nbsp;&nbsp; ⏱️ 1:20 – 2:10

> ### ✍️ Texto desta cena — **digite ao final**
>
> Nada novo até o fim da cena. Aqui você só **comenta** a linha que já escreveu,
> com zoom nela. No último segundo, fecha o cabeçalho:
>
> ```yaml
> ---
> ```

> Olha o que eu escrevi: "use quando o usuário pedir revisão de um comunicado interno, e-mail corporativo, aviso ou circular antes do envio".
>
> Repara que eu não escrevi "revisa textos".
>
> Eu escrevi a **situação**. Quando isso deve acontecer.
>
> Essa é a diferença entre uma skill que entra sozinha e uma que fica parada esperando você lembrar dela. O Claude lê essa linha pra decidir se é hora de usar. Se a linha descreve a função, ele não reconhece o momento. Se descreve o momento, ele reconhece.
>
> Se você levar uma coisa só desse vídeo, leva essa.
>
> **[fecha o cabeçalho com os três tracinhos]**

---

## 4 · Quando usar
**🖥️ EDITOR** &nbsp;&nbsp; ⏱️ 2:10 – 2:50

> ### ✍️ Texto desta cena — **digite**
>
> ```markdown
> # Revisor de Comunicado Interno
>
> ## Quando usar
> - O usuário colou um texto e pediu revisão, ajuste ou opinião
> - O texto é uma comunicação interna: comunicado, e-mail, aviso, circular
> ```

> **[escreve o título e a seção "Quando usar"]**
>
> Agora sai do cabeçalho e começa o corpo, que é markdown normal.
>
> Primeira seção: quando usar. Aqui eu escrevo os gatilhos com mais calma, em bullet.
>
> **[escreve]** "O usuário colou um texto e pediu revisão, ajuste ou opinião." "O texto é uma comunicação interna: comunicado, e-mail, aviso, circular."
>
> Isso reforça a descrição. A descrição é a versão curta que ele lê primeiro. Essa seção é o detalhe.

---

## 5 · As instruções
**🖥️ EDITOR** &nbsp;&nbsp; ⏱️ 2:50 – 4:10

> ### ✍️ Texto desta cena — **cole em 3 partes**
>
> A cena mais longa. Digitar isso inteiro dá quase 2 minutos de tela morta.
> **Cole em blocos**, comentando cada um enquanto aparece.
>
> **Bloco 1** — cole e comente:
> ```markdown
> ## Instruções
>
> 1. Verifique se o texto responde a três perguntas, nesta ordem:
>    o que muda, a partir de quando, e o que o leitor precisa fazer.
> ```
>
> **Bloco 2** — cole e comente (é onde está o argumento da cena):
> ```markdown
> 2. Aponte todo jargão desnecessário: "vimos por meio desta",
>    "no que tange a", "sendo certo que", "do corrente mês".
> ```
>
> **Bloco 3** — cole e comente:
> ```markdown
> 3. Verifique se as datas estão por extenso e se há bloco de próximos passos.
> 4. Responda sempre em 3 seções, nesta ordem:
>    - **Problemas** (no máximo 5, os mais importantes)
>    - **Sugestão** (o texto reescrito, pronto para enviar)
>    - **Nota** (1 a 10, com justificativa de 1 linha)
> ```

> **[escreve a seção Instruções]**
>
> Agora o miolo: o passo a passo. E a regra pra escrever isso bem é essa — escreva como se estivesse explicando pra uma pessoa que entrou hoje no time.
>
> **[escreve o passo 1]** Passo um: verificar se o texto responde três perguntas, nessa ordem — o que muda, a partir de quando, e o que o leitor precisa fazer.
>
> **[escreve o passo 2]** Passo dois: apontar jargão desnecessário. E aqui eu vou ser bem específico, listando os termos: "vimos por meio desta", "no que tange a", "sendo certo que", "do corrente mês".
>
> Presta atenção nisso: quanto mais específico, melhor. "Evite jargão" é vago. Listar os termos que te incomodam é uma regra que ele consegue aplicar.
>
> **[escreve os passos 3 e 4]** Passo três: conferir datas por extenso e bloco de próximos passos. E passo quatro, o formato de saída: sempre três seções — problemas, sugestão e nota de um a dez.

---

## 6 · O que evitar
**🖥️ EDITOR + ZOOM** — seção "O que evitar" &nbsp;&nbsp; ⏱️ 4:10 – 4:50

> ### ✍️ Texto desta cena — **digite**
>
> ```markdown
> ## O que evitar
> - Não invente problema. Se o texto está bom, diga que está bom.
> - Não mude o tom original sem motivo.
> - Não deixe o texto reescrito mais longo que o original.
> ```
>
> Três linhas, digite. **Salve o arquivo ao final da cena.**
>
> ✅ Arquivo completo para conferir:
> [`recursos/skill-revisor-comunicado.md`](../recursos/skill-revisor-comunicado.md)

> **[escreve a seção]**
>
> E a última seção, que eu coloco em toda skill que escrevo: o que evitar.
>
> **[escreve]** "Não invente problema. Se o texto está bom, diga que está bom." "Não mude o tom original sem motivo." "Não deixe o texto reescrito mais longo que o original."
>
> Essa seção é onde você registra o erro que você já cansou de corrigir.
>
> Toda vez que você usar a skill e ela fizer alguma coisa que te irrita, você volta aqui e escreve a regra. Em duas semanas ela fica afiada.
>
> **[salva o arquivo]** E pronto, a skill está escrita.

---

## 7 · Instalando
**🖥️ TELA** — área de Skills &nbsp;&nbsp; ⏱️ 4:50 – 5:40

> ### 🎬 O que fazer
>
> Sem texto novo. Você instala o `SKILL.md` que acabou de escrever, do mesmo
> jeito que instalou a `resumo-reuniao` antes do vídeo A — o passo a passo está
> no [README da skill de demonstração](../recursos/skill-demo-resumo-reuniao/README.md).
>
> ⚠️ **Ensaie a instalação antes de gravar.** Você precisa saber onde clicar.
> E confira que a `revisor-comunicado` **não está** instalada de antes, senão a
> cena mostra uma skill que já existia.

> Agora eu preciso colocar ela pra funcionar.
>
> **[adiciona a skill na conta]** É aqui que eu adiciono.
>
> **[quando aparecer na lista]** E aí está ela, na lista, junto com as outras.
>
> A partir de agora ela está disponível em qualquer conversa. Não é como o Projeto, que você precisa entrar. Ela está no ambiente, esperando o assunto aparecer.

---

## 8 · Testando
**🖥️ TELA** — conversa nova &nbsp;&nbsp; ⏱️ 5:40 – 6:50

> ### 📋 Texto desta cena — **cole inteiro**
>
> Arquivo pronto: [`recursos/cena8-colar.txt`](../recursos/cena8-colar.txt).
> Copie tudo e cole numa conversa nova, **fora de qualquer Projeto**.
>
> ```
> Revisa esse comunicado.
>
> Prezados, vimos por meio desta informar que no que tange ao estacionamento
> do prédio, a partir do dia 20 do corrente mês as vagas passarão a ser
> rotativas, sendo certo que a não observância poderá acarretar em remoção
> do veículo.
> ```
>
> **Não faça:** citar o nome da skill, pedir formato, pedir as três seções.
>
> **O que deve aparecer:**
> - Seção **Problemas** — com "vimos por meio desta", "no que tange" e "do corrente mês"
> - Seção **Sugestão** — o comunicado reescrito
> - Seção **Nota** — de 1 a 10, com justificativa de 1 linha
>
> Os três jargões estão plantados no texto de propósito: são exatamente os que
> você listou no passo 2 das instruções, na cena 5.

> Vamos testar. **[abre conversa nova e cola o texto de teste]**
>
> Presta atenção no que eu vou escrever: "revisa esse comunicado". Só isso.
>
> Eu não vou dizer o formato. Não vou dizer o que olhar. Não vou chamar a skill pelo nome.
>
> **[envia]**
>
> **[quando a skill for acionada]** E olha aí — ela entrou sozinha.
>
> **[percorre a resposta]** E o resultado veio no formato que eu defini: problemas, sugestão, nota. Ele apontou o "vimos por meio desta", apontou o "no que tange", apontou o "do corrente mês".
>
> São exatamente os termos que eu listei no passo dois das instruções.
>
> Eu não disse nada disso agora. A skill disse por mim.

---

## 9 · Ajustando
**🖥️ EDITOR** → **🖥️ TELA** &nbsp;&nbsp; ⏱️ 6:50 – 7:50

> ### ✍️ Texto desta cena
>
> **1) No editor**, acrescente esta linha no fim da seção `## O que evitar`:
> ```markdown
> - Sempre sugira um assunto de e-mail melhor que o atual.
> ```
>
> **2) Salve e recarregue a skill** na conta (mesmo caminho da cena 7).
>
> **3) Na conversa**, cole **o mesmo texto da cena 8** de novo
> ([`recursos/cena8-colar.txt`](../recursos/cena8-colar.txt)).
>
> **O que muda:** agora a resposta traz também uma sugestão de assunto de
> e-mail. É o antes/depois que prova o ponto da cena.
>
> ⚠️ Use **conversa nova** para o segundo teste. Na mesma conversa ele pode
> responder pelo contexto anterior, e aí você não sabe se foi a regra nova.

> E agora o quarto passo, o que quase todo mundo pula.
>
> Vendo o resultado, eu senti falta de uma coisa: ele não sugeriu um assunto melhor pro e-mail. Então eu vou adicionar essa regra.
>
> **[volta ao editor e escreve]** "Sempre sugira um assunto de e-mail melhor que o atual."
>
> **[salva e recarrega]** Salvo, recarrego a skill…
>
> **[roda o mesmo teste]** …e rodo o mesmo teste de novo.
>
> **[quando responder]** E agora ele sugere o assunto.
>
> É esse o ciclo: usa, não gostou de alguma coisa, volta e escreve a regra. Skill não nasce pronta, ela é calibrada.
>
> As minhas que eu mais uso foram ajustadas umas dez vezes cada. As que eu criei e nunca mais toquei são justamente as que eu não uso.

---

## 10 · Fecho
**🖥️ SLIDE 11** &nbsp;&nbsp; ⏱️ 7:50 – 8:40

> E terminamos. Skill escrita, instalada, testada e ajustada. E ela vale pra qualquer conversa daqui pra frente.
>
> Seu exercício: pega a tarefa que você mais explica no trabalho e transforma numa skill. Não precisa ficar bonita na primeira versão — precisa funcionar e ser ajustada com o uso.
>
> E com isso a gente fecha esses três módulos.
>
> No primeiro você aprendeu a conversar: os cinco blocos do prompt, Projetos, Artifacts e análise de arquivo.
>
> No segundo, a automatizar: descrever a tarefa, conectar, agendar e testar.
>
> E nesse, a especializar: escrever uma skill que carrega o seu padrão sozinha.
>
> Conversar, automatizar e especializar. É isso que faz a diferença entre usar o Claude como uma caixa de perguntas e usar como ferramenta de trabalho de verdade.
>
> Obrigado por acompanhar, e bons projetos.
