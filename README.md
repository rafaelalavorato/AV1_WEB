# AV1_WEB
AV1 da disciplina Arquitetura de aplicações WEB da faculdade Newton Paiva

# Projeto de API REST em Java com Spring Boot
# 1. Implementar um endpoint "Hello World"
Dependências:
* Spring Web: Esta dependência inclui tudo o que você precisa para desenvolver aplicativos web, incluindo suporte para RESTful APIs, controle de requisições HTTP e configuração automática.

* Spring DevTools: Esta dependência fornece funcionalidades adicionais durante o desenvolvimento, como reinicialização automática da aplicação ao detectar mudanças no código, além de outras melhorias que facilitam o desenvolvimento.

O endpoint deve receber um parâmetro e exibir uma mensagem personalizada na tela do navegador

# 2. Criar uma API REST para consultar a tabela FIPE

Desenvolver uma API REST em Java, utilizando o Spring Framework, para consultar informações sobre marcas, modelos e valores de carros da tabela FIPE.
Utilizar as seguintes APIs para consumir as informações da tabela FIPE:
API FIPE de Deivid FortunaLinks to an external site.
API FIPE ParallelumLinks to an external site.
Estrutura do Projeto
O projeto deve ser organizado da seguinte forma:

Pacote controller: Contém as classes responsáveis por gerenciar as requisições HTTP e as respostas.
Pacote service: Contém as classes que implementam a lógica de negócio e a comunicação com a API da tabela FIPE.
Requisições da API FIPE
As seguintes requisições devem ser implementadas:

Para obter a lista de marcas:

GET https://parallelum.com.br/fipe/api/v1/carros/marcas
Para obter os modelos de uma marca específica (por exemplo, marca com ID 59):

GET https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos
Para consultar os anos de um modelo específico (por exemplo, modelo com ID 5940) de uma marca específica (ID 59) e ano (por exemplo, 2014):

GET https://parallelum.com.br/fipe/api/v1/carros/marcas/59/modelos/5940/anos/2014-3
Chatbot utilizando a API do Gemini
Implementar uma API de Chatbot utilizando o Gemini
Acesse o Google AI StudioLinks to an external site. para gerar uma API e siga o guia de início do API.
