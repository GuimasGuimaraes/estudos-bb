# Plano de Estudos Estratégico — Agente de Tecnologia BB

> Versão melhorada do plano original (Gemini), corrigida com o cenário real de
> julho/2026: **banca indefinida** (Cesgranrio fora) e **edital sem previsão**.

## A tese central (continua válida)

Sua bagagem (PL/SQL, Java, Linux, Defesa Cibernética) é exatamente o core dos
Conhecimentos Específicos. Você **não** vai aprender TI do zero — vai:

1. **Blindar os Conhecimentos Básicos** (Português, Bancários, Atualidades,
   Estatística) — é onde candidato de TI reprova.
2. **Converter conhecimento prático em ponto de prova** — resolver questão até
   o padrão de cobrança virar automático.
3. **Garantir a redação** — ela é eliminatória e classifica; é o que separa
   "aprovado" de "aprovado dentro das vagas".

## O que mudou em relação ao plano original

| Plano original (Gemini) | Correção |
| --- | --- |
| Treinar "malícia da Cesgranrio" | Cesgranrio foi **descontratada** (jan/2026). Até sair a banca, treine multibanca: Cesgranrio (provas antigas do BB continuam sendo o melhor material), FGV e Cebraspe. FGV cobra código mais pesado; Cebraspe usa certo/errado — estilos bem diferentes. |
| Um cronograma único | **Duas fases**: pré-edital (construção de base, ritmo sustentável) e pós-edital (sprint de 2–4 meses, recalibrado pela banca e conteúdo reais). Estamos na fase pré-edital. |
| "Assine QConcursos ou TecConcursos" | Mantido, com preferência pelo **TecConcursos** para TI (comentários mais técnicos). Uma assinatura basta. |
| Revisão genérica ("flashcards/resumos") | **Revisão espaçada com regra fixa**: todo tópico estudado é revisto em 1 dia → 7 dias → 30 dias. O caderno de erros é a fonte da revisão, não os resumos. |
| Sem métrica de progresso | Toda semana registra: horas líquidas, questões resolvidas, % de acerto por disciplina. Sem número, não há como saber se está funcionando. |

## As regras do jogo (baseadas no último edital — confirmar no novo)

- Prova objetiva com Conhecimentos Básicos + Específicos; historicamente exige
  **mínimo de ~50% em cada bloco** e **não zerar nenhuma disciplina**.
- **Redação eliminatória** (nota mínima) e **classificatória** (desempata e
  sobe posição). Errar aqui anula meses de estudo de TI.
- Específicos valem mais pontos por questão — mas o corte real acontece nos
  Básicos, porque é onde todo mundo de TI é fraco e o teto é mais baixo.

## Estratégia por disciplina

### 1. Conhecimentos Bancários + Atualidades do Mercado Financeiro (prioridade nº 1)
É o conteúdo mais distante do seu dia a dia e o mais "decoreba lógica".

- **Método:** teoria em PDF/vídeo + resumo esquematizado próprio + questões no
  mesmo dia. Entenda a *lógica da regulação*, não decore listas soltas.
- **Mapa mínimo:** SFN (CMN → Bacen → CVM → Susep/Previc — quem normatiza ×
  quem supervisiona × quem opera), política monetária, Pix (regras e limites),
  Open Finance, LGPD aplicada a bancos, resoluções do Bacen sobre segurança
  cibernética (Res. 4.893), produtos bancários (CDB, poupança, fundos, crédito),
  ASG/ESG, prevenção à lavagem de dinheiro (Lei 9.613 + Circular 3.978).

### 2. Língua Portuguesa (prioridade nº 2)
- Mínimo **30 questões/semana**, misturando bancas enquanto não sai o edital.
- Foco: interpretação profunda, concordância, regência, crase, colocação
  pronominal, reescrita mantendo sentido, semântica no contexto.
- Todo erro vai ao caderno de erros com a regra gramatical anotada.

### 3. Probabilidade e Estatística
- Teoria só onde houver lacuna: descritiva (média/mediana/moda/desvio),
  probabilidade condicional, distribuições (binomial, normal, Poisson),
  amostragem, correlação e regressão linear.
- Depois disso, 100% questões.

### 4. Tecnologia da Informação (manutenção agressiva, não aprendizado)
**Regra de ouro mantida: zero teoria passiva de TI.** Só resolução de questões
comentadas + engenharia reversa do erro.

- **Banco de Dados:** questões de modelagem (MER/DER), formas normais (1FN–BCNF),
  SQL/PL-SQL, NoSQL (tipos: chave-valor, documento, coluna, grafo). Pegadinhas
  clássicas: TRUNCATE × DELETE × DROP (rollback/espaço), NULL em agregações e
  comparações, HAVING × WHERE, tipos de JOIN com linhas órfãs.
- **Java / Estrutura de Dados:** treinar leitura de código cronometrada —
  identificar output, erro de compilação, exceção. Atenção a: escopo, static ×
  instância, sobrecarga × sobrescrita, try-catch-finally (finally sempre
  executa?), String pool e imutabilidade, complexidade de estruturas
  (ArrayList × LinkedList × HashMap).
- **Segurança / Redes (sua zona de conforto — cuidado com excesso de confiança):**
  o risco é a *terminologia de concurso* divergir do jargão prático. Revisar:
  criptografia simétrica × assimétrica × hash × assinatura digital, PKI/ICP-Brasil,
  TLS/HTTPS, OSI × TCP/IP, portas padrão, firewall × IDS × IPS × WAF, OWASP Top 10,
  tipos de malware e ataques.
- **Linux / Git / DevOps:** chmod (numérico × simbólico), chown, grep/awk/sed,
  processos e pacotes; Git (merge × rebase, fluxo de branches); Docker/Kubernetes
  e CI/CD em nível conceitual; metodologias ágeis (Scrum, Kanban, XP, Lean).
- **Novidades prováveis no próximo edital:** computação em nuvem, APIs REST,
  microsserviços, mensageria (Kafka/RabbitMQ), IA/aprendizado de máquina
  (conceitos), Big Data. O BB cobrou isso em 2021 e a tendência só cresceu.

### 5. Língua Inglesa
- Baixo custo, não zerar: 5–10 questões/semana de interpretação de texto
  técnico. Sua leitura de documentação já resolve 90%.

### 6. Redação (a partir da semana 3, 1 por semana — inegociável)
- Estrutura fixa em [redacao/modelo-estrutura.md](../redacao/modelo-estrutura.md).
- 1 redação completa por semana, manuscrita, 30 linhas, cronometrada (1h).
- Temas prováveis em [redacao/temas.md](../redacao/temas.md).

## As duas fases

### Fase 1 — Pré-edital (agora → publicação)
- Ritmo sustentável: **3 blocos de 1h por dia útil** (manhã/tarde/noite) +
  fim de semana = **~18h líquidas/semana** (ver [cronograma](cronograma.md)).
- Objetivo: Bancários e Português em nível de prova, TI aquecida com questões,
  1 simulado de prova antiga a cada 2 semanas, 1 redação/semana.
- Critério de "tópico dominado": **≥ 80% de acerto em ≥ 20 questões** do tópico
  → marcar no [edital verticalizado](edital-verticalizado.md).

### Fase 2 — Pós-edital (sprint)
- Reler o edital linha a linha e cortar/adicionar tópicos no verticalizado.
- Filtrar TODAS as questões pela banca definida; aprender o estilo dela em 2 semanas.
- Simulado completo **toda semana**, no horário real da prova.
- Últimas 2 semanas: só revisão do caderno de erros + leis secas + simulados.

## Plano de ação imediato (próximos 30 dias)

- [ ] Assinar TecConcursos (ou QConcursos).
- [ ] Baixar edital + provas de Agente de Tecnologia BB 2021 e 2023 (Cesgranrio).
- [ ] **Simulado diagnóstico neste fim de semana**: prova 2021 na íntegra, 5h
      cronometradas, sem consulta. Registrar em [simulados](../simulados/registro-simulados.md).
- [ ] Analisar o diagnóstico e calibrar:
  - TI ≥ 75% → zerar teoria de TI, redirecionar tudo para Básicos.
  - TI < 75% → manter 40% do tempo em questões de TI e mapear os buracos.
  - Bancários/Português baixos → é o esperado; eles são o foco dos 3 primeiros meses.
- [ ] Montar resumo esquematizado do SFN (1ª entrega de Bancários).
- [ ] Escrever a 1ª redação na semana 3.
