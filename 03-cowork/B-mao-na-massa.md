# Cowork · Vídeo B — Mão na massa

**Alvo:** 9 min · **Slides:** 5 e 6 (apoio) do deck `03-cowork.html`

Uma automação, do zero ao agendamento: **resumo diário de e-mails.**

> ⚠️ **Faça um ensaio completo antes de gravar.** Você precisa saber onde ficam
> os botões e quanto tempo a execução leva. Interface nova não se improvisa em
> vídeo.

---

## Preparação

- [ ] Cowork acessível, conector de e-mail **já autorizado** (não grave a tela de login)
- [ ] Uma **conta de e-mail de demonstração** com 5 a 10 mensagens fictícias —
      **nunca** sua caixa real
- [ ] Nenhuma automação com o mesmo nome já criada
- [ ] Descrição da tarefa copiada em bloco de notas

⚠️ **Privacidade:** e-mail aparece na tela. Use conta de teste. Se não tiver,
troque o exemplo por algo sem dado pessoal — um resumo de página web, por exemplo.

---

## Roteiro

### Abertura · **fala literal**

> "Vamos montar uma automação de verdade: todo dia de manhã, o Claude olha os
> e-mails do dia anterior e me manda um resumo do que precisa de resposta.
>
> São quatro passos: descrever a tarefa, conectar a ferramenta, agendar o
> horário e testar. Vamos."

---

### 1. Descrever a tarefa `[TELA]` · ~2min30

- Crie a automação e cole a **Descrição da tarefa** (abaixo).
- Comente enquanto cola:
  - > "Repara que eu escrevi como se estivesse explicando pra alguém que entrou hoje na empresa: o que olhar, o que fazer e como me entregar."
- Aponte que a estrutura é a mesma do prompting do módulo passado: contexto, tarefa, formato.

---

### 2. Conectar a ferramenta `[TELA]` · ~1min30

- Mostre onde escolhe o conector e que ele já está autorizado.
- > "Conecta só o que essa tarefa precisa. Se ela só lê e-mail, não dá acesso de envio."
- Se a interface mostrar o escopo do acesso, **mostre** — é informação relevante para o aluno.

---

### 3. Agendar `[TELA]` · ~1min30

- Defina o horário: todo dia útil, 8h.
- Mostre onde se define frequência e onde se pausa depois.
- > "Isso aqui é a diferença entre uma ferramenta que você usa e uma que trabalha pra você."

---

### 4. Testar `[TELA]` · ~2min30

- **Execute na hora**, sem esperar o horário — mostre onde fica esse botão.
- Acompanhe a execução e mostre o resultado.
- Abra o histórico/log: quando rodou, o que fez, se deu erro.
- > "Sempre teste manualmente antes de confiar no agendamento. Automação que você nunca viu rodar é aposta, não automação."

---

### Fecho · **fala literal**

> "Pronto: tarefa descrita, ferramenta conectada, horário definido e testada.
> Ela roda amanhã sozinha.
>
> Meu conselho pra começar: escolha uma tarefa chata, repetitiva e de baixo
> risco. Nada que mande mensagem pra cliente na primeira semana.
>
> No próximo módulo a gente ensina o Claude a ser especialista em alguma coisa
> sua. Chama Skills. Te vejo lá."

---

## Descrição da tarefa

```
Todo dia útil às 8h, faça o seguinte:

1. Leia os e-mails recebidos desde as 8h do dia anterior.
2. Ignore newsletters, notificações automáticas e propaganda.
3. Separe em três grupos:
   - PRECISA DE RESPOSTA HOJE
   - PODE ESPERAR
   - SÓ INFORMATIVO
4. Para cada e-mail dos dois primeiros grupos, escreva uma linha:
   quem enviou, o assunto e o que estão pedindo.

Formato: lista curta, no máximo 15 linhas no total.
Se não houver nada relevante, responda apenas "sem pendências".
NÃO responda nenhum e-mail. Apenas resuma.
```

> A última linha é de propósito: **restrição explícita**. Comente isso no vídeo —
> automação que age sem você mandar é o erro mais caro de quem está começando.

---

## Plano B

- **Não deu pra conectar e-mail?** Troque por uma automação sem dado pessoal:
  "todo dia, resuma as novidades desta página e me entregue em 5 bullets".
  O fluxo dos 4 passos é idêntico.
- **A execução demorou muito?** Marque `[CORTE]` e mostre o resultado pronto.
- **Deu erro na execução?** Grave. Mostrar o log e o erro é conteúdo melhor que
  a execução perfeita — é o que o aluno vai encontrar.
- **Passou de 10 min?** Corte o histórico/log (item 4) e mencione no fecho.

---

## Edição

- Borre remetentes, assuntos e endereços de e-mail — mesmo sendo conta de teste.
- O momento da execução manual é o clímax: mostre inteiro, sem corte no meio.
- A tela de agendamento merece **zoom** — é o conceito central do módulo.
