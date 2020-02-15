
## Name: **Andrii Konovalov**

### **Contact Info:**
* _[GitHub account: **@Garza0**](https://github.com/Garza0)_
* _Email: **konovalovandrey7@gmail.com**_ 
* _Phone number: **+38 097 349 66 92**_

### **Goal:**

I want to be a Front End developer in a good company to improve my skills in JavaScript, Node JS, and frameworks. I realy like new technologies.

### **Skills:**
  * JavaScript
  * HTML/CSS/Sass
  * Node.js/Express
  * React JS


### **Code examples:**
Code for YouTube Video Speed Controller Google Chrome extension

```javascript 
function createNewEl() {
    const element = document.querySelector('.newTime')
    const magEl = document.querySelector('.ytp-time-duration')
    const span = document.createElement('span')
    firstParagraph = text.firstElementChild
    if (!element) {
        magEl.insertBefore(span, firstParagraph)
        span.setAttribute('class', 'newTime')
    } else { 
        element.remove() 
        magEl.insertBefore(span, firstParagraph)
        span.setAttribute('class', 'newTime')
    }
}

function reCalcDur() {
    createNewEl()

    let seconds = document.querySelector('.ytp-time-duration').innerText
    .split(':')
    .reverse()
    .reduce((ss, n, i) => +ss + n * (60 ** i))

    let mult = document.querySelector('.vsc-controller').shadowRoot.children[1].innerText
    seconds /= mult
    document.querySelector('.newTime').innerText += ` (${toHhMmSs(seconds | 0)})`
}

function toHhMmSs(ss) {
    let left = ss % 3600
    let hours = (ss - left) / 3600
    let seconds = left % 60
    let minutes = (left - seconds) / 60
    // return {hours, minutes, seconds}
    if (hours) return hours + ':' + minutes.toString().padStart(2, 0) + ':' + seconds.toString().padStart(2, 0)
    return minutes + ':' + seconds.toString().padStart(2, 0)
}

document.body.onkeydown = function (event) {
    if (event.key == 'b') reCalcDur()
}
```

### **Experience:**

Completed online courses: 

* [**codecademy.com:** html / css](https://www.codecademy.com/profiles/garza0)
* [**FreeCodeCamp:** JavaScript / html / css / sass  ](https://www.freecodecamp.org/certification/garza/javascript-algorithms-and-data-structures)
* **JavaScript v.2.0 / Luschenko Alexandr**
* **JavaScript - The Complete Guide 2020 (Beginner + Advanced) / Maximilian Schwarzmüller**
* **React JS from Zero to Proffesional / Vladilen Minin**
* **Webpack - The Complete Guide 2020 / Vladilen Minin**

Other:
* [Codewars Rank: 5 kyu](https://www.codewars.com/users/Garza0)


### **Education:**
2009-2014 - Automation and Computer Systems (National University of Food Technology)

### **English:**
English level: B1

Lived and talked with native English speakers for about 6 months