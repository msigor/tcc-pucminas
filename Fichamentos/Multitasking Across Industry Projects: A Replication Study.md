# Multitasking Across Industry Projects: A Replication Study

**Karina Kohl; Bogdan Vasilescu; Rafael Prikladnicki.** "Multitasking Across Industry Projects: A Replication Study," in *Proceedings of the 13th International Workshop on Cooperative and Human Aspects of Software Engineering (CHASE 2020), co-located with ICSE*, pp. 1–8, Seoul, South Korea, May 2020. doi: [10.1145/1122445.1122456](https://doi.org/10.1145/1122445.1122456)&#x20;

---

## 1. Fichamento de Conteúdo

Este artigo apresenta uma **replicação conceitual** de um estudo anterior de Vasilescu et al. (ICSE 2016) sobre **multitarefa de desenvolvedores**. Enquanto o original analisava desenvolvedores de projetos open source (GitHub), esta replicação foca em **desenvolvedores de uma empresa de software no Brasil**, usando dados de **157.658 commits em 2.453 repositórios GitLab** e **entrevistas semiestruturadas com 10 desenvolvedores**.

**Resultados principais**:

* **Níveis de multitarefa**: Desenvolvedores da indústria multitaskam em média em **2,41 projetos/semana**, similar a OSS developers (2,57). Em 22,37% das semanas analisadas houve multitarefa (contra 37% em OSS).
* **Razões para multitarefa**: suporte a outros times, incidentes de produção, dependências entre equipes, reuniões e até procrastinação/ansiedade.
* **Impacto na produtividade**: Trabalhar em menos projetos e manter foco repetitivo dia a dia **aumenta a produtividade**. Maior diversidade de linguagens e maiores context-switches correlacionaram-se negativamente. **Multitarefa em excesso não trouxe ganhos significativos**.
* **Percepção dos desenvolvedores**: interrupções curtas (< 3 min) não impactam produtividade; acima disso geram perda de foco e sensação de “deixar a tarefa para trás”. Desenvolvedores relataram **aumento de stress e queda de felicidade** quando multitarefa é frequente.
* **Comparação com OSS**: Em OSS, multitarefa é mais comum e vista como oportunidade de contribuição/reputação; na indústria, é frequentemente **imposta** por demandas externas (bugs, suporte, prioridades de negócio).

Conclusão: a multitarefa é inevitável em SE, mas deve ser gerida com atenção ao custo cognitivo. Replicações como essa fortalecem a evidência de que o **excesso de context-switching compromete produtividade e bem-estar**.

---

## 2. Fichamento Bibliográfico

* **Multitarefa em SE**: prática comum para otimizar alocação, mas com custos cognitivos (pp. 1–2).
* **Dimensões analisadas**:

  * *ProjectsPerDay* (número de projetos distintos por dia)
  * *Weekly Focus (SFocus)* – dispersão de atenção entre projetos
  * *Day-to-Day Focus (SSwitch)* – repetitividade nos padrões de mudança de contexto (pp. 3–4).
* **Dataset da replicação**: 1.213 devs, 282 projetos, 157.658 commits, período 2018–2019, mais entrevistas qualitativas (pp. 3–4).
* **Resultados quantitativos**: Focar em menos projetos aumenta produtividade; multitarefa alta (AvProjectsPerDay) não é significativa (pp. 8).
* **Resultados qualitativos**: interrupções curtas toleráveis, mas interrupções longas geram dificuldade de retomar tarefas; stress aumenta em cenários de multitarefa recorrente (pp. 12–14).

---

## 3. Fichamento de Citações

* *“We found out that industry developers multitask as much as OSS developers focusing more on fewer projects, and working more repetitively from one day to the next is associated with higher productivity.”*
* *“Short context change, less than three minutes, did not impact results… however, longer interruptions bring a feeling of leaving the previous tasks behind.”*
* *“Dependencies, personal interests, and social relationships are common reasons to multitask; in industry, production incidents and support requests add additional pressure.”*
* *“Happiness decreases and stress levels increase at some point when multitasking frequently happens, leaving developers frustrated.”*
* *“Focusing more (on fewer projects) and working more repetitively is associated with higher productivity, but there is no effect for higher multitasking.”*