# Customer Churn - Modelo de Previsão de Perda de Clientes

![Churn](/churn.jpg)

O índice 'churn', é o índice que mede a saída de clientes ou materiais mediante à um período. O churn, conhecido também como 'índice de atrito', diz respeito à saída de clientes de uma empresa, e como consequência, perda de receita.

Normalmente, o churn é registrado em uma base de dados de cadastro de clientes, relacionando o tempo de permanência de um determinado cliente com outros fatores que podem - ou não - acarretar sua saída ou abandono de serviço.

Este ítem é muito importante de ser medido e controlado, pois é um importante fator que mede a qualidade do serviço oferecido e um importante preditor de receita ao longo do tempo, uma vez que o churn pode significar queda nas receitas.

Este projeto utlizando Machine Learning, foi desenvolvido para prever o comportamento e os fatores que levam a perda de clientes.

Foram escolhidas, dentre tantos outros, 3 classificadores para criação do modelo:

- Regressão Logística
- Boosting Gradient (XGBoost)
- Random Forest 


Todos os modelos vem da biblioteca Scikit-Learn (https://scikit-learn.org/stable/), juntamente com as funções de medidas de desempenho do modelo (metrics).

Trata-se de uma empresa bancária e o objetivo é prever a taxa de churn ao longo do tempo.

Como documentação desse dataset, podemos descrever as seguintes features:

RowNumber: Corresponde ao sumário do dataset.
CustomerId: Chave única de cada cliente.
Surname: O sobrenome do cliente.
CreditScore: pode ter efeito no customer churn, pois um cliente com um alto score bancário é menos provável de deixar a empresa.
Geography: A localização de um cliente pode afetar a decisão de deixar a empresa.
Gender: Gênero. É interessante explorar se o gênero tem alguma influência nas decisões de deixar a empresa.
Age: Idade. É certamente relevante, pois quanto mais velho for, mais propensos estão em deixar a empresa.
Tenure: Se refere ao tempo em anos que um cliente permanece na empresa. Normalmente, clientes mais velho são mais leais e menos propensos em deixar a empresa.
Balance: Balanço. Também um bom indicador de churn, clientes com maior balanço em suas contas são menos propensos em deixar a empresa em relação àqueles com menor balanço.
NumOfProducts: Quantidade de produtos aderidos por um cliente na empresa.
HasCrCard: Descreve se um cliente tem ou não cartão de crédito. Esta feature é interessante, pois clientes que possuem cartão são menos propensas em deixar o banco.
IsActiveMember: Clientes ativos são menos propensos em deixar a empresa.
EstimatedSalary: Como no balanço, clientes com menores salários são mais propensas em deixar a empresa comparada com aqueles de maior salário.
Exited: Churn. Se o cliente deixou ou não a empresa.
