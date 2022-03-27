# Tatiana Klimova
#### _Junior Frontend Developer_

---

#### Contacts:
**E-mail:** lisaw@ya.ru
**Telegram:** @ittatyana
**Discord:** Tatiana K (@1LisaW)

---

#### About me:
I have a rich experience as business analytic and methodologist of banking accounting systems. As a part of the team I collected the business requirements, transformed it into documentation, made manual tests during all lifecycle of new App and delivered project to the client.

Now I'm looking to leverage my project's expertise and passion for programming and problem solving for progressive change as a frontend developer.

---

#### Skills:
* CSS 3
* HTML 5
* JavaScript
* React, Redux
* d3.js
* git
* Communication Skills
* Team-Player

---

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

#### Education:
***Faculty of Mathematics and Mechanics*** - _Saratov Chernyshevsky State University_ - 2008
#### Courses:

* Basic HTML & CSS, MIPT
* JavaScript: basics and functions, MIPT
* CSS - The Complete Guide 2022 (incl. Flexbox, Grid & Sass), Academind by Maximilian Schwarzmüller, Online Education;
* Mastering data visualization in D3.js, Adam Janes, Data Visualization Engineer;
* JavaScript Algorithms and Data Structures Masterclass. Colt Steele, Developer and Bootcamp Instructor;
* React + Redux - Professional Development, Juriy Bura, Solution Architect;

---

#### English language:
According to the EF's test [www.efset.org](https://www.efset.org/quick-check) my level of English is in the range of B1 INTERMEDIATE to B2 UPPER INTERMEDIATE
![EF Score](img/englvlEF.png)