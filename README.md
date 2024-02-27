# dio-lab-machine-learning-azure
Lab de Machine Learning do curso de IA

### Descrição

Primeiro Laboratório Trabalhando com Machine Learning na Prática no Azure ML.

## Passo-a-passo

1. Acesse o Portal do Azure: Faça login na sua conta do Azure em https://portal.azure.com.

2. Navegue para o Azure Machine Learning: No painel de navegação à esquerda, procure por "Machine Learning" ou "Serviços de Machine Learning". Clique para acessar o serviço de Estúdio do Azure Machine Learning.

3. Crie um Modelo: Se você já tem um modelo treinado, pode importá-lo para o Azure Machine Learning. Caso contrário, você pode treinar um modelo diretamente no Azure ou importar um modelo treinado anteriormente de outras fontes, como o Azure ML Studio ou ferramentas de desenvolvimento local.

4. Prepare o Modelo para Implantação: Se necessário, prepare seu modelo para implantação. Isso pode envolver a criação de um script de inferência (por exemplo, um arquivo Python) que carrega o modelo treinado e define como os dados de entrada serão processados.

5. Crie um Serviço de Implantação: No Azure Machine Learning, navegue até a seção de "Implantações" ou "Serviços" e clique em "Novo Serviço de Implantação" ou similar.

6. Configure o Serviço de Implantação: Preencha os detalhes necessários, como nome, região, tipo de computação, número de instâncias, etc. Selecione o tipo de serviço apropriado para o seu caso, como "Serviço de Contêiner" se estiver usando Docker.

7. Implante o Modelo: Selecione o modelo que você preparou na etapa 3 para implantação. Especifique o script de entrada (por exemplo, um script Python que aceita solicitações HTTP e chama o modelo) e quaisquer outras configurações relevantes.

8. Configure o Ponto de Extremidade: Durante o processo de implantação, você definirá um ponto de extremidade para o serviço. Aqui, você pode configurar detalhes como autenticação, escalabilidade, limites de taxa, etc.

9. Implantação e Teste: Após configurar o ponto de extremidade, implante o serviço. Uma vez implantado, você pode testar o ponto de extremidade para garantir que esteja respondendo corretamente às solicitações, fornecendo previsões de aluguel de bicicletas com base nos dados de entrada.

Lembre-se de que esses passos são gerais e podem variar dependendo de fatores como o tipo específico de modelo de machine learning que você está usando, suas preferências de configuração, a estrutura de dados de entrada/saída, entre outros. Certifique-se de consultar a documentação oficial do Azure Machine Learning e seguir as melhores práticas recomendadas.