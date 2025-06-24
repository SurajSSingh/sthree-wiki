---
id: knevre2p58xwvlhvmz0pwu1
title: SILT#00073
desc: 'Something I learned today for 2025, June 20'
updated: 1750566778578
created: 1750486076290
bluesky: 
---

SILT#00073: If you are asked to choose a prime number between 200 and 210, save your energy because there are no primes in that range. In fact, the primes 199 and 211 bookend these ranges. There are others like this (a round range with a gap at least 10), but I wonder the first that has a gap of 100

## Additional Notes

My terrible JavaScript code for looking for this:

```js
const numbers = 1_000_000;
const primes = new Set([2]);

for(let n = 3; n < numbers; n++){
    let isPrime = true;
    for (const p of primes) {
        if (n % p === 0){
            isPrime = false;
            break;
        }
    }
    if(isPrime){
        primes.add(n);
    }
}

const ranges = [];
const range_window = 10; 


for(let n = 0; n < numbers; n=n+range_window){
    let isClear = true;
    for(let i = n; i < n+range_window; i++){
        if(primes.has(i)){
            isClear = false;
            break;
        }
    }
    if (isClear){
        ranges.push(n);
    }
}

console.log(ranges)
```
