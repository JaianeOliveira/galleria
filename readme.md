# SASS 

Temos duas sintaxes disponíveis

- .scss 
- .sass

a diferença é que o *.scss* é mais próximo do css e a gente não precisa digitar certas coisas

## Como usar 

    <link rel="stylesheet" href="css/styles.css" />

cria um link pro arquivo css que o sass vai gerar, cria uma pasta *sass* e dentro dela um arquivo *styles.sass*

## A sintaxe

- Se orienta por tabs e não por chaves
- Não coloca ";"

        div
            background: red

- digita o comando para gerar o css
`
    
        sass --watch sass/styles.sass:css/styles.css

