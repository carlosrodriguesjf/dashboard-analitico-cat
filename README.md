

# DASHBOARD ANALÍTICO CENTRAL DE ATENDIMENTO

Este é um Dashboard que exibe o resultado baseado nas métricas de uma Central de Atendimento de uma Universidade Pública. O Dashboard foi desenvolvido utilizando PowerBI



## 🎯 Objetivos

A Central de Atendimento de uma universidade enfrentava o desafio de monitorar seu desempenho de forma fragmentada, com dados dispersos em múltiplas planilhas e sistemas. Essa falta de visibilidade em tempo real dificultava a identificação de gargalos e a tomada de decisões baseadas em dados.

No final de cada mês era gerado um relatório em pdf com os reultados, o que era muito trabalhoso por causa dos dados estarem dispersos.

Havia também a necessidade de realocação dos funcionários em determinadas tarefas de acordo com a demanda, o seu desempenho e também a realocação do número de funcionários que executavam algumas tarefas durante os horários de maior movimento no dia.

Para solucionar alguns desses problemas, desenvolvi um Dashboard Analítico em Power BI. O objetivo do projeto foi criar uma solução unificada para coletar, limpar e visualizar dados de atendimentos, permitindo que a gestão:

- Obtenha uma visão clara do volume de atendimentos presenciais e telefônicos.
- Monitore a produtividade e o desempenho individual e da equipe.
- Identifique picos de demanda para otimizar a alocação de recursos.
- Avalie a eficiência do serviço e os pontos de melhoria, garantindo uma experiência superior para as pessoas atendidas pelo setor.



## 🔍 Considerações Iniciais
Os dados verdadeiros foram alterados para preservar informações sensíveis do setor de trabalho, sendo outras informações como nomes de cursos e nomes de serviços são públicas.

Depois de março de 2024, os dados são totalmente gerados por uma ferramenta de inteligêncial artificial para que o dashboard continue atualizado e esse trabalho continue com o foco para estudos pessoais.



## 🚀 Começando

Acesso
O dashboard publicado pode ser acessado no endereço abaixo:
https://app.powerbi.com/view?r=eyJrIjoiOTkzNzFkZTQtYWU4ZS00N2M5LWI3ODUtZGRmY2Q4Yzk1MDcwIiwidCI6ImY2MjFhMmY0LWJhM2QtNGEyMC05MDA3LTZjNTAyNjU1MGFiZiJ9

Os registros foram coletados a partir do dia 06/06/2022.

O Dashboard era atualizado, em geral, no primeiro dia útil do mês.



## 📦 Implantação

O sistema utiliza as seguintes bases de dados para a coleta de informações:

- As informações sobre atendimentos presenciais é coletada de uma relatório emitido pelo sistema de senhas NovoSGA
- Informações sobre Visualizações de páginas visitadas é coletada, uma parte, automaticamente pela conexão ao do Google Analytics. Outra parte sobre relatórios mensais
- Informações sobre atendimento telefônico, são retiradas de uma planilha Google onde essas informações são registradas pelos atendentes através de um formulário Google
- Informações sobre os funcionário são coletadas de uma planilha com o registro dos dados pessoais dos funcionários do setor -> dados_funcionarios.xlsx
- Todas as outras informações são coletadas de planilhas cujo o registro é realizado manualmente. Essas planilhas são:
    - 1 - Protocolo Geral.xlsx
    - 3 - Controle de Arquivamento.xlsx
    - 6 - Postagem Correios - Protocolo.xlsx
    - Distribuição de Demandas - CAT.xlsx
    - Distribuição de Demandas - CAT v2.xlsx
    - outros_dados.xlsx



## 🛠️ Construído com

* Power BI


## 📌 Versão

Foi usado o Git para controle de versão e o github para armazenamento do projeto. Para as versões disponíveis, acesse https://github.com/carlosrodriguesjf/dashboard-analitico-cat e as alterações realizadas no arquivo -> controle-de-versoes.txt



## ✒️ Autor

Carlos Eduardo Rodrigues - Analista de Dados







