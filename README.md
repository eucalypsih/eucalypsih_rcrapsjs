# eucalypsih_rcrapsjs

```javascript
console.log(document.location.href);
// Ini hanya membaca URL saat ini.
// Contoh output: "https://www.example.com/page1.html"
```

```javascript
document.location.href = "https://www.example.com/page2.html";
// Browser akan langsung menuju URL baru.
// Sama seperti klik link biasa.
// Menyimpan riwayat halaman sebelumnya, sehingga tombol "Back" berfungsi.
```

```javascript
document.location.assign("https://www.example.com/page2.html");
// Fungsi ini mirip dengan href = ..., browser navigasi ke URL baru.
// Menyimpan riwayat, tombol "Back" bisa digunakan.
```

```javascript
document.location.replace("https://www.example.com/page2.html");
// Mengganti halaman saat ini dengan halaman baru tanpa menyimpan di history. 
// Tombol "Back" tidak akan kembali ke halaman sebelumnya.
// Berguna misal untuk redirect otomatis setelah login.
```

```javascript
document.location.reload(true);
// Memuat ulang halaman saat ini.
```

```javascript
document.location.reload();
// untuk memaksa reload dari server (bukan cache).
```

```javascript
document.location.protocol = 
document.location.host = "www.example.com:443";
document.location.hostname = "www.example.com";
document.location.port = "443";
document.location.pathname = "/page3.html";
document.location.search = "?q=javascript";
document.location.hash = "#section2"; // Navigasi langsung ke elemen dengan ID 'section2'
```

```javascript
let obj = {
    _name: 'John',
    
    get name() {
        return this._name;
    },
    
    set name(value) {
        this._name = value;
    }
};

console.log(obj.name);  // Mengakses getter
obj.name = 'Jane';      // Mengakses setter
console.log(obj.name);  // Mengakses getter lagi
```


```javascript
const o = {
    counter: 0
};
Object.defineProperty(o, "decrement", {
    get() {
        return this.da = 0;
    },
    writeable: true,
    enumerable: false,
    configurable: true
});
console.log(o); // { counter: 0 }
o.decrement
console.log(o); // { counter: 0, da: 0 }
```

```javascript
const o = {};
o.__defineSetter__("fungsiKu",  function(val) {
    this.ano = val;
});
o.fungsiKu = 6;
console.log(o.ano);
```
```javascript
const o = {
    set fungsiKu(val) {
        this.ano = val; 
    }
};
o.fungsiKu = 6;
console.log(o.ano);
```
```javascript
const o = {};
Object.defineProperty(o, "fungsiKu", {
    set(val) {
        this.ano = val;
    }
});
o.fungsiKu = 6;
console.log(o.ano);
```

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


