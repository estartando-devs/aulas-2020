# Estartando Devs:green_heart:

# Javascipt

## O basico...

`console.log("Hello World!")`
O comando console.log() é usado para monstrar um valor durante a interpretação

---

## Declaração de Variveis

#### Existem _3_ tipos de declarar uma viariavel

`var varivel1 = "eu sou uma var"`

`let varivel2 = "eu sou um let"`

`const varivel3 = "eu sou uma const"`

#### Quais as diferenças das declarações?

`const` é uma constante, ela não pode ser alterada.

`let` é uma variavel que pode ser acessada apenas no escopo em que ela é declarada.

`var` é uma variavel que pode ser acessada em qualquer lugar do projeto. É aconselhado que você só use ela caso necessario.

---

## Tipos

### Esses são os tipos que temos no JavaScript

- string
- number
- object
- undefined
- boolean
- function

##### String

String é um tipo que armazena textos. Para entendermos vamos criar uma varivel que o valor é do tipo string

`const souUmaString = "Eu sou uma variavel do tipo string!"`

##### Number

Number é um tipo que armazena numeros (Damm).

`const souUmNumber = 10`

##### Object

Esse é um pouco mais complexo, mas eu gosto muito :stuck_out_tongue_winking_eye:
O objeto é identificado por `{}`. Ele tem o que podemos chamar de "keys" (chaves). No exemplo abaixo vou mostrar um objeto que é referente á pessoa e vou dar á ele as keys nome e idade.

`const pessoa = { nome: "Breno Nunes", idade: 18}`

Como vocês podem ver as keys do objeto tem valores, e esses valores podem ter tipos diferentes. No caso `nome` é do tipo string e `idade` do tipo number

#### Undefined

Undefined é um tipo indefinido. Nada mais nada menos que um variavel que ainda não tem seu valor definido/setado

`const indefinido;`

##### Boolean

Boolean é um tipo booleano :thinking:. Ela tem 2 opções, `true` ou `false`... Acho que já entenderam.

```
const verdadeiro = true;
const falso = false;
```
