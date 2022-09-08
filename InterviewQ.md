### Interview Question
//==========================
```php

var arr = [1, 3, 5, 2, 4];
var filteredValue = arr.filter(function (element, index) {
    return (index % 2 === 0);
});
console.log(filteredValue)
// output == [ 1, 5, 4 ]
// ===========================



let main2 = [1, 3, 5, 2, 4];
let finalValue = main2.map(val => {
    return (Math.pow(val, 2))
})
console.log(finalValue)

// output == [ 1, 9, 25, 4, 16 ]




var arr = [1, 3, 5, 2, 4];
var filteredValue = arr.filter(function (element, index) {
    return (index % 2 === 0)
}).map(index => {
    return  (Math.pow(index, 2))
});
console.log(filteredValue)

// output == [1, 25, 16]
// ===========================




// ===========================
