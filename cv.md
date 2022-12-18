# Sergey Park
### Junior Frontend Developer

---
### **Contact Information**
*Phone number:* +998 90 969 0605

*E-mail:* sergius.park@gmail.com

[<img style="width: 30px" src="https://img.icons8.com/color/512/telegram-app.png">](https://t.me/parkyhere)
[<img style="width: 30px" src="https://img.icons8.com/color/512/discord-logo.png">](https://discord.com/users/560059726348550164)
[<img style="width: 30px" src="https://img.icons8.com/color/512/linkedin-circled.png">](https://www.linkedin.com/in/sergey-park-a834961b3)
[<img style="width: 30px" src="https://img.icons8.com/color-glass/512/github.png">](https://github.com/parkyhere)
[<img style="width: 30px" src="https://img.icons8.com/fluency/512/codewars.png">](https://www.codewars.com/users/parkyhere)

---
### About Me
I'm an organized, hard working and methodical individual.
I'm a flexible person seeking employment which will allow development, growth and make use of my existing skills.

As a dedicated problem solver, I display a skill in JavaScript and supportning libraries/frameworks that solve real-world problems through code.
My greatest passion is using my technical know-how to benefit other people and companies.

---
### Skills
* HTML5
* CSS3 (Bootstrap, SASS/LESS, BEM)
* JavaScript (ES6+)
* TypeScipt
* Reac(hooks), Redux, MaterialUI
* Git/GitLab/GitHub/Bitbucket

---
### Code Example
[Try on Codewars](https://www.codewars.com/kata/541c8630095125aba6000c00/train/javascript)

***Digital root** is the recursive sum of all the digits in a number.
Given **n**, take the sum of the digits of **n**. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.*
```
    16  -->  1 + 6 = 7
   942  -->  9 + 4 + 2 = 15  -->  1 + 5 = 6
132189  -->  1 + 3 + 2 + 1 + 8 + 9 = 24  -->  2 + 4 = 6
493193  -->  4 + 9 + 3 + 1 + 9 + 3 = 29  -->  2 + 9 = 11  -->  1 + 1 = 2
```
```javascript
function digitalRoot(n) {
  if(n < 10) return n
  let res = 0;
  String(n).split('').map(num => {
    res += Number(num)
  });
  return digitalRoot(res)
}
```
---
### Experience
> June 2022 - current

* Junior Frontend Developer
  - build stable and maintainable application using ReactJS
  - collaborating closely with the team to support project during all phases of delivery
  - monitoring application performance and rectifying front-end-releated issues
  - identifying innovative ideas and proof of concepts according to project requirements

---
### Languages
+ Russian - Native
+ English - B1/B2
+ Korean, German - A1/A2
