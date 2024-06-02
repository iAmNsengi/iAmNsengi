- 👋 Hi, I’m @iAmNsengi
- 👀 I’m a Software Engineer
- 🌱 I’m currently using NodeJs, Typescript, Express, MongoDB and React Js
- 💞️ I’m looking to collaborate on any Web Based Software
- 📫 How to reach me +(250)785-816-971 and on iamnsengi@icloud.com
- Tools I Use:
  <div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain-wordmark.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/gatsby/gatsby-original.svg" title="Gatsby"  alt="Gatsby" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>
<img src="https://komarev.com/ghpvc/?username=iAmNsengi&style=flat-square&color=blue" alt=""/>
 <img src="https://www.codewars.com/users/iAmNsengi/badges/small"/>


<h2><code> My Favorite Algorithm So far : </code></h2>

```Javascript
  // sumUnique([1, 2, 2, 3, 4, 4, 5]) ==>  1 + 3 + 5 => 9
//   sumUnique([10, 20, 20, 30, 40, 40, 50]) ==> 10 + 30 + 50 => 90 
//  sumUniquey([5, 5, 10, 15, 20, 25, 25]) =>  10 + 15 + 20 => 45

const sumUnique = (arr)=>{
 return Object.entries(arr.reduce(function (obj, value2 ){
    return (obj[value2] ? ++obj[value2] :(obj[value2] = 1),obj)
 },{})).filter(([key,value]) => value  === 1).flat().filter(el => typeof el == 'string').reduce((a,b) => parseInt(a)+ parseInt(b) ,0)
}
```

