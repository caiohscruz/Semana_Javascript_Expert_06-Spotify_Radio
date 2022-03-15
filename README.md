Separação de camadas
    server
        service = regras de negócio e processamento
        controller =  intermédio entre camadas de apresentação e de negócio
        routes = camada de apresentação
        server = cria o servidor - MAS NÃO O INSTANCIA
        index = instacia o servidor e o expõem para a Web (lado da infraestrutura)
        config = tudo que for estático do projeto

Libs novas
    pino / pino-pretty = para registro de logs
    `npm install pino@7.8.0 pino-pretty@7.5.3`

PAREI EM 58'53"