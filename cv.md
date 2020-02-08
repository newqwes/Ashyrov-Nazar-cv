# Ashirov Nazar

Front End Developer

## Contacts

- Phone: +375256573217
- Mail: newnewqwes@gmail.com
- Github: @newqwes

## Objective

I like to create something new, modern, something that can be useful for society, as well as the process of visualizing code in a beautiful application.

## Work Experience

No have work experience. I’m self-taught, and I do projects on lessons.

## Technical Skills

- HTML & CSS
- Bootstrap
- JS, JQuery
- Gulp, SASS
- React and Redux
- PHP

## Code examples

I tried to write a roulette game myself

```
let myMoney = prompt("Введите количество ваших денег:");

myMoney = myMoney - 1;
myMoney = myMoney + 1;
document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";


function betColor(newColor) {
    let randomNumber = Math.floor(Math.random()*101);
    if ( newColor === 'red') {
        if (randomNumber >= 49) {
            myMoney = myMoney - 1;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("Не угадал");
        }
        else {
            myMoney = myMoney + 1;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("Молодец!");
        }

    }
    else if ( newColor === 'black') {

        if (49 < randomNumber <= 98) {
            myMoney = myMoney + 1;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("Отлично, всегда ставь на черное!");
        }
        else {
            myMoney = myMoney - 1;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("Не повезло");
        }
    }
    else if ( newColor === 'zero') {

        if (randomNumber > 98) {
            myMoney = myMoney + 10;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("ПОБЕДА!!! ВОТ ЖЕ ВЕЗЕНИЕ!");
        }
        else {
            myMoney = myMoney - 1;
            document.getElementById("h11").innerHTML = "Ваши деньги: " + myMoney + "$";
            alert("Прости, не выпало, попробуй еще");
        }
    }


}
```

## Education

I graduated from the GRSU, specialty: computer security.

## English

Courses Mr.English Level A2
