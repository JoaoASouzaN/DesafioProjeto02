# DesafioProjeto02
 Desafio de Projeto Trabalhando com Machine Learning na Prática no Azure ML 


Criação de um Espaço de Trabalho no Azure Machine Learning

Acesse o portal Azure em https://portal.azure.com usando suas credenciais da Microsoft.
Selecione + Criar um recurso, pesquise por Machine Learning e crie um novo recurso Azure Machine Learning com as configurações necessárias (Assinatura, Grupo de Recursos, Nome, Região, Conta de Armazenamento, Key Vault, Application Insights, Container Registry).
Clique em Revisar + criar e, em seguida, em Criar. Aguarde a criação do espaço de trabalho.
Acesso ao Azure Machine Learning Studio

Selecione Iniciar estúdio (ou abra uma nova guia do navegador em https://ml.azure.com e faça login no Azure Machine Learning Studio com sua conta Microsoft).
Utilizando Aprendizado de Máquina Automatizado para Treinar um Modelo

No Azure Machine Learning Studio, acesse a página Automated ML (em Authoring).
Crie um novo trabalho Automated ML com as configurações especificadas:
Configurações básicas: Nome do trabalho, Nome do experimento, Descrição.
Tipo de tarefa e dados: Tipo de tarefa (Regressão), Conjunto de dados (Criar novo conjunto de dados com configurações específicas).
Configurações da Tarefa: Tipo de Tarefa, Conjunto de Dados, Coluna-Alvo, Configurações Adicionais.
Validação e teste: Tipo de Validação, Percentual de Dados de Validação.
Computação: Tipo de Computação, Tipo de Máquina Virtual, Número de Instâncias, etc.
Envie o trabalho de treinamento e aguarde a conclusão.
Revisão do Melhor Modelo

Na guia Visão Geral do trabalho Automated ML, observe o resumo do melhor modelo.
Selecione o nome do algoritmo para visualizar os detalhes.
Na guia Métricas, revise os gráficos de desempenho do modelo, incluindo os gráficos de resíduos e verdadeiros previstos.
Implantação e Teste do Modelo

Na guia Model do melhor modelo treinado, selecione Implantar e use a opção de Serviço Web.
Configure os detalhes da implantação (Nome, Descrição, Tipo de Computação, Autenticação) e inicie a implantação.
Aguarde até que o status da implantação mude para Bem-Sucedido (pode levar de 5 a 10 minutos).
Teste do Serviço Implante

No Azure Machine Learning Studio, na guia Endpoints, abra o endpoint de tempo real do serviço implantado.
Na página de teste, substitua o JSON de exemplo pelos dados de entrada fornecidos.
Clique em Testar e revise os resultados do teste, incluindo o número previsto de aluguéis com base nas características fornecidas.
Ao seguir esses passos, você utilizou o aprendizado de máquina automatizado no Azure Machine Learning para treinar, implantar e testar um modelo preditivo de aluguel de bicicletas com base em dados históricos.



User
ok, agora eu quero que voce faça uma verificação minuciosa e procure por erros, caso ache algum resolva. me informe caso encontre algum erro e transcreva fazendo as correçoes necessarias

ChatGPT
Explorando o Aprendizado de Máquina Automatizado no Azure Machine Learning

Criação de um Espaço de Trabalho no Azure Machine Learning

Acesse o portal Azure em https://portal.azure.com usando suas credenciais da Microsoft.
Selecione + Criar um recurso, pesquise por Machine Learning e crie um novo recurso Azure Machine Learning com as configurações necessárias (Assinatura, Grupo de Recursos, Nome, Região, Conta de Armazenamento, Key Vault, Application Insights, Container Registry).
Clique em Revisar + criar e, em seguida, em Criar. Aguarde a criação do espaço de trabalho.
Acesso ao Azure Machine Learning Studio

Selecione Iniciar estúdio (ou abra uma nova guia do navegador em https://ml.azure.com e faça login no Azure Machine Learning Studio com sua conta Microsoft).
Utilizando Aprendizado de Máquina Automatizado para Treinar um Modelo

No Azure Machine Learning Studio, acesse a página Automated ML (em Authoring).
Crie um novo trabalho Automated ML com as configurações especificadas:
Configurações básicas: Nome do trabalho, Nome do experimento, Descrição.
Tipo de tarefa e dados: Tipo de tarefa (Regressão), Conjunto de dados (Criar novo conjunto de dados com configurações específicas).
Configurações da Tarefa: Tipo de Tarefa, Conjunto de Dados, Coluna-Alvo, Configurações Adicionais.
Validação e teste: Tipo de Validação, Percentual de Dados de Validação.
Computação: Tipo de Computação, Tipo de Máquina Virtual, Número de Instâncias, etc.
Envie o trabalho de treinamento e aguarde a conclusão.
Revisão do Melhor Modelo

Na guia Visão Geral do trabalho Automated ML, observe o resumo do melhor modelo.
Selecione o nome do algoritmo para visualizar os detalhes.
Na guia Métricas, revise os gráficos de desempenho do modelo, incluindo os gráficos de resíduos e verdadeiros previstos.
Implantação e Teste do Modelo

Na guia Model do melhor modelo treinado, selecione Implantar e use a opção de Serviço Web.
Configure os detalhes da implantação (Nome, Descrição, Tipo de Computação, Autenticação) e inicie a implantação.
Aguarde até que o status da implantação mude para Bem-Sucedido (pode levar de 5 a 10 minutos).
Teste do Serviço Implante

No Azure Machine Learning Studio, na guia Endpoints, abra o endpoint de tempo real do serviço implantado.
Na página de teste, substitua o JSON de exemplo pelos dados de entrada fornecidos.
Clique em Testar e revise os resultados do teste, incluindo o número previsto de aluguéis com base nas características fornecidas.
Ao seguir esses passos, você utilizou o aprendizado de máquina automatizado no Azure Machine Learning para treinar, implantar e testar um modelo preditivo de aluguel de bicicletas com base em dados históricos.



