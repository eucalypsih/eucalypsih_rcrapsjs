# eucalypsih_rcrapsjs
```javascript
const o = {};
o.__defineGetter__("fungsiKu", function () {
    return 5;
});
console.log(o.fungsiKu); // 5
```

```javascript
const o = {
    get fungsiKu() {
        return 5;
    }
};
console.log(o.fungsiKu); // 5
```

```javascript
const o = {};
Object.defineProperty(o, "fungsiKu", {
    get() {
         return 5;
     },
     configurable: true,
     enumerable: true
});
console.log(o.fungsiKu); // 5
```


```javascript
const fruits = {Apples: 450, Bananas: 500};
console.log(Object.entries(fruits)); // [ [ 'Apples', 450 ], [ 'Bananas', 500 ] ]
console.log(Object.fromEntries(Object.entries(fruits))); // { Apples: 450, Bananas: 500 }

```
```javascript
const fruits = {Apples: 450, Bananas: 500};
console.log(Object.values(fruits)); // [ 450, 500 ]
```
```javascript
const fruits = {Apples: 450, Bananas: 500};
console.log(Object.keys(fruits)); // [ 'Apples', 'Bananas' ]
```

NodeJs v20.0.0
```javascript
Object.groupBy();
```


