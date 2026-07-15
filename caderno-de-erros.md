# Caderno de Erros

> **O arquivo mais importante do projeto.** Prova se ganha eliminando erro
> repetido, não acumulando conteúdo novo. Toda questão errada (ou acertada no
> chute) entra aqui NO MESMO DIA.

## Como registrar

Copie o template abaixo. Classifique a **causa** com honestidade — é ela que
diz o que fazer:

| Causa | O que significa | Ação corretiva |
| --- | --- | --- |
| 🔴 `CONCEITO` | Não sabia a matéria | Voltar à teoria do tópico |
| 🟠 `CONFUSÃO` | Sabia, mas troquei conceitos parecidos | Criar quadro comparativo / flashcard |
| 🟡 `DESATENÇÃO` | Li errado, cai em "EXCETO", pressa | Treinar leitura do comando da questão |
| 🔵 `CHUTE-SORTE` | Acertei sem saber (registrar também!) | Mesmo tratamento de CONCEITO |

**Revisão espaçada:** releia cada erro em +1 dia, +7 dias e +30 dias (marque as
datas). Erro revisto 3x sem reincidência pode ser arquivado.

---

## Template

```markdown
### [DISCIPLINA] Tópico — Banca/Ano — nº da questão ou link
- **Data:** 2026-__-__  |  **Causa:** CONCEITO | CONFUSÃO | DESATENÇÃO | CHUTE-SORTE
- **O que a questão cobrou:** ...
- **Por que errei:** ...
- **A regra/conceito correto (nas MINHAS palavras):** ...
- **Pegadinha para lembrar:** ...
- **Revisões:** R1: __/__ · R7: __/__ · R30: __/__
```

---

## Registros

### Exemplo — [BD] TRUNCATE × DELETE — Cesgranrio/2021
- **Data:** 2026-07-15 | **Causa:** CONFUSÃO
- **O que a questão cobrou:** qual comando permite ROLLBACK.
- **Por que errei:** no trabalho uso os dois sem pensar em transação implícita.
- **A regra correta:** `DELETE` é DML → pode rollback, dispara triggers, não
  reseta identity. `TRUNCATE` é DDL → commit implícito (Oracle), sem rollback,
  libera espaço, mais rápido. `DROP` remove a estrutura inteira.
- **Pegadinha para lembrar:** "TRUNCATE é DDL disfarçado de limpeza".
- **Revisões:** R1: __/__ · R7: __/__ · R30: __/__

<!-- Novos registros abaixo -->
