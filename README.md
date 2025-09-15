# API Galera do Vôlei

## Requerimentos

- O sistema deve permitir o cadastro e consulta de jogadores
- O sistema deve permitir o cadastro e consulta de partidas
- O sistema deve permitir a alterações em partidas
- O sistema deve permitir a avaliação de partidas
- O sistema deve permitir a avaliação de jogadores

## API

A API foi construída com uma abordagem *design-first*.
A partir da [OpenAPI Specification](https://spec.openapis.org/oas/v3.0.4.html)
é possível descrever a API com um arquivo [YAML](https://yaml.org/).
Tal arquivo é utilizado para gerar a documentação da API.
Além disso, por causa da especificação é possível gerar códigos em
diversas linguagens tanto para o servidor quanto para o cliente.
Assim, o código *boilerplate* para a API acompanha a documentação
e será possível focar na lógica de negócio.
