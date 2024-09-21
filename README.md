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
  if((year % 400 === 0) || ((year % 4 === 0) && (year % 100 !== 0))){
    console.log(`${year} is a Leap Year!`);
  }
  else{
    console.log(`${year} is not a Leap Year!`);
  }
}
isLeapYear(2026);
```
