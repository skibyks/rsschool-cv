# Alexey Ivanov

## Contacts for communication

_phone_ : +375(29)395-43-13

_Telegram_ : @Alexey_ivanov_1995

## About me :

I have finished the courses "Developing Web Applications with JavaScript" and "Developing Web Applications with HTML / CSS / JavaScript". I really enjoy development and I want to devote all my time to developing and improving my skills in this area. My current job has nothing to do with IT so I would like to change my occupation and do only programming. In the future I plan to become a Full-Stack Developer. I am currently looking for a job as a Frontend Developer (trainee).

- I am
  - single-minded,
  - responsible,
  - diligent,
  - self-disciplined,
  - like to look for solutions to non-standard problems,
  - fond of volleyball

## Skills :

- Programming languages :

  - HTML
  - CSS
  - JavaScript

- Frameworks :

  - jQuery
  - bootstrap
  - materialize

- CVS :
  - Git

## Example of my code :

```
//Импорты с другий js файлов
import { videoPlayerInit } from './videoPlayr.js';
import { radioPlayerInit } from './radioPlayer.js';
import { musicPlayerInit } from './musicPlayr.js';


//объявление переменных констант
const playrBtn = document.querySelectorAll('.player-btn');
const playerBlock = document.querySelectorAll('.player-block');
const temp = document.querySelector('.temp');

//Functions

// функция убирающая не активные блоки(видео аудио музыка)
const deactivationPlayer = () => {
    playrBtn.forEach(item => item.classList.remove('active'));
    playerBlock.forEach(item => item.classList.remove('active'));
    musicPlayerInit.stop();
    radioPlayerInit.stop();
    videoPlayerInit.stop();


}

//обработчик события на каждую кнопку вызывает функцию и деалет активным выделенный блок
playrBtn.forEach((btn, i) =>  btn.addEventListener('click',() => {
        temp.style.display = 'none';
        deactivationPlayer();
        btn.classList.add('active');
        playerBlock[i].classList.add('active');
    })
);


//вызов экстпортируемых функция
videoPlayerInit();
radioPlayerInit();
musicPlayerInit();
```

## Job experience :

I don't have any commercial expeience.

- I have finished the next cousres :
  - Web application development in HTML / CSS / JavaScript [выпускной проект](http://fe.it-academy.by/Sites/0031009/proekt/home/index.html)
    - Stack :
      - HTML
      - CSS
      - JavaScript
      - jQuery
      - bootstrap
  - Web application development in JavaScript [выпускной проект](http://fe.it-academy.by/Sites/0031009/proektJS/index.html)
    - Stack :
      - HTML
      - CSS
      - JavaScript(ES6)
      - Ajax
      - MVC
      - Canvas
  - Glo-Academy online-course [проект](http://fe.it-academy.by/Sites/0030999/Portfolio/index.html) [сылка на Git](https://github.com/skibyks/-Tunes_project)
    - Stack :
      - HTML
      - CSS
      - JavaScript(ES7)

## Education :

- IT-Academy (online-course):
  - Web application development in JavaScript
- IT-Academy (online-course):
  - Web application development in HTML / CSS / JavaScript
- BNTU :
  - Faculty:
    - Energetic
  - Specialization:
    - Electric power systems and networks
  - Specialty:
    - Power Engineer

## Languages :

- English:

  - A1

- Russin:
  - native
