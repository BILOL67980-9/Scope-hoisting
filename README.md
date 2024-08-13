![image](https://github.com/user-attachments/assets/6c2695a8-c985-45f1-87d3-47060d68e9ba)
# JS lectures
## Scope и Hosting

### 1. Scope
- Scope (или "область видимости") - это термин, который описывает область, в пределах которой переменные, функции и объекты могут быть доступны и использованы в программе. Понимание scope критически важно для эффективного управления кодом и предотвращения ошибок.

***Основные типы scope:***
- Global Scope (Глобальная область видимости): Переменные и функции, объявленные в глобальной области видимости, доступны из любой части программы.
- Local Scope (Локальная область видимости): Переменные и функции, объявленные внутри функций или блоков кода, доступны только в пределах этих функций или блоков.
- Block Scope (Область видимости блока): В языках программирования, поддерживающих block scope (например, JavaScript с использованием let и const), переменные видны только в пределах блока кода, в котором они объявлены.

![logo](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2015/08/1439485113Fotolia_83773272_Subscription_Monthly_M.jpg)
  
### 2. Hosting
- Hosting (или "всплытие") - это механизм в языках программирования, который позволяет функциям и переменным быть доступными до их фактического объявления в коде. Это особенно важно в JavaScript и некоторых других языках.

***Как это работает:***
- В JavaScript, когда интерпретатор выполняет код, он сначала "всплывает" (hoists) все объявления переменных и функций в верхнюю часть своей области видимости, но не их инициализацию. Это означает, что функции могут быть вызваны до их фактического определения в коде, а переменные будут инициализированы значением undefined, если к ним обратиться до инициализации.

![logotipe](https://top-kray.ru/images/ex/good/b_60382ec0.jpg)
