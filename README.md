## EVISUS-hackathon-inovadados-

Esse repositório refere-se ao protótipo da aplicação EviSUS, cuja missão é concatenar e traduzir dados e evidências científicas provenientes de variadas fontes no âmbito do Ministério da Saúde (com ênfase no banco Pesquisa Saúde e nos dados epidemiológicos referentes a produção ambulatorial e hospitalar veiculados no DATASUS).

O propósito da aplicação é que esta constitua aplicativo próprio; todavia, em virtude de sua arquitetura linear e intuitiva, foi possível elaborar seu protótipo no formato de chatbot no aplicativo de mensagens Telegram. 

Seguem as seções e subseções da aplicação, inicializada em um menu principal no qual o usuário deve selecionar seu nível de acesso (gestor, pesquisador ou profissional de sáude)

Canal do gestor
- Boletins epidemiológicos: Regulares, Especiais e COVID-19
- Produção ambulatorial e hospitalar -> estratificadores: geográficos, temporais, modalidade de financiamento e nível de complexidade
- Dados de morbimortalidade hospitalar -> stratificadores: geográficos, temporais, agravo em saúde
- Recomendações - Pesquisa Saúde: Por categoria, Por palavra-chave

Canal do pesquisador
- Orientações gerais
- Recursos disponíveis: Materiais de apoio, Editais disponíveis
- Lacunas de conhecimento: Mapeamento do conhecimento, Demandas prioritárias

Canal do profissional de saúde
- Protocolos e diretrizes: Protocolos clínicos e diretrizes terapêuticas, Diretrizes para diagnóstico e tratamento, Diretrizes nacionais, Linhas de cuidado
- Mapeamento clínico-epidemiológico -> estratificadores: sistema (SIM, SINAN, SIH), geográficos, temporais, agravos
- Atualização técnico-científica: estratificadores: fonte (evidências Pesquisa Saúde, iniciativas específicas...), categoria, palavras-chave
 
O fluxo da aplicação já foi estabelecido de ponta-a-ponta, e algumas das funcionalidades propostas desenvolvidas (no protótipo) e testadas.
  
Foi criado um dataset exemplificativo (incompleto e não necessariamente fidedigno à estrutura pretendida) para fins de prototipação, contando com dados provenientes dos 3 eixos de alimentação da aplicação (Pesquisa Saúde, documentos MS e DATASUS).
  
Todas as etapas de desenvolvimento até então foram implementadas em Python.

Link para o protótipo (no momento, fora do ar): https://t.me/prototipoEVISUSbot
