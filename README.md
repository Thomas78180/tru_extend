# tru_extend

Use as jQuery $.extend() method

## Usage
```javascript
const extend = require('tru_extend');

var a = {
    toto: 'toto',
    tata: 'tata',
    a: {
        c: 'c'
    }
};

var b = {
    toto: 'toto2',
    titi: 'titi',
    a: {
        b: 'a'
    }
};

console.log(extend(true, a, b));
/*
{
    toto: 'toto2',
    tata: 'tata',
    a: {
        c: 'c',
        b: 'a'
    },
    titi: 'titi'
}
*/
```