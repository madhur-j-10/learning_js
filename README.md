# i am learning js and making projects



```javascript

localStorage.setItem('scores', JSON.stringify(score));
let score = JSON.parse(localStorage.getItem('scores')) || {
            wins: 0,
            loses: 0,
            ties: 0
        };
# these both are local storage