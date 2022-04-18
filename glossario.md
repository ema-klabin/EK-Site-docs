# Glossário

## Tipos de dados

- `boolean` - Boleano (`true`/`false`)
- `number` - Qualquer tipo de número 
  - `integer` - Número inteiro
- `string` - Fragmento de texto
- `object` - Pares de chaves e valores
- `array` - Lista de valores
- `null` - Nulo

## Propriedades

> [Rest API Schema](https://developer.wordpress.org/rest-api/extending-the-rest-api/schema/)

- `name` - Nome do metadado, utilizado internamente 
- `label` - Etiqueta visível do metadado
- `type` - Tipo de dado
- `format` - Formato da `string` para o metadado. [Expressão regular](https://en.wikipedia.org/wiki/Regular_expression), `date-time`, `email` ou `uri`.
- `min` - Para string `minLength`, para integer `minimum`, para array `minItems`   
- `max` - Para string `maxLength`, para integer `maximum`, para array `maxItems`
- `oneOf` / `anyOf` - Permite escolher entre [outros](https://developer.wordpress.org/rest-api/extending-the-rest-api/schema/#oneof-and-anyof) esquemas
- `public` - Se o metadado é público ou não (`boolean`)
- `rich` - Se o metadado utiliza o editor rico ou não (`boolean`)
- `default` - Valor padrão do metadado

## Mapeamento

> Relações com esquemas de metadados externos.

- [`schema.org`](https://schema.org/) - Esquema de metadados estruturados fundados por uma parceria entre Google, Microsoft, Yahoo e Yandex.
- [`FOAF - Friend of a Friend`](http://xmlns.com/foaf/spec/) - Ontologia para descrever e estabelecer links entre pessoas e informações.
- [`dc - Dublin Core`](https://www.dublincore.org/) - Esquema de metadados estruturados para descrever objetos digitais, como vídeos, sons, imagens, textos e sites na web.
- `wp - WordPess` - Relação com os metadados já estabelecidos no Core do WordPress.