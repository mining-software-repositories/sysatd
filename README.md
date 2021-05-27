# sysatd
Analysis of Architectural Technical Debt

1. Dados dos repositórios analisados    

2. Lista dos commits de cada versão analisada

3. Análise das versão v1 (hadoop-branch-2.0.5)

3.2 Criar arquivo csv para complexidade dos arquivos de v1
3.3 Filtrar apenas os arquivos .java de v1
3.4 Lista de métricas de code churn para os arquivos de v1
3.5 Total code churn for each file in v1
3.6 Criar arquivo csv para code churn dos arquivos de v1
3.6.1 Filtrar apenas arquivos .java

4. Análise das versão v2 (hadoop-branch-3.0.0)
4.2 Criar arquivo csv para complexidade dos arquivos de v2
4.3 Filtrar apenas os arquivos .java de v2
4.4 Lista de métricas de code churn para os arquivos de v2
4.5 Total code churn for each file in v2
4.6 Criar arquivo csv para code churn dos arquivos de v2
4.6.1 Filtrar apenas arquivos .java

5. Análise das versão 3 (hadoop-branch-3.1)
5.2 Criar arquivo csv para complexidade dos arquivos de v3
5.3 Filtrar apenas os arquivos .java de v3
5.4 Lista de métricas de code churn para os arquivos de v3
5.5 Total code churn for each file in v3
5.6 Criar arquivo csv para code churn dos arquivos de v3
5.6.1 Filtrar apenas arquivos .java

6. Análise das versão 3 (hadoop-branch-3.2)
6.2 Criar arquivo csv para complexidade dos arquivos de v4
6.3 Filtrar apenas os arquivos .java de v4
6.4 Lista de métricas de code churn para os arquivos de v4
6.5 Total code churn for each file in v4
6.6 Criar arquivo csv para code churn dos arquivos de v4
6.6.1 Filtrar apenas arquivos .java

Dataframes with Cyclomatic Complexity
Dataframes with Code Churn
Dataframes with cyclomatic complexity, code churn and ccnXchurn

Obs: papers usados para inferir o impacto de esforço de manutenção usando a Complexidade Ciclomática e Code Churn:
1. Nagappan, Nachiappan, and Thomas Ball. "Use of relative code churn measures to predict system defect density." Proceedings of the 27th international conference on Software engineering. 2005.

2. Faragó, Csaba, Péter Hegedűs, and Rudolf Ferenc. "Cumulative code churn: Impact on maintainability." 2015 IEEE 15th International Working Conference on Source Code Analysis and Manipulation (SCAM). IEEE, 2015.

3. Olsson, Tobias, Morgan Ericsson, and Anna Wingkvist. "The relationship of code churn and architectural violations in the open source software JabRef." Proceedings of the 11th European Conference on Software Architecture: Companion Proceedings. 2017.

4. Shin, Yonghee, et al. "Evaluating complexity, code churn, and developer activity metrics as indicators of software vulnerabilities." IEEE transactions on software engineering 37.6 (2010): 772-787.