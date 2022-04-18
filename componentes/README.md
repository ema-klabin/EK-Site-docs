# Componentes

> Metadados reutilizáveis 

***
### `(denominacao)`

#### descrição

> Componente utilizado para nomear agentes.

| label | type | public | mapeamento::wp
|----|----|----|----|
| Denominação | `object` | `true` | post_title (SOBRENOME, Nome) |

#### propriedades

| name | label | type | rich |
|----|----|----|----|
| nome | Nome | `string` | `false` |
| sobrenome | Sobrenome | `string` | `false` |

***
### `(emails)`

#### descrição

> Lista de e-mails.

| label | type | public |
|----|----|----|
| E-mails | `array<string>` | `false` |

#### propriedades

| name | label | type | format |
|----|----|----|----|
| endereco | Endereço | `string` | `email` |

***
### `(telefones)`

#### descrição

> Lista de telefones.

| label | type | public |
|----|----|----|
| Telefones | `array<object>` | `false` |

#### propriedades

| name | label | type | default |
|----|----|----|----|
| pais | Código de país | `integer` | 55 | 
| regiao | Código de região | `integer` | -- | 
| numero | Número de telefone | `integer` | -- |  

***
### `(redes_sociais)`

#### descrição

> Lista de redes-sociais.

| label | type | public |
|----|----|----|
| Redes-sociais | `array<object>` | `true`

#### propriedades

| name | label | type | enum |
|----|----|----|----|
| rede | Rede-social | `string` | [rede](http://localhost:3000/#/enum/README?id=redes) | 
| usuario | Nome de usuário | `string` | | 

***
### `(explore)`

#### descrição

> Lista de links do explore.

| label | type | public |
|----|----|----|
| Links explore | `array<object>` | `true`

#### propriedades

| name | label | type | format | rich |
|----|----|----|----|----|
| tombo | Número de tombo | `string` | -- | `false`
| url | URL | `string` | `uri` | `false`

***
### `(sites)`

#### descrição

> Lista de links.

| label | type | public |
|----|----|----|
| Sites | `array<object>` | `true`

#### propriedades

| name | label | type | format | rich |
|----|----|----|----|----|
| titulo | Título do site | `string` | -- | `false`
| url | URL | `string` | `uri` | `false`


