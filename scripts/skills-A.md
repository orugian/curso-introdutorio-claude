# Script — Skills · Vídeo A: Visão geral

**Duração estimada:** 8 min · **Deck:** `05-skills.html`
**Roteiro de apoio:** [`05-skills/A-visao-geral.md`](../05-skills/A-visao-geral.md)

### Telas usadas, na ordem

| # | Passagem | Tela |
|---|----------|------|
| 1 | Abertura | SLIDE 1 — "Skills: Criando Superpoderes" |
| 2 | O que é uma Skill | SLIDE 2 — "4.1 O que são Skills" |
| 3 | Prompt, Projeto e Skill | SLIDE 2 |
| 4 | Skills prontas | SLIDE 3 → TELA — área de Skills |
| 5 | Uma skill funcionando | TELA — conversa |
| 6 | Como é por dentro | SLIDE 4 → EDITOR — SKILL.md |
| 7 | A descrição | EDITOR + ZOOM |
| 8 | Onde isso chega | SLIDE 7 — "4.6 Criando Agentes Autônomos" |
| 9 | Fecho | SLIDE 2 |

---

## 1 · Abertura
**🖥️ SLIDE 1** — "Skills: Criando Superpoderes" &nbsp;&nbsp; ⏱️ 0:00 – 0:35

> Terceiro e último módulo desse bloco.
>
> No primeiro você aprendeu a pedir bem. No segundo, a automatizar. Esse aqui é sobre especializar.
>
> Skill é o jeito de ensinar ao Claude como a sua empresa faz uma coisa — o seu processo, o seu padrão, o seu formato — e ele passar a fazer daquele jeito sem você explicar de novo.
>
> Oito minutos de visão geral. No próximo vídeo a gente cria uma do zero.

---

## 2 · O que é uma Skill
**🖥️ SLIDE 2** — "4.1 O que são Skills" &nbsp;&nbsp; ⏱️ 0:35 – 1:35

> Definição: uma skill é um conjunto de instruções reutilizáveis que o Claude carrega sozinho quando o assunto aparece.
>
> Vou repetir a parte que importa: sozinho, quando o assunto aparece.
>
> Você não precisa lembrar de chamar. Você não precisa colar nada. Você fala do assunto e ela entra.
>
> E pra que serve? Pra transformar ele em especialista num domínio que é seu. Não em "revisar texto" no genérico — em revisar texto do jeito que a sua empresa revisa, com as regras que a sua empresa usa.
>
> É a diferença entre um assistente que sabe muito e um assistente que sabe como as coisas funcionam aqui.

---

## 3 · Prompt, Projeto e Skill
**🖥️ SLIDE 2** &nbsp;&nbsp; ⏱️ 1:35 – 2:35

> E aí vem a confusão clássica, que eu quero resolver agora: qual a diferença pra um Projeto?
>
> Vamos pelos três.
>
> Um prompt é um pedido. Você escreve, ele responde, acabou. Serve pra tarefa pontual.
>
> Um Projeto é um espaço com contexto fixo. Você entra nele e tudo lá dentro já sabe do que se trata. Serve pra trabalho recorrente.
>
> E uma skill é uma instrução que ele carrega quando reconhece o momento. Ela não está presa a um espaço — vale em qualquer conversa.
>
> A diferença prática entre skill e Projeto é essa: no Projeto, você vai até o contexto. Com a skill, o contexto vem até você.
>
> Se você usa aquele padrão só quando está trabalhando naquele assunto específico, Projeto resolve. Se aquele padrão precisa valer sempre que o tema aparecer, é skill.

---

## 4 · Skills prontas
**🖥️ SLIDE 3** por ~10s → **🖥️ TELA** — área de Skills &nbsp;&nbsp; ⏱️ 2:35 – 3:20

> E a boa notícia é que você não precisa começar do zero.
>
> **[abre a área de Skills]** Aqui é onde as skills ficam. **[percorre a lista]** Tem skill pronta pra várias coisas — revisão, análise, documentação, apoio a desenvolvimento.
>
> Vale você abrir e dar uma olhada no que já existe antes de escrever a sua. Muitas vezes o que você ia fazer já está aqui, e aí você só ajusta.
>
> Mas o mais interessante não é a lista. É ver uma funcionando.

---

## 5 · Uma skill funcionando
**🖥️ TELA** — conversa nova &nbsp;&nbsp; ⏱️ 3:20 – 4:10

> **[faz um pedido que aciona a skill instalada]**
>
> Repara no que eu escrevi: eu não chamei a skill pelo nome. Eu não falei "usa a skill tal". Eu só descrevi o que eu queria.
>
> **[quando a skill for acionada]** E olha aí — ela entrou sozinha. Ele reconheceu o assunto e carregou as instruções.
>
> **[mostra o resultado]** E o resultado já vem no formato que a skill define, sem eu ter pedido formato nenhum.
>
> É esse o ganho. A skill carrega o padrão por você.

---

## 6 · Como é por dentro
**🖥️ SLIDE 4** por ~10s → **🖥️ EDITOR** — arquivo `SKILL.md` aberto &nbsp;&nbsp; ⏱️ 4:10 – 5:20

> Agora deixa eu abrir o capô, porque no próximo vídeo você vai escrever uma dessas.
>
> **[abre o SKILL.md no editor]** Uma skill é um arquivo de texto. Só isso. Chama SKILL ponto MD e tem três partes.
>
> **[aponta o cabeçalho]** Primeira parte: o cabeçalho, entre esses tracinhos. Tem o nome, que é curto e sem espaço, e a descrição.
>
> **[aponta a seção "quando usar"]** Segunda parte: quando usar. Os gatilhos, escritos em português mesmo — em que situação essa skill deve entrar.
>
> **[aponta as instruções]** E terceira: as instruções. O passo a passo do que fazer, numerado, do jeito que você explicaria pra alguém que chegou agora.
>
> Dá pra anexar arquivo de referência e até script junto, mas isso é assunto avançado. Pra começar, é texto.

---

## 7 · A descrição
**🖥️ EDITOR + ZOOM** — linha `description` &nbsp;&nbsp; ⏱️ 5:20 – 6:10

> E agora a parte que eu preciso que você não esqueça, porque é onde quase todo mundo erra na primeira skill.
>
> **[destaca a linha da descrição]** Essa linha aqui, a descrição.
>
> Olha o que está escrito: "use quando o usuário pedir revisão de um comunicado interno, e-mail corporativo ou aviso antes do envio".
>
> Repara que ela não descreve o que a skill faz. Ela descreve **quando usar**.
>
> Essa é a diferença entre uma skill que entra sozinha e uma que fica lá parada, esperando você lembrar dela.
>
> Se você escrever "revisa textos", ele não vai saber reconhecer o momento. Se você escrever a situação, ele reconhece.
>
> Descrição descreve o gatilho, não a função. Anota essa.

---

## 8 · Onde isso chega
**🖥️ SLIDE 7** — "4.6 Criando Agentes Autônomos" &nbsp;&nbsp; ⏱️ 6:10 – 7:00

> Antes de fechar, deixa eu te mostrar onde esse caminho vai dar.
>
> Junta as três coisas do curso: uma skill, que é o conhecimento especializado. Um conector, que dá acesso aos seus dados. E um agendamento, que faz rodar sozinho.
>
> Isso tem nome: agente.
>
> Um exemplo pra ficar concreto: uma skill que sabe montar o seu relatório do jeito que a diretoria gosta, conectada à sua planilha de números, agendada pra rodar toda segunda de manhã. Você não pede nada. O relatório chega.
>
> A gente não vai construir isso agora, e nem precisa. Eu só quero que você saiba que o caminho existe, e que ele começa exatamente onde a gente vai começar no próximo vídeo: escrevendo uma skill simples.

---

## 9 · Fecho
**🖥️ SLIDE 2** &nbsp;&nbsp; ⏱️ 7:00 – 7:40

> Recapitulando: skill é instrução reutilizável que o Claude carrega sozinho quando o assunto aparece. Ela é um arquivo de texto com nome, descrição, gatilho e passo a passo. E a descrição é o que faz ela funcionar.
>
> E o conselho que vale mais que o resto: comece pela tarefa que você mais explica.
>
> Aquela que toda vez você repete do zero, aquela que quando alguém novo entra no time você tem que sentar e ensinar de novo. Essa é a sua primeira skill.
>
> No próximo vídeo a gente escreve ela juntos. Te vejo lá.
