# Roteiros de Gravação — Curso Introdutório Claude

Roteiros e guia de condução para a **gravação em vídeo** dos módulos sob
responsabilidade do **Guilherme**: **Chat**, **Cowork** e **Skills**.

Cada micro-aula tem roteiro com fala literal nos pontos críticos, checklist de
preparação, prompts prontos para copiar, plano B para quando a demonstração
falhar e notas de edição.

---

## Relação com o material do curso

Este repositório contém **apenas os roteiros de gravação**. O material didático
do curso — `modulos/`, `slides/`, `artigos/`, `exercicios/` — vive em
repositório separado e **não foi alterado** por este trabalho.

Cada roteiro indica, no cabeçalho, qual seção do módulo e quais slides ele
cobre, usando o caminho no repositório do curso. Exemplo:

```
Material base: curso-iniciante/modulos/02-chat/README.md
Deck:          curso-iniciante/slides/02-chat.html — 14 slides
```

Como os slides foram gerados a partir dos READMEs dos módulos, **1 slide
corresponde a uma seção de 10 a 30 min** — enquanto cada vídeo tem 7 a 10 min.
Alguns slides, portanto, servem a mais de uma micro-aula. Onde isso acontece
está mapeado no README de cada módulo.

---

## Como usar

1. Leia este arquivo uma vez — convenções, setup e os erros que custam regravação.
2. Abra o README do módulo que vai gravar, para ver o mapa das aulas e a ordem recomendada.
3. Abra **um arquivo de micro-aula por gravação**. Cumpra o checklist de preparação antes de apertar REC.
4. Anote no próprio roteiro o que não funcionou. É esse retorno que calibra os próximos módulos.

---

## Status

| Módulo | Micro-aulas | Tempo de vídeo | Status |
|--------|-------------|----------------|--------|
| [02 — Chat](02-chat/README.md) | 10 | ~80 min | ✅ Roteiros prontos |
| 03 — Cowork | ~8 | ~65 min | ⏳ Aguardando validação do piloto |
| 05 — Skills | ~13 | ~105 min | ⏳ Aguardando validação do piloto |

**Total previsto:** ~31 micro-aulas · ~4h10 de vídeo.

O módulo de Chat é o **piloto**. Grave 1 ou 2 aulas dele, avalie o formato e
me diga o que ajustar — só depois eu escrevo Cowork e Skills no mesmo padrão.

---

## Convenções do roteiro

Todo arquivo de micro-aula usa as mesmas marcações. Aprenda uma vez, vale para
todas.

| Marcação | O que significa |
|----------|-----------------|
| `[SLIDE 6]` | Coloque o slide 6 do deck do módulo em tela cheia |
| `[TELA: claude.ai]` | Corte para a tela real do Claude (compartilhamento de tela) |
| `[TELA: destaque]` | Continua na tela, mas aponte/amplie o elemento citado |
| `> "texto entre aspas"` | **Fala literal.** Leia como está escrito |
| `- bullet` | **Fala livre.** Narre com suas palavras enquanto opera |
| `⏱ 1:30` | Marca de tempo aproximada dentro do vídeo |
| `⚠️` | Ponto onde a demo costuma falhar — veja o Plano B |

**Regra de ouro da fala literal:** abertura, definição de conceito, transição e
fecho vêm escritos porque são os trechos onde travar custa caro na edição. O
resto é seu.

---

## Setup de gravação (uma vez, antes de tudo)

### Ambiente físico
- [ ] Microfone testado, gravação de 30s ouvida com fone
- [ ] Ambiente sem eco e sem ruído de fundo (ar-condicionado, notificação)
- [ ] Celular no silencioso, fora da mesa

### Ambiente digital
- [ ] Resolução da tela em **1920×1080** (não use ultrawide — corta na edição)
- [ ] Zoom do navegador em **125%** (o texto do Claude fica legível no vídeo)
- [ ] **Todas as notificações desligadas** (Windows: Assistente de Foco / Não Perturbe)
- [ ] Barra de favoritos limpa ou escondida (`Ctrl+Shift+B`)
- [ ] Navegador em **janela limpa e dedicada** — sem abas pessoais visíveis
- [ ] Perfil do navegador sem extensões que poluam a tela

### Privacidade — checar antes de cada gravação
- [ ] Nenhum dado real de cliente, CPF, e-mail pessoal ou chave de API na tela
- [ ] Histórico lateral de conversas do Claude sem títulos sensíveis
- [ ] Nome de conta / e-mail no canto: aceitável se for o corporativo, caso
      contrário use um perfil de demonstração

### Slides
Os decks estão em `curso-iniciante/slides/*.html`. Abra no navegador e use
`F11` para tela cheia. Cada `<section>` é um slide — role com `Page Down`.

Para exportar em PDF: `Ctrl+P` → Salvar como PDF (o CSS já tem
`page-break-after` configurado).

---

## Padrão de cada micro-aula

Todo vídeo segue a mesma espinha, mesmo quando o conteúdo muda:

```
[0:00] GANCHO      15-30s   Slide de título. Uma frase que diz o que o aluno
                            vai conseguir fazer ao final. Sem "olá pessoal,
                            tudo bem, hoje nós vamos".
[0:30] CONCEITO    1-2 min  Slide. O mínimo de teoria necessário.
[2:00] DEMO        4-6 min  Tela do Claude. Fazendo de verdade.
[7:00] FECHO       30-45s   Slide. O que ficou pronto + gancho da próxima aula.
```

**Duração alvo: 7 a 10 min.** Se passar de 11, corte a demo — não corte o fecho.

---

## Nomenclatura dos arquivos de vídeo

Grave e exporte com este padrão, para o material bater com o roteiro:

```
M02-A01-primeiros-passos.mp4
│   │   └── slug da aula (igual ao nome do arquivo do roteiro)
│   └────── número da aula dentro do módulo
└────────── número do módulo
```

---

## Recursos de apoio

Arquivos usados nas demonstrações estão em [`recursos/`](recursos/):

| Arquivo | Usado em | Para quê |
|---------|----------|----------|
| [`vendas-exemplo.csv`](recursos/vendas-exemplo.csv) | 02.07, 02.09 | Upload e análise de dados de vendas |
| [`guia-de-estilo-tiops.md`](recursos/guia-de-estilo-tiops.md) | 02.05 | Base de conhecimento do Projeto "Revisor" |

⚠️ **Antes de gravar a aula 02.05:** exporte `guia-de-estilo-tiops.md` para PDF
(abra no VS Code → Markdown PDF, ou cole no Word → Salvar como PDF). O upload
na base de conhecimento fica mais convincente com um PDF de verdade.

---

## Erros que custam regravação

Levantados na preparação deste material — leia uma vez antes da primeira gravação:

1. **Não leia o slide em voz alta.** O aluno já lê. O slide é a âncora visual;
   sua fala é a camada que o slide não tem.
2. **Não deixe silêncio enquanto o Claude responde.** Ou você narra o que
   espera ver, ou marca `[CORTE]` para a edição. Silêncio de 20s mata retenção.
3. **Não prometa o que a aula não entrega.** Se o gancho diz "você vai publicar
   um dashboard", o vídeo termina com o dashboard publicado.
4. **Não improvise prompt na frente da câmera.** Todo prompt demonstrado já
   está escrito no roteiro, testado. Cole, não digite do zero — digitar 8
   linhas em tela é tempo morto.
5. **Nomes de modelo mudam.** Se citar o modelo em uso, confira o seletor no dia
   da gravação. Prefira falar "o modelo mais capaz disponível no seu plano" a
   fixar um nome que envelhece em três meses.
6. **Uma aula, uma ideia.** Se você sentiu que a aula tem dois assuntos, ela tem
   — e vira duas.

---

**Tiops Tecnologia LTDA**
