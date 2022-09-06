# Artem Lobovskii
![my_photo](/images/my_photo.jpg)

***

## Contacts

- Email: lobovskiy@yandex.ru
- Phone: +7 953 654 21 45
- RS School Discord: [Artem Lobovskii (@lobovskiy)](https://discordapp.com/users/646052700877750323/)

***

## About myself

I've been working as a Junior Frontend Developer in the "MMTR Technology" since January 2022. I practice in web technologies and development tools and have ambitions to become a good specialist in web development. I use React + Redux, know JavaScript, can work with Webpack, Git, Docker. I've created several commercial websites and maintain them so far.

I have rich experience in network administration and telecommunications sector, have a solid basic knowledge of network protocols and basic network services, understand the principles of operation of server equipment, PBX, client-server architecture, virtualization technologies.

Also I used to set up, repair and sell computer and network equipment as an individual entrepreneur. I've acquired good soft skills working there, and know how to establish communicative relations.

In my spare time, I practice with cloud computing and services (in particular with Amazon Web Services), learn English with a personal teacher and do boxing.

***

## My skills

- HTML5, CSS, SASS, LESS
- JavaScript, jQuery
- React, Redux, Redux Toolkit
- Webpack
- Git, Github, Gitlab
- Docker
- AWS
- OSI
- Cisco
- Adobe Photoshop, Microsoft Office

***

## Code example

Here is solution of [Array Deep Count Kata](https://www.codewars.com/kata/596f72bbe7cd7296d1000029) on Codewars: *Your task is to create a function deepCount that returns the number of ALL elements within an array, including any within inner-level arrays*

```
function deepCount(a){
  let sum = 0;
  
  function getSum(arr) {
    if (!arr.length) {
      return;
    }
    
    const lastElement = arr.pop();
    
    if (Array.isArray(lastElement)) {
      getSum(lastElement);
    }
    
    sum += 1;
    getSum(arr);
  }
  
  getSum(a);
  
  return sum;
}
```

***

## Work experience

Since April 2022 I have been working in team of 10 people on the web application which is the portal for moderation of trading violation reported with mobile application. It's being developed using React, LESS, Java, PostgreSQL. I work on developing frontend application with React, Redux, Saga.

***

## Education

- **Kostroma State Technological University**
  - Automation of technological processes and production
- **Udemy**
  - [JavaScript and React](https://www.udemy.com/course/javascript_full/)

***

## Languages

- Russian - Native
- English - Upper-intermediate

I've been learning English with a personal teacher for more than a year and here is my result of passing the [EF SET quick test](https://www.efset.org/quick-check/):

![english-test-result](/images/efset-test-result.jpg)