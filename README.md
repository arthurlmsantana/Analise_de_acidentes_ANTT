# Análise de dados via Python/SQL aplicada a acidentes de trânsito registrados no site oficial da ANTT (Bahia, ano de 2024).

No complexo mundo da logística, onde eficiência e segurança são essenciais, a análise de dados emerge como uma ferramenta indispensável para entender padrões, identificar áreas de melhoria e tomar decisões estratégicas fundamentadas. Neste artigo, mostro uma análise de dados aplicados a acidentes de trânsito do estado da Bahia no ano de 2024 via Python/ SQL, utilizando conjuntos de dados disponíveis no site da ANTT (Agência Nacional de Transportes Terrestres).

A logística desempenha um papel vital em todas as esferas da economia, desde a movimentação de mercadorias até o transporte de pessoas. No entanto, junto com os benefícios do transporte eficiente, vêm os desafios da segurança viária. Os acidentes de trânsito não apenas representam uma ameaça à vida e à segurança dos indivíduos, mas também têm um impacto significativo nos custos operacionais e na reputação das empresas de logística. O primeiro passo da análise foi a importação das bibliotecas, dataset específico da ANTT e uma primeira visualização da base carregada:

![base](https://github.com/user-attachments/assets/b45dce1c-1c5f-4a41-b082-6326a2b7231f)

A análise de Pareto é uma ferramenta valiosa para identificar os trechos críticos em acidentes de trânsito, permitindo que os tomadores de decisão concentrem seus esforços nos locais que representam a maioria dos problemas. Ao aplicar essa técnica aos dados da ANTT, podemos priorizar intervenções onde são mais necessárias, maximizando o impacto e otimizando recursos:

![pareto](https://github.com/user-attachments/assets/2e7d1969-ce25-4e39-a024-8c25cfd8065d)

A criação de um mapa de calor é uma abordagem poderosa para entender a distribuição temporal de acidentes ao longo de trechos críticos de estrada, identificados através da análise de Pareto. Este método visual nos permite visualizar de forma intuitiva quando e onde os acidentes ocorrem com mais frequência, fornecendo insights valiosos para a implementação de medidas preventivas e estratégias de segurança. Nesse caso específico, utilizamos o trecho 'BR-324/BA' como prioridade da análise, uma vez que, sozinho, representa mais de 50% da frequência de acidentes no período.

![cdigo_mapa_calor](https://github.com/user-attachments/assets/18687d1f-6082-4410-9608-2198340cfb3b)

![mapa_calor](https://github.com/user-attachments/assets/117bed02-ae3d-4428-b801-a49a8ae8cac3)

