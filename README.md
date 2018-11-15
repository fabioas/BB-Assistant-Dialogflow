# BB Assistant - Actions on Google - DialogFlow

Repositório para BB Assistant Actions on Google - DialogFlow

## Instruções

### Steps
1. Use o [Actions on Google Console](https://console.actions.google.com) para criar um novo projeto com um nome de sua escolha e clique *Create Project*.
1. Clique *Skip*, no canto superior direito. Não é preciso escolher nenhuma categoria nesta etapa.
1. No menu à esquerda sob o título *BUILD*, clique em *Actions*. Clique em *Add Your First Action* e escolha o idioma.
1. Selecione *Custom intent*, clique *BUILD*. Isso abrirá o console do Dialogflow. Cliquw *CREATE*.
1. Clique no ícone da engrenagem - *project settings*.
1. Selecione *Export and Import*.
1. Selecone *Restore from zip*. Siga as instruções para instalar o arquivo `BBAssistantDFlow.zip`. Isso colocará todas as intenções necessárias pra execução da aplicação.
1. Faça o deploy da aplicação no servidor escolhido, e utilize o código em `index.js`, para escolha do deploy em Firebase ou outro servidor. Ajuste o código se necessário. Adicione ou exclua arquivos ao projeto, de acordo com a necessidade do servidor.
1. Volte ao console do Dialogflow e selecione *Fulfillment* no menu à esquerda. Habilite *Webhook*, e preencha o campo *URL* com o endpoint do webhook adequado, e clique *Save*.
1. Vá ao [Actions on Google Console](https://console.actions.google.com), no menu à esquerda sob o título *Test*, clique em *Simulator*.

Para maiores detalhes sobre deploy do projeto, acesse a [documentação](https://developers.google.com/actions/sdk/deploy-fulfillment).

## Referências
* Actions on Google (documentação): [https://developers.google.com/actions/](https://developers.google.com/actions/)
