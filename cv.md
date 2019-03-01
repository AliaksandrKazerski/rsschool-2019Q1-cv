# My resume
1. Aliaksandr Kazerski
2. Minsk, Rokossovskogo avenue, h. 76, ap 55
3. I love learning to look for new information and solve problems. 
I like to do something with my own hands applying my new knowledge.
I believe that if you are doing something, then it must be well, or not do it.
Very interesting js because this language can be used to solve easy and difficult tasks.
4. I'm learning js, html, css. git Familiar with c and java.
5. ```javascript
  module.exports = function getZerosCount(number, base) {
  var prNum = [2], resultArr = [];
  next:// create an array of primes range from 0 to base
  for (var i = 2; i <= base; i++) {
    for (var j = 2; j < i; j++) {
      if (i % j === 0) {
        continue next;
      }
      if (i !== prNum[prNum.length - 1])
      prNum.push(i);
    } 
  }
  for (i = 0; i < prNum.length; i++) { // loop divides base into prime numbers and divides number into this prime numbers
    if (base === 1) { 
      break;
    }
    var count = 0, result = 0, numLoop = number;
    while (base % prNum[i] === 0){ 
      count++; // save pow
      base /= prNum[i];
    }
    while (numLoop >= prNum[i]) {
      numLoop = Math.floor(numLoop / prNum[i]);
      result += numLoop;
    }
    resultArr.push(Math.floor(result / count));   //  pow needed here and result push on array
  }
  return Math.min(...resultArr); // return min result from array
}
```
6. I do not have experience.
7. BNTU faculty Mechanics And Technology. 
8. A2. I use the English language at work when I need to communicate with foreigners
