#**Project Model Canvas – Kaggler Chatbot MVP (Exploração de dados meteorológicos globais)**

##Contexto
###O clima exerce influência direta em praticamente todos os setores da sociedade. Empresas e governos dependem de informações ###meteorológicas confiáveis para planejamento estratégico, redução de riscos e tomada de decisão rápida. 
###Esse dataset contém informações climáticas (precipitação, velocidade dos ventos, temperatura) de mundo inteiro dos anos de 1942 ###a 1945.
###O objetivo é usar esse conjunto de informações como base para construir um chatbot simples.

##Problema a ser respondido
###Existem padrões consistentes em regiões diferentes?

##Pergunta norteadora
###•	Qual é a temperatura média de cada ano de 1942 a 1945?

##Solução Proposta
###Desenvolver um chatbot educacional em Streamlit que:
###•	Permita upload do arquivo train.csv do Titanic.
###•	Treine modelos de:
      ###1.	Regressão linear (predição de Temperatura Média).
###•	Mostre métricas de avaliação (R2, MAE, RMSE).
###•	Explique a importância das variáveis por meio de coeficientes e odds ratios.
###•	Responda perguntas do usuário via chatbot regrado.

##Desenho da arquitetura
###O sistema será estruturado em camadas:
  ###•	Interface (app/): Streamlit como front-end para upload, treino e perguntas.
  ###•	Core (core/): módulos para dados, features, modelos, explicabilidade e chatbot.
  ###•	Dados (data/): pastas para armazenar arquivos brutos, tratados e modelos treinados.
  ###•	Documentação (docs/): PMC, arquitetura, governança e testes.

##Resultados Esperados
###•	Modelo de classificação com acurácia próxima de 75–80%.
###•	Relatório de métricas e importâncias de variáveis.
###•	Deploy em Streamlit Cloud com documentação completa no GitHub.


