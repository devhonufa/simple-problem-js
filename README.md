- Function to generate a random number between 1 and 6
```
function rollRanNum() {
  return Math.floor(Math.random() * 6) + 1;
}

print the result to the console
console.log(rollRanNum());
```
- How can we alphabetically arrange the student's names in all our classrooms?
```
const students = ["Parvez", "Honufa", "Ruksana", "kadija", "salman"];
students.sort;
console.log(students);
```
- How can we arrange the student's roll in all our classrooms?
 ```
const roll_numbers = [3, 5, 2, 6, 1, 30];

console.log(roll_numbers.sort(function(a, b){
  return a - b;
}));
```
- How can I find out which year is a leap year?
```
 function isLeapYear(year){
  if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)){
    console.log(`${year} is a Leap Year!`);
  }
  else{
    console.log(`${year} is not a Leap Year!`);
  }
}
isLeapYear(2026);
```
### Leap Year Logic:

- year % 4 === 0: The year is divisible by 4.
- year % 100 !== 0: The year is not divisible by 100 (except if divisible by 400).
- year % 400 === 0: If the year is divisible by 100, it must also be divisible by 400 to be a leap year.


### How can we find duplicate numbers in javascript?
```
const numbers = [1, 4, 3, 5, 5, 7, 8, 9, 3, 10, 4];

const duplicateNumbers = numbers.filter(function(value, index, array){
  return array.indexOf(value) !== index
});
console.log(duplicateNumbers);
```

### How can we find unique numbers in Javascript?
```
const uniqueNumber = [1, 4, 3, 5, 5, 7, 8, 9, 3, 10, 4];

const uniqueNumbers = uniqueNumber.filter(function(value, index, array) {
  return array.indexOf(value) === index
});

console.log(uniqueNumbers);
```

