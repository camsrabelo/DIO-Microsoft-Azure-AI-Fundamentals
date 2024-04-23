# Criando e testando Machine Learning com o Azure Machine Learning 

- [Pré-requisitos](README.md/#pré-requisitos)
- [Criando um espaço de trabalho](README.md/#criando-um-espaço-de-trabalho)
- [Criando um ML automatizado](README.md/#criando-um-ml-automatizado)


> Obs.: Todos as etapas foram seguidas de acordo com a vídeo-aula disponível no curso e também na [documentação da Microsoft](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#deploy-and-test-the-model)

## Pré-requisitos:
- Conta na Azure (utilizando uma nova ou em caso de uma já existente, que tenha uma assinatura disponível - se passados os 30 dias gratuitos dos serviços necessários. Mais detalhes no vídeo [deste link](https://www.youtube.com/watch?v=8aDA8dPY_rs&ab_channel=CanaldaCloud));

## Criando um espaço de trabalho

Há duas formas de criar um workspace no Azure, pelo [portal geral](https://portal.azure.com/) e pelo [portal de machine learning](https://ml.azure.com/). 
<br>
No portal geral, basta clicar em Create a resource, pesquisar por machine learning e clicar no Azure Machine Learning e em Create

![pesquisa machine learning](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image.png)

![detalhes do servico de machine learning](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-1.png)

Na página de criação, a dica é ficar atento a região que vai escolher o recurso e o padrão de nome utilizado, os outros itens pode deixar como padrão 

![formulario de criacao de workspace](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-2.png)

![aba networking  do formuário workspace](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-3.png)

![aba encryption do formuário workspace](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-4.png)

![aba identity do formuário workspace](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-5.png)

Depois de provisionado, clicar em __ ou simplesmente acessar o [link do ML](https://ml.azure.com/)

![acessar ML Studio](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-6.png)


## Criando um ML automatizado

![Menu ML automatizado](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-7.png)

**__ATENÇÃO!!!__**

Escolher a melhor execução do job para criar modelo e endpoint, senão o modo de preenchimento não segue igual da documentação!!!

![best execution of job](https://raw.githubusercontent.com/camsrabelo/DIO-Microsoft-Azure-AI-Fundamentals/main/1%20-%20Trabalhando%20com%20Machine%20Learning%20na%20Pr%C3%A1tica%20no%20Azure%20ML/Images/image-8.png)
