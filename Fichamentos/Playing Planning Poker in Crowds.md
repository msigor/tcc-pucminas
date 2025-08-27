# Playing Planning Poker in Crowds: Human Computation of Software Effort Estimates

Mohammed Alhamed; Tim Storer. "Playing Planning Poker in Crowds: Human Computation of Software Effort Estimates," in *Proceedings of the 43rd IEEE/ACM International Conference on Software Engineering (ICSE)*, pp. 1–12, 2021. doi: [10.1109/ICSE43902.2021.00014](https://doi.org/10.1109/ICSE43902.2021.00014)&#x20;

---

## 1. Fichamento de Conteúdo

O artigo discute a dificuldade de realizar **estimativas de esforço em software**, um problema recorrente tanto em projetos comerciais quanto em projetos de código aberto. Embora o **Planning Poker**, prática comum em métodos ágeis, tenha mostrado bons resultados ao reunir especialistas, ele é caro e pouco escalável, já que depende da disponibilidade de um grupo de desenvolvedores experientes. Para contornar esse limite, os autores propõem o **Crowd Planning Poker (CPP)**, uma adaptação do método tradicional para trabalhadores de crowdsourcing na plataforma **Amazon Mechanical Turk**. No CPP, cada trabalhador recebe descrições de tarefas de software, fornece uma estimativa categórica (de horas a semanas) e uma justificativa. Estimativas de baixa qualidade são filtradas por um modelo automatizado. O estudo envolveu mais de **5.000 trabalhadores** e **39 tarefas reais** de projetos como Apache, JBoss e Spring. Os resultados mostraram que, apesar da variabilidade, os **trabalhadores leigos organizados em grupo conseguem atingir níveis de precisão semelhantes aos de especialistas** e a um custo muito inferior (média de **US\$ 1,99 por estimativa**, contra US\$ 20 estimado para equipes de especialistas). Além disso, alguns participantes ofereceram insights valiosos sobre resolução das tarefas, mostrando que a técnica pode ir além da estimativa e apoiar também o triagem de issues. A pesquisa conclui que o CPP é viável para lidar com grandes backlogs, especialmente em projetos OSS, embora persistam desafios relacionados à qualidade das estimativas e ao risco de informações sensíveis serem expostas.

---

## 2. Fichamento Bibliográfico

* **Planning Poker**: método de estimativa em times ágeis baseado em consenso e cartas de esforço; reduz viés e melhora precisão em comparação com estimativas individuais (pp. 2–3).
* **Crowd Planning Poker (CPP)**: versão adaptada para plataformas de crowdsourcing, com rodadas iterativas, justificativas obrigatórias e filtros de qualidade (pp. 4–6).
* **Qualidade das estimativas**: filtrada por análise de comportamento do trabalhador (tempo gasto, cliques, justificativa) e classificador automático baseado em Random Forest (pp. 6–7).
* **Resultados principais**: em 30 ensaios, a acurácia dos crowds foi estatisticamente semelhante à dos especialistas (Mann-Whitney U test, p=0.4861), com redução de custos (pp. 7–8).
* **Benefício adicional**: além das estimativas, os trabalhadores muitas vezes forneceram sugestões úteis para resolução dos problemas, ampliando o valor do processo (p. 8).

---

## 3. Fichamento de Citações

* *“Our results show that a carefully organised and selected crowd of workers can produce effort estimates that are of similar accuracy to those of a single expert.”*
* *“Planning Poker depends upon the availability of a team of experts… making it impractical for large scale or open source projects.”*
* *“Crowd Planning Poker (CPP) was implemented on Mechanical Turk, with each worker providing a categorical estimate and a justification.”*
* *“The Mann-Whitney U Test indicated no statistically significant difference between expert and crowd estimates.”*
* *“Conducting the experiment trials resulted in an average cost of \$1.99 to produce a final estimate for one issue.”*
* *“An additional benefit was that many workers provided useful insights into how to resolve the task, beyond just estimating effort.”*
