# Skill de demonstração — `resumo-reuniao`

Skill pronta para instalar, usada na **cena 5 e na cena 6 do vídeo Skills A**.

Ela existe porque a conta usada na gravação pode não ter as skills embutidas
disponíveis. Esta aqui você instala em qualquer conta.

---

## Por que essa skill

A cena 5 precisa provar uma coisa só: **a skill entra sozinha, sem ser chamada
pelo nome.** Então ela precisa de três características, e esta tem as três:

1. **Gatilho natural** — "resume essa reunião" é um pedido que qualquer pessoa
   faria sem saber que existe skill.
2. **Saída visivelmente estruturada** — três seções com emoji e uma tabela. Fica
   óbvio na tela que o formato não foi pedido.
3. **Simples de explicar** — cabe inteira em uma tela de editor, o que serve
   para a cena 6.

---

## Como instalar

### No claude.ai

1. Vá até a área de **Skills** nas configurações da conta.
2. Escolha adicionar/criar uma skill.
3. Envie o arquivo `SKILL.md` desta pasta (ou cole o conteúdo dele).

> ⚠️ O caminho exato do menu muda entre versões da interface. Se não achar de
> primeira, procure por "Skills" ou "Capacidades" nas configurações.

### No Claude Code

Copie a pasta para o diretório de skills do projeto ou do usuário:

```bash
# no projeto
mkdir -p .claude/skills
cp -r skill-demo-resumo-reuniao .claude/skills/resumo-reuniao

# ou global, para valer em qualquer projeto
cp -r skill-demo-resumo-reuniao ~/.claude/skills/resumo-reuniao
```

---

## Como testar antes de gravar

Abra uma conversa nova e cole o conteúdo de
[`../anotacoes-reuniao.md`](../anotacoes-reuniao.md) precedido de:

```
Resume essa reunião pra mim.
```

**Deu certo se:** a resposta vier nas três seções (Decisões, Pendências,
Ficou para depois), com tabela nas pendências e a linha de risco no fim —
sem você ter pedido formato nenhum.

**Deu errado se:** vier um resumo em texto corrido. Nesse caso a skill não foi
acionada. Confira se ela está ativa na conta e teste de novo.

⚠️ **Ensaie antes do REC.** Você precisa saber que ela ativa antes de gravar,
porque o argumento da cena depende disso acontecer na tela.

---

## O que a skill ensina, de propósito

Duas regras dela são material didático para o vídeo B:

- *"Não invente responsável"* e *"não invente prazo"* — é a mesma disciplina
  contra alucinação que aparece no módulo de Chat, agora escrita como regra
  permanente.
- A seção **O que evitar** existe em toda skill boa. É onde você registra o erro
  que já cansou de corrigir.
