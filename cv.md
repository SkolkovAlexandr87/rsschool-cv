# Skolkov Alexander
![Photo](photo.jpg)
***
## Contact information:
  **Phone:** +79108886323\
  **E-mail:** Alexand333@mail.ru
***
## About Me:
  At the moment I have been working as a software-controlled machine tool adjuster since 2009.In 2020, he became interested in programming.I started to get acquainted with the C# programming language.I studied using literature and an application with training courses (Stepic).I didn't like the syntax in C#.
  
  In parallel with the study of C #, they suggested trying to take an interest in front-end development.I started learning HTML, CSS.  I studied HTML based on materials on various websites. I studied CSS from the book "The Big Book of CSS". I really liked this direction.

  At the moment I'm learning JavaScript using a website [learn.javascript.ru](https://learn.javascript.ru).JavaScript I find it more convenient for myself in comparison with C#.

   In training, if there is no access to a computer or there is no opportunity to study on a PC, the smartphone application helps a lot [EasyHTML](https://apps.apple.com/ru/app/easyhtml/id1344902528).

   In general, I like the constant development and study of various materials in this direction (front-end).Working in his current profession, unfortunately, there is no possibility of development.
***
## Skills:
  * HTML
  * CSS
  * JavaScript
  * Git, GitHub
  * VSCode  
***
## Code Example.

#### Valid Braces.

  Write a function that takes a string of braces, and determines if the order of the braces is valid. It should return `true` if the string is valid, and `false` if it's invalid.


  All input strings will be nonempty, and will only consist of parentheses, brackets and curly braces: `()[]{}`.

  What is considered Valid?
  A string of braces is considered valid if all braces are matched with the correct brace.


#### Examples:
```
  "(){}[]"   =>  True
  "([{}])"   =>  True
  "(}"       =>  False
  "[(])"     =>  False
  "[({})](]" =>  False

```
#### Solution:
```
function validBraces(braces){
  //TODO 
        let arrStr = braces.split(''),
            open = ['(', '{', '['],
            close = [')', '}', ']'],
            stack = [],
            openInd,
            closeInd;
  
        for (let i = 0, j = arrStr.length; i < j; i++) {
          openInd = open.indexOf(arrStr[i]);
          
          if(openInd !== -1) {
            stack.push(openInd);
            continue;
          }
          
          closeInd = close.indexOf(arrStr[i]);
          
          if(closeInd !== -1) {
            openInd = stack.pop();
            
            if(openInd !== closeInd) {
             return false;
           }
          }
         }
         
         if(stack.length !== 0) {
           return false;
         }
  
         return true;
}

```
***
## Cousers:
  * HTML and CSS lessons (completed)
  * JavaScript Guide [learn.javascript.ru](https://learn.javascript.ru) (in progress)
  * RS Schools course "JavaScript/Front-end. Stage 0" (in progress)

***

## English language.
  * Entry level - A1
