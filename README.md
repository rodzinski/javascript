# javascript
Curso de JavaScript do CursoemVideo

> Obs: no fim do curso vou formalizar e estruturar tudo.

<details><summary>Anotações:</summary>

PRECISO AJUSTAR ISSO

// Formatando Strings

`var s = 'JavaScript'`

'Eu estou aprendendo s'     // não faz interpolação

'Eu estou aprendendo' + s   // usa concatenação

`Eu estou aprendendo ${s}`  // usa template string -- com CRASE `

`var s = 'JavaScript'`

s.length          // quantos caracteres a string tem
s.toUpperCase()   // tudo para 'MAIÚSCULAS'
s.toLowerCase()   // tudo para 'minúsculas'

// Formatando números

n1 = 1545.5                                                         // Var para n1
n1.toFixed(2)                                                       // Aumenta a casa decimal EX: 1545.50
n1.toFixed(2).replace('.', ',')                                     // Muda de ponto para virgula EX: 1545,50
n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})    // Muda para o padrão real R$  EX: R$ 1.545,50

### Operadores

aritméticos                                                                   Cuidado!
    +  : 5+2  = 7                                                       EX: 5+3/2 = 6.5
    -  : 5-2  = 3                                                       Lembrar sempre que respeita
    *  : 5x2  = 10  --Multiplicação                                     a mesma regra que a matématica            
    /  : 5/2  = 2.5 --Divisão                                           de prioridade entre x e /;
    %  : 5%2  = 1   --Divisão inteira
    ** : 5**2 = 25  --Potencia Ex: nesse caso 5 ao quadrado 5x5=25
atribuição
relacionais
lógicos
ternário


<details><summary>Identificadores - VAR</summary>

- Podem começar com letra, $ ou _
- Não podem começar com números
- É possível usar letras ou números
- É possível usar acentos e símbolos
- Não pode conter espaços
- Não podem palavras reservadas

<details><summary>Dicas</summary>

- Maiúsculas e minúsculas fazem diferença
- Tente escolher nomes coerentes para variáveis
- Evite se tornar um 'Programador alfabeto' ou um 'Programador contador'

</details>

</details>

<details><summary>Data Types</summary>



**number**
5 18 -12 
0.5 -15.9 3.14 8.0

**number - Infinity**

**number - NaN**

**boolean**
true
false

**string**
"Google"
'JavaScript'
Maria`

**null**

**undefined**

**object**

**object - Array**

**function**

</details>

</details>

</details>