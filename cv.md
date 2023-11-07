# Dmitry Markovich
## Frontend Developer

### Contact information:
----

**Phone:** +375 (29) 225-79-98  
**Telegram:** @dima_markovich  
**Email:** dimamarkovich98@gmail.com  
**LinkedIn:** [dmitry-markovich](https://www.linkedin.com/in/dmitry-markovich-1894a218b/)  
**GitHub:** [github-dmitry-markovich](https://github.com/CrazyTapok)  


### Summary
----

I'm a beginner developer. I am proficient in the C# and JavaScript programming languages, worked with the ASP.Net Core framework, MS SQL Server and MySQL, HTML/CSS. Completed an internship at EpolSoft. Worked as a database administrator at the Brest Regional Library. M. Gorky, was involved in the development of websites, setting up networks and maintaining software. Completed courses from IT-Academy, developing web applications in JavaScript, as well as developing websites using HTML, CSS and JavaScript.

### Skills
----

- C#
- .Net
- OOP
- JavaScript
- ASP.Net Core
- Entity Framework (EF) Core
- WPF
- HTML5/CSS3
- MySQL
- MS SQL Server
- Git

### Code Examples
----

Implement the alternate function, which will take an array as the first parameter, and callbacks as the second and third. The function must apply callbacks to the array elements in turn. That is: for the first element - the first callback, for the second element - the second callback, for the third - the first callback again, and so on until the array elements run out.

```JavaScript
  function alternate(array, cb1, cb2) {

    let answer = []

    for (let i = 0; i < array.length; i++) {
      if (i % 2 === 0) {
        answer.push(cb1(array[i]))
      } else {
        answer.push(cb2(array[i]))
      }
    }

    return answer
  }

  let result = alternate(
    ['a', 'b', 'c', 'd', 'e', 'r'],
    function(elem) {
      return elem + '!';
    },
    function(elem) {
      return elem + '?';
    },
  );

  console.log(result); // ['a!', 'b?', 'c!', 'd?', 'e!']
```

### Work Experience
----

**Limited Liability Company "EUROTORG"**  
System Analyst  
08/12/2022 – Present


**Brest Regional Library M. Gorky**  
Database administrator  
18/05/2020 – 01/07/2022


**Trained in the company «EpolSoft»**  
Trainee .Net Developer  
10/02/2020 – 21/03/2020    
Developed a client-server application. Work with ASP.Net Core, MVC pattern, Entity Framework (EF) Core, HTML/CSS, Bootstrap.

### Education
----

**IT Academy**    
09/02/2022 - 01/06/2022    
Web application development with JavaScript


**IT Academy**  
11/10/2021 - 13/01/2022    
Website development with HTML, CSS & JavaScript


**Brest State University named after A.S. Pushkin**
2016 - 2020    
Physics and Mathematics, Applied Mathematic 

### English Language
----

- English: Intermediate (B1)
- Russian: Native
