# Chat · Vídeo B — Mão na massa

**Alvo:** 10 min · **Slides:** 5 e 13 (apoio) do deck `02-chat.html`

Um fluxo só, do começo ao fim: **criar um Projeto → usar → gerar um dashboard → subir um arquivo.**

---

## Preparação

- [ ] Plano **Pro** ativo (Projetos não existem no gratuito)
- [ ] `recursos/guia-de-estilo-tiops.md` exportado para **PDF**, na pasta Downloads
- [ ] `recursos/vendas-exemplo.csv` na pasta Downloads
- [ ] Nenhum Projeto chamado "Revisor de Conteúdo" na conta
- [ ] Todos os prompts copiados em bloco de notas

---

## Roteiro

### Abertura · **fala literal**

> "Vídeo prático. Em dez minutos a gente cria um Projeto do zero, testa,
> gera um dashboard e sobe uma planilha pra análise.
>
> Abre o Claude do seu lado e faz junto — esse aqui não funciona só assistindo."

---

### 1. Criando o Projeto `[TELA]` · ~3 min

- Novo Projeto → nome **Revisor de Conteúdo**.
- Cole as **Instruções** (abaixo). Comente três linhas enquanto cola:
  - o papel ("você é um revisor sênior")
  - o formato fixo (3 seções)
  - > "e essa aqui é a mais importante: *se o texto estiver bom, diga que está bom*. Sem isso ele inventa problema pra te agradar."
- Suba o **PDF do guia de estilo** na base de conhecimento.
  - > Um arquivo, não dez. Base enxuta funciona melhor.

---

### 2. Testando `[TELA]` · ~2 min

- Abra uma conversa **dentro** do Projeto e cole o **Texto de teste**.
- Antes de enviar: > "repara que meu pedido tem duas palavras. Todo o resto já está no Projeto."
- Quando responder, confira em voz alta: veio nas 3 seções? citou o guia?

---

### 3. Gerando um Artifact `[TELA]` · ~3 min

- Abra uma conversa **nova**, fora do Projeto.
- Cole o **Prompt do dashboard**. Narre enquanto gera.
- Quando renderizar: passe o mouse nos gráficos.
- Faça **uma** iteração — cole o **Prompt de ajuste**.
  - > "Repara que eu só falei o que muda, não repeti o pedido inteiro. É assim que se itera."
- Mostre onde publica e que gera link público.
  - > "Confere o conteúdo antes. Link publicado, qualquer um com ele vê."

---

### 4. Subindo um arquivo `[TELA]` · ~2 min

- Anexe `vendas-exemplo.csv` e cole o **Prompt da planilha**.
- Confira os números contra o gabarito abaixo.
- > "Eu abri essa planilha antes. É por isso que eu sei se ele acertou."

---

### Fecho · **fala literal**

> "Pronto: Projeto criado com instruções e documento, artifact gerado e
> publicado, planilha analisada. Isso é o essencial do chat.
>
> No próximo módulo a pergunta muda: e se ele fizesse isso sozinho, no horário
> certo, sem você pedir? Chama Cowork. Te vejo lá."

---

## Instruções do Projeto

```
Você é um revisor sênior de conteúdo corporativo.

Regras:
- Sempre responda em 3 seções: Problemas → Sugestão → Nota (1 a 10)
- Tom profissional e construtivo
- Se o texto estiver bom, diga que está bom (não invente problemas)
- Use o guia de estilo da base de conhecimento como referência
```

## Texto de teste

```
Revise este comunicado.

Prezados colaboradores, vimos por meio desta informar que a partir do dia 15
do corrente mês estaremos implementando de forma gradual e progressiva um novo
procedimento no que tange ao processo de solicitação de férias, o qual passará
a ser realizado exclusivamente através do sistema, sendo certo que solicitações
realizadas por e-mail não mais serão consideradas válidas.
```

## Prompt do dashboard

```
Crie um dashboard de vendas em HTML com Chart.js via CDN, como artifact.

Loja de acessórios para celular que vende em Mercado Livre e Shopee.
- 4 cards: Receita total, Ticket médio, Pedidos, Produto campeão
- Gráfico de barras: receita por mês (12 meses)
- Gráfico de rosca: participação de cada canal
- Tema escuro, valores em R$, responsivo
- Dados fictícios realistas
```

## Prompt de ajuste

```
Adicione um filtro no topo para alternar entre "Todos", "Mercado Livre" e
"Shopee". Os cards e o gráfico de barras devem recalcular. Mantenha o resto.
```

## Prompt da planilha

```
A planilha anexa tem os pedidos de uma loja de acessórios de celular.
Responda em tabela:
1. Receita total, número de pedidos e ticket médio — geral e por canal
2. Qual produto gerou mais receita e qual vendeu mais unidades
3. Qual produto caiu de junho para julho
```

### Gabarito — confira ao vivo

- **52 pedidos · R$ 8.105,20 · ticket médio R$ 155,87**
- Mercado Livre: 31 pedidos, ticket **R$ 194,97** — Shopee: 21 pedidos, ticket **R$ 98,14**
- Campeão de **receita**: Fone Bluetooth TWS Pro (R$ 3.987,90)
- Campeão de **unidades**: Cabo USB-C (50 un.) — **são produtos diferentes**, de propósito
- Em queda: Capa Silicone iPhone 14 — 21 unidades em junho, **2** em julho

---

## Plano B

- **Ele não seguiu as 3 seções?** Mostre e corrija a instrução ao vivo — vira conteúdo bom.
- **Dashboard em branco?** Peça: *"o dashboard está em branco, verifique se a biblioteca carregou e corrija"*.
- **Errou um número da planilha?** Ótimo momento: *"por isso eu confiro. Ele lê bem e erra às vezes — as duas coisas são verdade."*
- **Passou de 11 min?** Corte a iteração do dashboard (item 3).

---

## Edição

- Corte agressivamente as gerações — cada uma vira 2 ou 3 segundos.
- O prompt de duas palavras (item 2) grande na tela antes de enviar: é o argumento do vídeo.
- Revise o vídeo procurando dado sensível — o seletor de arquivos expõe sua pasta.
