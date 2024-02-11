# DeepLearningAzureAI

# MS-learn Fundamentals

Projeto básico para entender o funcionamento do ML automatizado do Azure IA da microsoft desenvolvido, seguindo o passo a passo das aulas.

## Criando uma conta no Microsoft Azure
Primeiro passo para se trabalhar no ambiente virtual, foi a criação da conta em [Azure](https://azure.microsoft.com/pt-br/).

## Acessando o Machine Learning do Azure
Após a criação da conta foi necessário configurar os primeiros passos para utilizar o ambiente de Machine Learning

## Importando os dados
Após a configuração inicial do ambiente, criamos um job importando nele os dados sobre aluguel de bicicleta disponíveis no [link](aka.ms/bike-rentals). E escolhemos o modelo de ML como regressão, que retorna um valor numérico.

## Rodando o modelo e vendo os resultados
Após selecionar os dados, e rodar o modelo. Após o modelo terminar de executar, conseguimos encontrar a melhor versão com os parâmetros que passamos. Conseguimos, també, encontrar os gráficos de valores preditos e o histograma de resíduos. Com a média dos valores preditos foi um pouco abaixo do valor real, quando se aumentaram os valores reais.

Foi realizado o teste da documentação nos resultado e o valor encontrado foi armazenado no arquivo json.

Parâmetros:
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }

