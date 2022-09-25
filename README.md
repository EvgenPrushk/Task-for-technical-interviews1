## 1. Что будет выведено в консоль

```javascript
function foo1(){
return {
bar: "Hello"
}
}
// bar: "Hello"

function foo2(){
return 
{
bar: "Hello"
}
}
// undefined
```
## 2. Что будет выведено в консоль


```javascript
let firstObject ={name: 'Hello"};
let secondObj = firstObject;
let firstObject ={name: 'Bye"};
console.log(secondObj.name) // {name:"Hello"}   
```

## 3. Что будет выведено в консоль

```javascript
 const first =[1, 2, 3,4];
 const second =[3,4,5,6];
 
```

##4. Как починить

```javascript
for (var i = 0; i < 10; i++){
setTimeout(function(){
console.log(i);
}, 0);
}
 console.log('end');
 // заменить  var  на let
```

##5. Что будет  выведено в консоль

```javascript
function foo(a){
console.log(arguments.length)
foo(1,2,3); // 3  аргумента
```

##5. Что будет  выведено в консоль

```javascript
function а (){
return 2;
}
typeof a; // function, а не {}. Проверку на   массив  Array.isArray(a) //  вернет либо   true  либо  false 

##6. Что будет  выведено в консоль

```javascript
console.log(parseInt('12.3.4.') // 12 console.log(parseFloat('12.3.4.') // 12.3
```

##7. Что будет  выведено в консоль

```javascript
var arr = [0,1,2,4]
console.log(arr.indexOf(3)) /- 1  аналог  includes
```

##7. Что будет  выведено в консоль

```javascript
var arr = [0,1,2,4]
console.log(arr.indexOf(3)) /- 1  аналог  includes
```

##8. Что будет  выведено в консоль

```javascript
div.onclick = function(){alert(1)}
div.onclick = function(){alert(2)} // выведеться только последний  только последний.
```
##9. Что нужно, чтобы удалить ссылку на функциию
Необходимо ссылка на именнованную функцию

