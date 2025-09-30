1. O que é uma API (Interface de Programação de Aplicações)?

Resposta:
Uma API é um conjunto de regras e definições que permite que diferentes softwares se comuniquem entre si.

2. Qual método HTTP é usado para solicitar dados de um recurso específico?

Resposta:
GET

3. Qual é a principal diferença entre os métodos HTTP PUT e PATCH?

Resposta:

PUT: Atualiza todo o recurso.

PATCH: Atualiza parcialmente o recurso.

4. Em uma requisição HTTP, qual código de status indica que a requisição foi bem-sucedida?

Resposta:
200 OK

5. Como você faria uma requisição GET para uma API usando o cURL no terminal?

Resposta:curl https://api.exemplo.com/recurso

6. Qual a principal desvantagem do XML em comparação com o JSON para APIs web modernas?

Resposta:
XML é mais verboso, menos legível e mais pesado em comparação ao JSON.

7. Qual é o objetivo de um cabeçalho HTTP (HTTP Header)?

Resposta:
Transmitir metadados sobre a requisição ou resposta (como tipo de conteúdo, autenticação, etc).

8. Qual é a função de uma 'API Key' (Chave de API) na autenticação de uma requisição?

Resposta:
Identificar e autenticar o cliente que está fazendo a requisição à API.

9. Qual comando cURL é usado para fazer uma requisição POST com um corpo de requisição em formato JSON?

Resposta:curl -X POST https://api.exemplo.com/recurso \
     -H "Content-Type: application/json" \
     -d '{"nome": "valor"}'

10. Para que serve o método HTTP DELETE?

Resposta:
Para excluir um recurso específico do servidor.

11. Qual é a diferença entre um código de status HTTP 401 Unauthorized e 403 Forbidden?

Resposta:

401 Unauthorized: Falta autenticação válida.

403 Forbidden: Autenticação fornecida, mas sem permissão de acesso.

12. Qual das seguintes tecnologias de autenticação é um padrão de autorização open-source para acesso a recursos protegidos?

Resposta:
OAuth 2.0

13. Qual dos seguintes comandos cURL é usado para enviar um cabeçalho HTTP personalizado chamado Authorization?

Resposta:curl -H "Authorization: Bearer SEU_TOKEN" https://api.exemplo.com/recurso

14. O que é o 'body' (corpo) de uma requisição HTTP POST?

Resposta:
É a parte da requisição que contém os dados a serem enviados ao servidor (ex: JSON, formulário, etc).

15. O que um desenvolvedor deve fazer ao integrar uma API e receber um código de status HTTP na série 4xx?

Resposta:

Verificar se a requisição está correta (sintaxe, autenticação, permissões).

Corrigir os erros conforme necessário.

Consultar a documentação da API.
