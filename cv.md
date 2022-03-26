# Tatiana Klimova
#### _Junior frontend developer_

---
##### Contacts:
**E-mail:** lisaw@ya.ru
**Telegram:** @ittatyana
**Discord:** Tatiana K (@1LisaW)
---
#### About me:

I have a rich experience as business analytic and methodologist of banking accounting systems. As a part of the team I collected the business requirements, transformed it into documentation, made manual tests during all lifecycle of new App and delivered project to the client.
Now I'm looking to leverage my project's expertise and passion for programming and problemvsolving for progressive change as a frontend developer.
---
#### Skills:
* CSS 3
* HTML 5
* Java Script
* React, Redux
* d3.js
* Git
* Communication Skills
* Team-Player
____
#### Code example:
[Codewars: Smallest possible sum](https://www.codewars.com/kata/52f677797c461daaf7000740)
```javascript
const checkV = (newArr) => newArr.find( a => a != newArr[0] );
function solution(numbers) {
 let newArr = numbers;
 while( !!checkV(newArr) ){
  let minElem = Math.min(...newArr);
  newArr= newArr.reduce((acc,curr) =>{
     curr = (curr % minElem) ?
      curr % minElem : minElem ;
     acc.push(curr);
     return acc;
  },[]);
 };
 return newArr.reduce(( a, b ) => a + b );
};
```
---
#### Experience:
* Developed interactive charts to visualize statistic information from pull-requests (JSON file) with d3.js framework.
  [diagramPullRequest](https://github.com/1LisaW/diagramPullReq)
* Designed and implemented HTML template of the App for gamification of performance reviews in Sberbank website department
  [Skillopus](https://github.com/1LisaW/skillopus)
---