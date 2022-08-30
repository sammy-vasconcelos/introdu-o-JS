# introdução-o-JS

## Arrow Function
```javascript
 const arrow = () => 'code here'; // => apenas uma expressão
 const arrow = () => {
   'code here'
   return 'code here'
 } //  => mais de uma expressão
```

## Objeto
```javascript 
const user = {
 name: 'Sammy'
  lastname: 'Vasconcelos'
  }
 Object.assign(user, {fullname: Sammy Vasconcelos}) //=> vai adicionar uma nova propriedade no objeto user
 Object.assign({}, user, {age:56}) //=> retorna um novo objeto mergeando dois ou mais objetos 
 Object.freeze(user) //=> não vai deixar o obj ser alterado de nenhum forma
 Object.seal(user) //=> pode alterar, mas não pode criar nem deletar 
```

## Function
```javascript
function soma(n1,n2){
    somatorio = n1 + n2
     return somatorio
} 
alert(soma(1,2))
//funciona como uma função matemática f(x), os parametros são passados ao chamar a função e ela vai executar os códigos dentro dela 
```

## Data
```javascript
var day = new Date()
alert(day.getMinutes())
```


## While
```javascript
var count = 5
 var contagem = "contagem regressiva... "
 while(count>0){
     alert(contagem + count)
     count--
 }
alert("Kabuuuuuuuuuuuum")
```


## For
```javascript
for(count=1; count<=5; count++){
 alert(count)
 }
```


## Prompt
```javascript
 var idade = prompt("qual sua idade?") => vai aparecer um pop up com espaço para digitar 
var idade = prompt("qual sua idade?")
 if (idade >= 18){
     alert("maior de idade")
} else {
     alert("menor de idade")
}
```

## Array
```
.push é para adicionar elemento em um array
.pop é para retirar
.length quantidade de elementos na lista
.reverse inverter os elementos
.toString transforma o array em uma string
.join(" - ") tbm transforma em string e substitui a virgula por um elemento dentro dos ()
var frutas = [{nome:"maça", cor:"vermelha"}, {nome:"uva", cor:"roxa"}]
alert(frutas[1].nome) result => "uva"
```
```javascript
const users = ['Guilherme', 'Pedro', 'Jennifer'];
const gender = {
  MAN: Symbol('M'),
  WOMAN: Symbol('W')
 }
const people = [
  {
    name: 'Guilherme',
    age: 26,
    gender: gender.MAN 
  },
  {
    name: 'Pedro',
    age: 20,
    gender: gender.MAN
  },
  {
    name: 'Jennifer',
    age: 27,
    gender: gender.WOMAN
  }
];

// iterar os itens do array
people.forEach(person => {
console.log(`nome: ${person.name}`);
})

// filtrar array
const men = people.filter(person => person.gender === gender.MAN);
console.log('\n Nova lista com homens:', men);

// spread ...
var partes = ['ombro', 'joelhos']
var musica = ['cabeça', ...partes, 'e', 'pés'];
```

## Function
```javascript

```

## Function
```javascript

```