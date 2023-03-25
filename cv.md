# Maria Voytovich

# Contact Information:
 * **Phone:** +375 29 129-25-33
 * **E-mail:** voit.masha.17@gmail.com
 * **GitHub:** [mariyavoytovich](https://github.com/mariyavoytovich "GitHub Profile")

# About Me:
I enjoy programming and learning new programming languages and new technologies.

# Skils
* JavaScript
* HTML
* CSS
* Git (GitHub)
* Visual Studio Code

# Code Example:

<b>Sorting by bits KATA from CODEWARS</b>: In this kata you're expected to sort an array of 32-bit integers in ascending order of the number of on bits they have.
E.g Given the array [7, 6, 15, 8]: 
* 7 has 3 on bits (000...0111)
* 6 has 2 on bits (000...0011)
* 15 has 4 on bits (000...1111)
* 8 has 1 on bit (000...1000)

So the array in sorted order would be [8, 6, 7, 15].
In cases where two numbers have the same number of bits, compare their real values instead.
E.g between 10 (...1010) and 12 (...1100), they both have the same number of on bits '2' but the integer 10 is less than 12 so it comes first in sorted order.
Your task is to write the function sortBybit() that takes an array of integers and sort them as described above.

```
function sortByBit(arr) {
  var regex = /1/g
  arr.sort((a,b)=>
            { 
              const aBit = a.toString(2).match(regex)?.length || 0;
              const bBit = b.toString(2).match(regex)?.length || 0;
              return aBit == bBit ? a - b : aBit - bBit;
             });
}
```

# Experience
* [RS-School CV](https://github.com/mariyavoytovich/rsschool-cv "CV")
* [Tasks For CodeWars](https://www.codewars.com/users/https://www.codewars.com/users/mariyavoytovich "CodeWars Profile")



