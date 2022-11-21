# Catherine Krichkovskaya 
## Engineer-constructor
***
## Contact Info
* Tel: +375 44 518 06 86 </br>
* E-mail: krichkovskaya.c@gmail.com </br>
* Discord: Catherine (@SnowYowlie) </br> 
* Linkedin: [Catherine Krichkovskaya](https://www.linkedin.com/in/catherine-krichkovskaya-a594a2256/) </br>
* Telegram: @SnowYowlie </br>
* Git: [SnowYowlie](https://github.com/SnowYowlie) </br>
***
## Summary
Working as an engineer-constructor since 01.06.2022 in "Regula". I am engaged in maintaining design documentation. </br>
I want to became a front-end developer because of the interest of both personal and career growth. The reason is that I stagnate at my main job and do not see such prospects. This direction interested me because of the constant development of technology. </br>
Also, my previous technical education and courses I attended will help me achieve my goals and become highly qualified specialist. </br>
My strengths:
- Perseverance;
- Purposefulness;
- Deep immersion into a problem.
***
## Skills
Engineering:</br>
* CAD/CAE systems:
  * AutoCAD
  * Altium Designer
  * SolidWorks
* Graphics:
    * CorelDRAW

Programming:
 * HTML5/CSS3
 * JS basics
 * Git
 * VS code
 * Sublime Text
 * SQL basics
***
## Code example

<b>Surrounding Primes for a value (kata)</b> </br>
We need a function <i>prime_bef_aft()</i> that gives </br>
the largest prime below a certain given value <i>n</i>, </br>
<i>befPrime</i> or <i>bef_prime</i> (depending on the language),</br>
and the smallest prime larger than this value, </br>
<i>aftPrime/aft_prime</i> (depending on the language). </br>

    function isPrime(num) {
      let value = true;
      for(let i = 2; i < num; i++){
          (num % i === 0) ? value = false : value = value;
          if (value == false) {
              break;
          }
      }
      return value;
    }

    function befPrime(num) {
      for (let i = num - 1; i > 0; i--) {
          if (isPrime(i)) {
              return i
          } else continue;
      }
    }

    function aftPrime(num) {
      for (let i = num + 1; ; i++) {
          if (isPrime(i)) {
              return i
          } else continue;
      }
    }

    function primeBefAft(num) {
      let arrNum = [];
      arrNum.push(befPrime(num), aftPrime(num));
      return arrNum;
    }

***
## Experience

<b>Regula</b> / Engineer-constructor</br>
June 2022 - present

Responsibilities:
* Archiving;
* Development and adjustment of design documentation in CAD-systems;
* Creating 3D-models in CAD/CAE-systems.
***
## Education
### <i>University:</i>

<b>BSUIR</b> / Bachelor’s degree, Electronics engineer </br>
2018 - 2022

### <i>Certificates:</i>

<b>TeachMeSkills</b> / Front-end developer</br>
August 2022 - present
***
## Language
<b>English</b> - B2 </br>
<b>Russian</b> - Native 