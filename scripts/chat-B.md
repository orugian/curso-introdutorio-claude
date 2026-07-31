# Script — Chat · Vídeo B: Mão na massa

**Duração estimada:** 10 min · **Deck:** `02-chat.html`
**Roteiro de apoio:** [`02-chat/B-mao-na-massa.md`](../02-chat/B-mao-na-massa.md)

### Telas usadas, na ordem

| # | Passagem | Tela |
|---|----------|------|
| 1 | Abertura | SLIDE 11 — "Modelo de Projeto: Revisor de Conteúdo" |
| 2 | Criando o Projeto | TELA — área de Projetos |
| 3 | As instruções | TELA + ZOOM — campo de instruções |
| 4 | A base de conhecimento | TELA — upload do PDF |
| 5 | Testando | TELA — conversa dentro do Projeto |
| 6 | Gerando o dashboard | SLIDE 13 → TELA — conversa nova |
| 7 | Iterando | TELA — painel do artifact |
| 8 | Publicando | TELA — botão de publicar |
| 9 | Subindo a planilha | TELA — anexo do CSV |
| 10 | Fecho | SLIDE 11 |

---

## 1 · Abertura
**🖥️ SLIDE 11** — "Modelo de Projeto: Revisor de Conteúdo" &nbsp;&nbsp; ⏱️ 0:00 – 0:30

> Vídeo prático. Nos próximos dez minutos a gente vai fazer quatro coisas, do zero: criar um Projeto, testar ele com um texto de verdade, gerar um dashboard e subir uma planilha pra análise.
>
> Meu pedido: abre o Claude do seu lado e faz junto comigo. Esse vídeo aqui não funciona só assistindo.
>
> Vamos começar pelo Projeto.

---

## 2 · Criando o Projeto
**🖥️ TELA** — área de Projetos &nbsp;&nbsp; ⏱️ 0:30 – 1:10

> **[clica em criar novo Projeto]** Vou criar um Projeto chamado "Revisor de Conteúdo".
>
> **[digita o nome]** E na descrição: "revisa documentos corporativos no padrão de redação da empresa".
>
> Um detalhe sobre a descrição: ela é pra você, não pra ele. Daqui a seis meses, com uns dez Projetos na conta, é ela que vai te fazer lembrar pra que serve esse aqui. Então escreve como se fosse pra outra pessoa ler.

---

## 3 · As instruções
**🖥️ TELA + ZOOM** — campo de instruções customizadas &nbsp;&nbsp; ⏱️ 1:10 – 2:50

> Agora a parte que importa: as instruções fixas. **[cola as instruções]**
>
> Deixa eu comentar três linhas dessas aqui.
>
> **[aponta a primeira linha]** A primeira define o papel: "você é um revisor sênior de conteúdo corporativo". Isso já muda o recorte de tudo que vem depois.
>
> **[aponta o formato]** Essa aqui fixa o formato: sempre três seções, problemas, sugestão e nota. Formato fixo é o que faz a saída ser comparável. Eu consigo olhar dez revisões e bater o olho, porque todas têm a mesma forma.
>
> **[aponta a linha anti-bajulação]** E essa aqui é a mais importante do Projeto inteiro: "se o texto estiver bom, diga que está bom, não invente problemas".
>
> Presta atenção nisso, porque é um comportamento real: se você pede problemas, ele acha problemas. Mesmo quando não tem. Escrever essa linha muda o resultado.
>
> Toda vez que você criar um Projeto que avalia alguma coisa, coloca uma linha dessas.

---

## 4 · A base de conhecimento
**🖥️ TELA** — arrastando o PDF para a base &nbsp;&nbsp; ⏱️ 2:50 – 3:40

> ### 📎 Qual arquivo é esse
>
> É o [`recursos/guia-de-estilo-tiops.md`](../recursos/guia-de-estilo-tiops.md)
> deste repositório — um guia de redação corporativa fictício, escrito para o curso.
>
> Ele nasce em Markdown. **Exporte para PDF antes de gravar** (VS Code com a
> extensão *Markdown PDF*, ou cole no Word e salve como PDF) e deixe na pasta
> Downloads. Em vídeo, subir um PDF é mais convincente que subir um `.md`.
>
> Se preferir não converter, pode subir o `.md` direto — a base de conhecimento
> aceita Markdown e a fala continua válida.

> Agora o segundo campo: a base de conhecimento. **[arrasta o PDF]**
>
> Vou subir um arquivo só: o guia de redação da empresa. **[o arquivo aparece na lista]**
>
> Um arquivo. Não dez.
>
> Eu subi esse porque é ele que define o que "certo" significa nessa empresa. Se eu subisse junto o organograma, o plano de metas e a apresentação institucional, eu não teria melhorado a revisão. Eu teria diluído o manual no meio de coisa que não tem nada a ver com revisar texto.
>
> **[aponta o indicador de capacidade]** E repara que tem um limite de espaço aqui. Quando encher, a resposta não é aumentar o plano. É limpar o que não deveria estar lá.

---

## 5 · Testando
**🖥️ TELA** — conversa nova dentro do Projeto &nbsp;&nbsp; ⏱️ 3:40 – 5:00

> Vamos testar. Vou abrir uma conversa dentro do Projeto e colar um comunicado bem ruim, de propósito. **[cola o texto de teste]**
>
> Antes de enviar, presta atenção no tamanho do meu pedido. **[aponta]** Duas palavras: "revisa esse". Sem contexto, sem formato, sem tom. Tudo isso já está no Projeto.
>
> **[envia]**
>
> **[quando responder]** E aí está. Vamos conferir se ele obedeceu.
>
> Três seções? **[aponta]** Problemas, sugestão, nota. Está lá.
>
> Ele usou o guia de estilo? **[aponta a citação]** Usou — apontou o "vimos por meio desta" e o "no que tange", que são termos que o guia proíbe.
>
> E esse é o ganho da coisa toda: o meu prompt tem duas palavras e a resposta tem qualidade de um prompt de vinte linhas. Multiplica isso por todo dia útil do ano.

---

## 6 · Gerando o dashboard
**🖥️ SLIDE 13** por ~15s → **🖥️ TELA** — conversa nova, fora do Projeto &nbsp;&nbsp; ⏱️ 5:00 – 6:40

> Segunda parte: Artifacts.
>
> **[slide 13]** Esse é o prompt que eu vou usar. Repara que ele não pede "faça um dashboard bonito". Ele especifica quatro coisas: a tecnologia, o visual, quais componentes e de onde vêm os dados.
>
> **[vai pra tela, conversa nova]** Importante: eu abri uma conversa nova, fora do Projeto. Se eu fizesse isso dentro do Revisor, as instruções de revisão iam atrapalhar.
>
> **[cola o prompt e envia]**
>
> **[enquanto gera]** Isso vai levar um tempinho, e é normal. Ele está montando a estrutura, depois os dados, depois os gráficos. Eu prefiro esperar quarenta segundos aqui do que passar duas horas montando isso à mão.
>
> **[quando renderizar]** Pronto. **[passa o mouse nos gráficos]** E não é imagem, é interativo — olha o valor aparecendo aqui.
>
> Ficou bom? Ficou. Ficou pronto? Não. E é aqui que a maioria das pessoas para, achando que a primeira versão é a resposta. A primeira versão é o rascunho.

---

## 7 · Iterando
**🖥️ TELA** — painel do artifact &nbsp;&nbsp; ⏱️ 6:40 – 7:30

> Vou fazer um ajuste. **[cola o prompt de ajuste]**
>
> Presta atenção em como eu pedi: eu não descrevi o dashboard inteiro de novo. Eu falei só o que muda — "adiciona um filtro por canal".
>
> Essa é a regra da iteração: fale da diferença, não do todo. Quem reescreve o pedido completo toda vez acaba perdendo o que já estava bom.
>
> **[quando atualizar, usa o filtro]** E olha aí, funcionando. Troco o canal e os números recalculam. E ele manteve tudo que já existia.

---

## 8 · Publicando
**🖥️ TELA** — botão de publicar / link gerado &nbsp;&nbsp; ⏱️ 7:30 – 8:10

> Última coisa sobre artifact: publicar. **[aponta o botão]**
>
> Um clique aqui e isso vira um link. Um link que a sua chefia abre no celular, sem ter conta no Claude, sem instalar nada.
>
> **[publica e mostra o link]**
>
> E aqui vai o aviso mais importante desse vídeo: publicado é público pra quem tiver o link. Não é "só quem eu mandei". Esse dashboard aqui tem dado inventado, por isso eu publiquei tranquilo.
>
> A pergunta que eu faço antes de clicar é essa: eu imprimiria isso e deixaria em cima da mesa de um café? Se a resposta for não, não publica.

---

## 9 · Subindo a planilha
**🖥️ TELA** — anexo do CSV, conversa nova &nbsp;&nbsp; ⏱️ 8:10 – 9:20

> Última parte: arquivo de verdade.
>
> **[anexa o CSV]** Essa é uma planilha de pedidos de uma loja de acessórios de celular, dois meses de vendas em dois marketplaces.
>
> **[cola o prompt e envia]** E eu não pedi "analisa essa planilha". Eu pedi três coisas específicas: o panorama por canal, qual produto lidera, e qual produto caiu.
>
> **[quando responder]** Vamos conferir.
>
> **[aponta os números]** Cinquenta e dois pedidos, oito mil e cento e cinco reais. Ticket médio quase o dobro no Mercado Livre em relação à Shopee.
>
> E olha esse detalhe, que é o mais interessante: o produto que mais gerou receita não é o que mais vendeu em unidades. São dois produtos diferentes. Se eu tivesse perguntado só "qual o campeão", eu teria uma resposta e perdido a outra.
>
> E repara no que eu estou fazendo agora, que é o hábito que eu mais quero que você leve daqui: eu estou conferindo. Eu abri essa planilha antes de gravar. Eu sei o que tem lá dentro. Se ele errasse, quem ia perceber era eu — não ele.

---

## 10 · Fecho
**🖥️ SLIDE 11** &nbsp;&nbsp; ⏱️ 9:20 – 10:00

> E terminamos. Projeto criado com instruções e documento, testado com texto real. Dashboard gerado, ajustado e publicado. Planilha analisada e conferida.
>
> Isso é o essencial do chat do Claude. Com essas quatro coisas você já resolve a maior parte do que aparece no dia a dia.
>
> Meu exercício pra você: cria um Projeto do seu trabalho. Não copia o meu — pensa numa tarefa que você faz toda semana explicando o mesmo contexto, e transforma aquilo num Projeto.
>
> No próximo módulo a pergunta muda de lugar. Até aqui, você pede e ele responde — você sempre na frente do computador. E se ele fizesse sozinho, no horário certo, sem você pedir? Isso chama Cowork. Te vejo lá.
