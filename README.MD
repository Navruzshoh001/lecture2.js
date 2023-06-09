# lecture2.js
## Table of Contents

> --> SCOPE
>
> --> HOISTING
> 
> --> RECURSION
>
> --> CLOUSER

## Scope (Область видимости)

>Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global: Global variables are those declared outside of a block. Local variables are those declared inside of a block.

>-Область действия в JavaScript относится к текущему контексту кода, который определяет доступность переменных для JavaScript. Существует два типа области видимости: локальная и глобальная: глобальные переменные — это переменные, объявленные вне блока. Локальные переменные — это переменные, объявленные внутри блока.

>There are 4 types of scope :
> 
> - 1) Global scope : In a programming environment, the global scope is the scope that contains, and is visible in, all other scopes.

>-Глобальная область: в среде программирования глобальная область — это область, которая содержит и видна во всех других областях.
>
> - 2) Function scope : A function creates a scope, so that (for example) a variable defined exclusively within the function cannot be accessed from outside the function or within other functions.


>-Область действия функции: функция создает область действия, так что (например) переменная, определенная исключительно внутри функции, не может быть доступна извне функции или внутри других функций.
>
> - 3) Block scope : Block scoped variables: A block scoped variable means that the variable defined within a block will not be accessible from outside the block. A block can reside inside a function, and a block scoped variable will not be available outside the block even if the block is inside a function.


>-Область действия блока: переменные области действия блока: переменная области действия блока означает, что переменная, определенная в блоке, не будет доступна извне блока. Блок может находиться внутри функции, и переменная области блока не будет доступна вне блока, даже если блок находится внутри функции.
>
> - 4) Module scope : In modules, a variable declared outside any function is hidden and not available to other modules unless it is explicitly exported. Exporting makes a function or object available to other modules. In the next example, I export a function from the sequence.


>-Область модуля: в модулях переменная, объявленная вне какой-либо функции, скрыта и недоступна для других модулей, если только она не экспортирована явно. Экспорт делает функцию или объект доступными для других модулей. В следующем примере я экспортирую функцию из последовательности
>
>![](https://res.cloudinary.com/practicaldev/image/fetch/s--lI9XvHjf--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i.ibb.co/vJhg635/Scope.png)

## Hoisting (Подъем)

> JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code. Hoisting is not a term normatively defined in the ECMAScript specification.

>Подъем JavaScript относится к процессу, при котором интерпретатор, по-видимому, перемещает объявление функций, переменных или классов в верхнюю часть их области видимости перед выполнением кода. Подъем не является термином, нормативно определенным в спецификации ECMAScript.
>
>![](https://i.ytimg.com/vi/EvfRXyKa_GI/maxresdefault.jpg)

> - Being able to use a variable's value in its scope before the line it is declared. ("Value hoisting")
>
>![](https://www.tutorialsteacher.com/Content/images/js/hoisting.png)
>
>![](https://res.cloudinary.com/practicaldev/image/fetch/s--UkSuyTRW--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/yf0z2gqviit8ouds4gz0.png)

## Recursion (Pекурсия)

>Recursion is a programming technique useful in childhood where a task can be naturally divided into several similar but simpler tasks. Or when the task can be simplified to simple actions plus a simple version of the same task. Or, as we shall see, to work with certain data structures.
Рекурсия — это метод программирования, полезный в детстве, когда задачу можно естественным образом разделить на несколько похожих, но более простых задач. Или когда задачу можно упростить до простых действий плюс простой вариант той же задачи. Или, как мы увидим, для работы с определенными структурами данных.
>
>![](https://i.ytimg.com/vi/vLhHyGTkjCs/maxresdefault.jpg)

## Closure (Закрытия)

>A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function.
Замыкание — это комбинация функции, связанной вместе (вложенной) со ссылками на ее окружающее состояние (лексическое окружение). Другими словами, замыкание дает вам доступ к области действия внешней функции из внутренней функции.
>
>![](https://www.freecodecamp.org/news/content/images/2020/05/image-147.png)# Lecture2-JavaScript