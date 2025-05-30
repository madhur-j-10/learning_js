# i am learning js and making projects

first project is rock paper scissors

new thing i've learned is Local Storage

```javascript

localStorage.setItem('scores', JSON.stringify(score));
let score = JSON.parse(localStorage.getItem('scores')) || {
            wins: 0,
            loses: 0,
            ties: 0
        };
// these both are local storage methods
```

I've also learned about objects