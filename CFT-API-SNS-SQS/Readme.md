# CFT-API-SNS-SQS

Cloud formation que utilizaremos para generar una estructura de AWS compuesta por una API Gateway, un SNS topic y una SQS suscrita al SNS Topic generado anteriormente.

Para relacionar los diferentes componentes utilizaremos CFT diferentes y los iremos incorporando en un CFT padre mediante NESTED Stack de AWS.

