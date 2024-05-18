# AlexaChatGPT4
Para integrar o ChatGPT-4 com a Alexa utilizando uma função AWS Lambda em Python, vamos criar um script um pouco mais avançado que utiliza a API do ChatGPT-4. A seguir, estão os passos detalhados para configurar essa integração.

Pré-requisitos
Conta na AWS.
Conta na OpenAI com acesso à API do ChatGPT-4.
AWS CLI configurado em sua máquina.
Criar a Função Lambda
Aqui está um exemplo de script Python que você pode usar como uma função Lambda. Este script receberá uma entrada da Alexa, enviará essa entrada para a API do ChatGPT-4, e retornará a resposta para a Alexa:
