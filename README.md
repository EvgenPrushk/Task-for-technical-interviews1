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

## 4.  Как починить 

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

## 6. Что будет  выведено в консоль

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

##10. Какие мотоды позволяют  переходить по истории 
Back  and forward

##11.  Текущий   url  страницы.
window.location.href

##12.  Спрэд и рэст операторы.
Спрэд операторы
[...'string']
let arr = [1, 2, 3, 4]
let arr2 =[...arr].
Рэст операторы  (упаковывает все аргументы в массиве  )
function(...rest) {
return rest.reduce((total, current) => total + current)
}

##13.  Диструктуризация массива и объекта

```javascript
const objct ={
fisname: 'Marko',
lastName: 'Polo',
position: 'Developer',
year: 2016
}
let {fisname: fName, lastName: lName, position, year}  = objct;
```

##14.  Promise.all  для чего нужен
 Для того, чтобы получить ответы от всех Promise
 
 ##15.    Счастливое число.
 
 ```javascript
 let num=112242335566;
 function(num){
 num=[...String(num)];
 let res ={};
 
if(let i =0; i<num.length; i++) {
if(res[num[i]){
res[num[i]++
} else {
res[num[i]] = 1
}
 }
 let result =0;
 for(let key in res){
 if(res[key] == key){
 rusult =Match.max(result,key);
 }
 }
 return result
 }
```
  ##17. Расплитить строку
  
   ```javascript
let res ={}
str = str.split('&') // ['user.name.firstname=Bob']
str = str.map(i.split('.');

for(let i = 0; i < str.length; i++){
let cur = res
for(let key =0; key <str.[i].length; key++){
 let name =str[i][key]
 if(key = str[i].lenght -1) {
 name = name.split('=')
 cur[name[0]] = decodeUriComponent((name[1]))
 break
 }
 if(cur[name){
 cur = cur[name]
 } esle{
  cur[name] = {}
  cur = cur[name]
 }
}
}


```

  ##18. Результ выполнения 
  
     ```javascript
var a = 5 // a =5 
function f(){
// a = undefined
// не сработает  a = undefined
if(a){

console.log(a)
var a = 10;
}
}

```

 ##19. Результ выполнения 
  
     ```javascript

console.log(a) // a = = undefined
var a = 5 
console.log(b) // type error
let b = 6; 
```

 ##20. Написать функцию inc 
  
     ```javascript
let inc = (function (){
let counter = 0;

return fynction inc(){
counter +1
}
})()
```
 ## 19. Что выведет функция
  
     ```javascript
     const obj = {
     a: 42,
     say: setTimeout( function (){
     console.log(this.a);
     },1000);
          }
     }
     
          const obj = {
     a: 42,
     say: setTimeout( () => { // es6
     console.log(this.a);
     },1000);
          }
     }
     obj.say(); // 42
     
      
       const obj = {
     a: 42,
     say: function (){
     function helper(){
     console.log(this.a);
     }
     setTimeout(helper.bind(this), 1000);
     
          }
     }
     obj.say(); // 42

```

 ## 19. Что выведет функция
  
     ```javascript
    const ex = function(value, sum){ console.log(sum+value)}
    const fx  =ex(null, 10);
   ex(12,7) // 19
   fx(7,12) // 10+ 7 = 17
```

## 20. Что выведет функция
     ```javascript
  let  words = ['a', 'b', 'c', 'd', 'a', 'd']
  const mySort(words) =>{
  const result = [];
  const temp  words.reduce(acc, cur)=>{
  acc[cur] = acc[cur] || 0) +1;
  return acc;
  }, {})
  const keys = Object.keys(temp);
  return keys.sort((a,b) =>{
 return temp[b]- temp[a]
  })
  
  

}
```
## 21. Увеличивать в 2 раза

MyltiByTwo(1,2,3,4,5,6). 
function MyltiByTwo(...restArgs){
return restArgs.map(el => el*2)
}

## 22. Увеличивать в 2 раза

MyltiByTwo(1,2,3,4,5,6). 
function MyltiByTwo(...restArgs){
return restArgs.map(el => el*2)
}

## 23. Увеличивать в 2 раза
function calculate(cb){
return fucntion (a){
return function(b) {
return cb(a,b)
}
}
}

 ## 24 Посчитать  сумму элементов массива
 
  ```javascript
 const array = [1,2,3,4,5,6,6];
 sum = array.reduce((acc, next)=> acc+ next, 0)

```
 ## 25 Максимальный элемент
 
  ```javascript
 const array = [1,2,3,4,5,6,6];
 const  max = array.reduce((acc, next)=> Math.max(acc,next));
 const  max1 = array.sort((x1, x2) => x1-x2)  
 const max2 = array.pop()
const max3 = Math.max(...array); 
```

 ## 26 Сортировка элементов массива
 ``javascript
 const array = [1,2,3,4,5,6,6];

 const  max1 = array.sort((x1, x2) => x1-x2)  
 

```

 ## 27 Сортировка элементов массива с объектов
 ``javascript
 const array = [{name: 'Test1', age: 17},{name:'Test2',age: 20}];

 const  max1 = array.sort((x1, x2) => x1.age-x2.age)  
 //    сортировка по полю  алфавиту
 onst  max1 = array.sort((x1, x2) => {return u1.name.localeCompare(u2.name)})
```
 ## 28 Сортировка элементов массива с объектов
 ``javascript
 const array = [{name: 'Test1', age: 17},{name:'Test2',age: 20}];

 const  max1 = array.sort((x1, x2) => x1.age-x2.age)  
 //    сортировка по полю  алфавиту
 onst  max1 = array.sort((x1, x2) => {return u1.name.localeCompare(u2.name)})
```

 ## 28 Перевернуть массив 
 
 ``javascript
 const array = [1,2,3,4,5,6,6];
  const reversed = array.map((e, index, arr) => arr[arr.length - index - 1]
  const revers1 = [...array].map(array.pop, array)



 ## 28 Перевернуть массив 
 
 ``javascript
 const array = [1,'correct', 0, false, 9, Nan, ''];
 const noFalse = array.filter(n =>!!n);

```
