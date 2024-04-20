# Criando um Modelo de Previsão no Azure ML
 vamos criar um modelo de previsão utilizando o Azure Machine Learning e configurar seus pontos de extremidade para que possa ser facilmente acessado e utilizado.

Passo 1: Configuração do Ambiente
Antes de começarmos, é necessário ter uma conta no Azure e acessar o Azure Machine Learning Studio. Se você ainda não tem uma conta, pode se inscrever gratuitamente em azure.microsoft.com.

Passo 2: Preparação dos Dados
Para este exemplo, vamos utilizar um conjunto de dados de exemplo disponível no Azure ML Studio. Você pode escolher um conjunto de dados adequado para o seu problema de previsão.

Passo 3: Criação do Experimento
No Azure ML Studio, clique em "Experiments" e em seguida em "New Experiment".
Arraste e solte um módulo de pré-processamento de dados, como "Clean Missing Data", e conecte-o ao conjunto de dados.
Adicione os módulos de treinamento do modelo, como "Train Model", e configure-os conforme necessário.
Execute o experimento e verifique se o modelo foi treinado com sucesso.
Passo 4: Implantação do Modelo
Após treinar o modelo com sucesso, clique em "Deploy Web Service".
Siga as instruções para configurar o serviço web e implante o modelo.
Anote o ponto de extremidade (endpoint) gerado para acessar o modelo.
Passo 5: Testando o Modelo
Utilize ferramentas como o Postman ou escreva um script em Python para enviar requisições para o ponto de extremidade do modelo.
Envie os dados de teste para o ponto de extremidade e verifique se as previsões estão sendo feitas corretamente.
