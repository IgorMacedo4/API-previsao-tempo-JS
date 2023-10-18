# API-previsao-tempo-JS
Este script Node.js é construído para interagir com uma API de clima. Ele começa importando as bibliotecas dotenv e axios, que são usadas para carregar variáveis de ambiente e fazer requisições HTTP, respectivamente. As variáveis de ambiente são carregadas de um arquivo .env e são utilizadas para construir a URL da API que será consultada.

Na primeira parte do script, uma requisição GET é feita para uma API para obter as coordenadas de latitude e longitude de um local especificado. As coordenadas são então exibidas no console.

Na segunda parte do script, as coordenadas obtidas são usadas para construir uma nova URL da API, que é usada para fazer outra requisição GET para obter informações de clima atuais do local. As informações recuperadas incluem a sensação térmica e a descrição do clima, que são então convertidas para Celsius (no caso da sensação térmica) e exibidas no console.

O script também inclui tratamento básico de erros que exibirá uma mensagem de erro no console se alguma das requisições GET falhar.




