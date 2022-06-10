# Maria Belyanskaya

## Junior Frontend Developer

***

## Contact information:

Phone: +7 916 9111051

E-mail: belkamaria@gmail.com

Telegram: @belkamaria

***

## Briefly About Myself:

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

***

## Skills and Proficiency:

HTML5, CSS3

JavaScript Basics

Git, GitHub, GitLab

VS Code, WebStorm

***

## Code example:

`        function Calculator () {

            this.calculate = function (str) {

                let calcArray = str.split(' ');

                let first = +calcArray[0],

                    second = +calcArray[2],

                    operator = calcArray[1];

                if (calcArray.length !== 3 || !isFinite(first) || !isFinite(second)) {

                    return "Неверно заданы числа, либо отсутствуют пробелы в строке: " + str;

                } else {

                    if (this.metods[operator] === undefined) {

                        return "В калькуляторе отсутствует оператор " + operator;

                    } else {

                        return this.metods[operator] (first, second);

                    }

                }

            }

            this.metods = {

                "+": (a, b) => a + b,

                "-": (a, b) => a - b,

            };

            this.addMethod = function (name, func) {

                this.metods[name] = func;

            }

        }
`

***

## Courses:

JavaScript Manual on learnjavascript.ru (in progress)

RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

Innopolis University Course «Fundamentals of Frontend Development» (in progress)


***

## Languages:

English - Pre-Intermediate

Russian - Native
