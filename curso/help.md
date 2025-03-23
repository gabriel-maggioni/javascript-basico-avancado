# CONCEITOS BÁSICOS 1

|1| [ESTRUTURAS CONDICIONAIS](#estruturas-condicionais)

|2| [ESTRUTURAS DE REPETIÇÃO - LOOPS](#estruturas-de-repetição)

|3| [OPERADORES LÓGICOS](#operadores-lógicos)



## estruturas condicionais

```javascript
if ...
else ...
```

## estruturas de repetição

for...
```javascript
for (let i = 0; i < 10; i++){
    console.log(i)
}
```

for ... in
```javascript
let array = ["a","b","c","d"];

for (let letra in array){
    console.log(array[letra])
}
```

while...
```javascript
let array = ["a","b","c","d"];
let count = 0;

while(count <= array.length - 1){
console.log(array[count]);
count++;
}
```

do while...
```javascript
let count = 5;

do {
console.log("valor de count:" + count);
count++;
} while (count <= 5);
```

## operadores lógicos
`&&`, `||`

## operadores relacionais
`>`, `<`, `<=`, ``>=`, `==`, `===`, `!=`, `!==`

## operadores aritméticos
`+`, `-`, `/`, `%`, `*`
`Math.PI`;
`num.toString()`
`num.toFixed(2)`
`Math.pow(3,2)` <= potencia
`Math.sqrt(2)` <= raiz quadrada

## operadores unário e ternário
unário: `++`, `--`
ternário: `... ? ... : ...`

## intervalos e timeout

```javascript
// repete
function print(){
    console.log("Olá mundo!");
}

let myInterval = setInterval(print, 1000)
```

```javascript
// parando o interval
clearInterval(myInterval);
```

```javascript
// delay
setTimeout(print, 1000)
```