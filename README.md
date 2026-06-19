# JavaScript

Curso de **JavaScript** — Curso em Vídeo  

> **Observação:** Ao final do curso, este material será revisado, formalizado e estruturado.

---

## 📌 Anotações

### 🔤 Formatação de Strings

```js
var s = 'JavaScript'
```

```js
'Eu estou aprendendo s'      // Não faz interpolação
'Eu estou aprendendo ' + s  // Concatenação
`Eu estou aprendendo ${s}`  // Template string (crase)
```

#### Propriedades e métodos de string

```js
s.length        // Quantidade de caracteres
s.toUpperCase() // Converte para MAIÚSCULAS
s.toLowerCase() // Converte para minúsculas
```

---

### 🔢 Formatação de Números

```js
let n1 = 1545.5
```

```js
n1.toFixed(2)                         // 1545.50
n1.toFixed(2).replace('.', ',')       // 1545,50
n1.toLocaleString('pt-BR', {
  style: 'currency',
  currency: 'BRL'
})                                   // R$ 1.545,50
```

---

## ➕ Operadores

### Aritméticos

| Operador | Exemplo | Resultado |
|--------|--------|-----------|
| `+` | `5 + 2` | `7` |
| `-` | `5 - 2` | `3` |
| `*` | `5 * 2` | `10` |
| `/` | `5 / 2` | `2.5` |
| `%` | `5 % 2` | `1` |
| `**` | `5 ** 2` | `25` |

> ⚠️ **Atenção:** A precedência segue as regras matemáticas.  
> Exemplo: `5 + 3 / 2 = 6.5`

---

### Relacionais

> O resultado **sempre será booleano** (`true` ou `false`).

```js
5 > 2    // true
7 < 4    // false
8 >= 8  // true
9 <= 7  // false
5 == 5  // true
4 != 4  // false
```

```js
5 === '5' // false (tipo diferente)
5 === 5   // true
```

#### Exemplos práticos

```js
preco >= 200.50
idade < 18
curso == 'JavaScript'
n1 != n2
```

---

### Lógicos

| Operador | Descrição |
|--------|----------|
| `!` | Negação |
| `&&` | Conjunção (E) |
| `||` | Disjunção (OU) |

```js
true && true   // true
true && false  // false
false || true  // true
```

#### Exemplos

```js
idade >= 15 && idade <= 17
estado == 'RJ' || estado == 'SP'
salario > 1500 && sexo != 'M'
```

---

## 🔀 Precedência de Operadores

Ordem (do maior para o menor):

1. `()`  
2. `**`, `*`, `/`, `%`  
3. `>`, `<`, `>=`, `<=`  
4. `!`  
5. `&&`  
6. `||`

---

## ❓ Operador Ternário

```js
teste ? true : false
```

```js
media >= 7 ? "Aprovado" : "Reprovado"
```

---

## 🏷️ Identificadores (VAR)

- Podem começar com **letra**, `$` ou `_`
- Não podem começar com números
- Podem conter letras e números
- Podem usar acentos e símbolos
- Não podem conter espaços
- Não podem ser palavras reservadas

### 💡 Dicas
- JavaScript diferencia **maiúsculas e minúsculas**
- Use nomes coerentes para variáveis
- Evite ser um *“programador alfabeto”* ou *“programador contador”*

---

## 📦 Data Types

### `number`
```js
5, 18, -12, 0.5, 3.14
```

- `Infinity`
- `NaN`

### `boolean`
```js
true
false
```

### `string`
```js
"Google"
'JavaScript'
`Maria`
```

### Outros tipos
- `null`
- `undefined`
- `object`
- `Array`
- `function`

---

## DOM

DOM = Document Object Model

### Árvore DOM

*Exemplo aula06/ex005.html*
windows
  location
  document
    html
      head
        meta
        title
      body
        h1
        p
        p
          strong
        div
  history

### Selecionando

por Marca
  getElementsByTagName()
por ID 
  getElementById()
por Nome
  getElementsByName()
por Classe
  getElementsByClassName()
por Seletor
  querySelector()
  querySelectorAll()

### Eventos DOM

#### Eventos Mouse

mouseenter
mousemove
mousedown
mouseup
click
mouseout

#### Funções
São executados após os eventos

function ação(param){
  
}

