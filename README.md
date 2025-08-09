# 📊 Análise de Dados: Taxa de Rotatividade de Funcionários 

Este projeto tem como objetivo explorar e visualizar uma base de dados de colaboradores, utilizando o Power BI para gerar indicadores relevantes e apoiar a tomada de decisões estratégicas na área de gestão de pessoas.

Arquivo base: collaborators_base.csv 
Disponível em: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data
Contém informações sobre idade, cargo, departamento, nível educacional, tempo de empresa, salário, entre outros.

# Ferramentas utilizadas

Power BI – criação do dashboard interativo e visualizações

DAX – criação de medidas e colunas calculadas para análise

Google Colab (Python) – análise complementar do dataset: inspeção inicial, verificação de nulos e duplicados, estatísticas descritivas e criação de gráficos simples com Pandas, Matplotlib e Seaborn

# Análises realizadas

# No Google Colab: 

Carregamento do arquivo collaborators_base.csv no Pandas

Visualização inicial (head(), info(), describe())

Verificação de valores nulos e duplicados

Contagem da frequência de Attrition

Criação de gráficos simples (barras e pizza) para visualização básica da distribuição dos dados

# No Power BI:

# Colunas calculadas criadas:

Age Group – Agrupamento por faixa etária

Income Level – Classificação de nível salarial

YearsAtCompany Group – Agrupamento por tempo de empresa

YearsAtCompany Order – Coluna de ordenação para gráficos

# Medidas DAX criadas:

Attrition Rate – Taxa de rotatividade

Average Age – Idade média

Average Monthly Income – Renda mensal média

Gender Distribution – Distribuição por gênero

Attrition Numeric – Conversão de texto para valor numérico

Salary Difference – Diferença salarial entre homens e mulheres

# Visualizações Criadas:

Cartões de Indicadores: Exibem KPIs como Total de colaboradores, Funcionários que saíram e Percentual de rotatividade

Gráfico Donut:
Para visualização de Attrition e Total Employees.

Gráfico de Barras:
Para visualização de Taxa de Rotatividade por Faixa Etária 

Gráfico de Dispersão:
 Correlação entre YearsAtCompany Group e Attrition Rate
 
Matriz de Comparação:
 Comparação entre OverTime, MaritalStatus, EployeeNumber e Attrition.

Segmentações para filtragem por:
Nível Salarial |
Gênero |
Departamento |
Cargo 

# Tarefa Bônus: Automação de Alerta via Power Automate

Foi criado um fluxo no Power Automate que verifica semanalmente, toda segunda-feira, a taxa de rotatividade dos colaboradores. Caso a taxa ultrapasse 15%, um e-mail automático é enviado com a seguinte mensagem:

Olá,
Detectamos que a taxa de rotatividade de colaboradores ultrapassou o limite estabelecido de 15% no último período.
Para mais detalhes, acesse o dashboard atualizado no Power BI clicando no link abaixo:
👉 <a href="https://app.powerbi.com/links/AGOTDx48Hf?ctid=e8cf2639-1f98-4bb4-bd89-abd14928937f&pbi_source=linkShare">Clique aqui para acessar o relatório</a>

Atenciosamente,

Equipe de Dados


# Observações:

Este README tem o objetivo de documentar tecnicamente a estrutura do projeto. As análises interpretativas e insights extraídos a partir dos dados estão disponíveis no painel interativo e na documentação.


