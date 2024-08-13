# README
## Scope и Hosting

### 1. Scope
- Scope (или "область видимости") - это термин, который описывает область, в пределах которой переменные, функции и объекты могут быть доступны и использованы в программе. Понимание scope критически важно для эффективного управления кодом и предотвращения ошибок.

***Основные типы scope:***
- Global Scope (Глобальная область видимости): Переменные и функции, объявленные в глобальной области видимости, доступны из любой части программы.
- Local Scope (Локальная область видимости): Переменные и функции, объявленные внутри функций или блоков кода, доступны только в пределах этих функций или блоков.
- Block Scope (Область видимости блока): В языках программирования, поддерживающих block scope (например, JavaScript с использованием let и const), переменные видны только в пределах блока кода, в котором они объявлены.

![logo] (https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2015/08/1439485113Fotolia_83773272_Subscription_Monthly_M.jpg)
  
### 2. Hosting
- Hosting (или "всплытие") - это механизм в языках программирования, который позволяет функциям и переменным быть доступными до их фактического объявления в коде. Это особенно важно в JavaScript и некоторых других языках.

***Как это работает:***
- В JavaScript, когда интерпретатор выполняет код, он сначала "всплывает" (hoists) все объявления переменных и функций в верхнюю часть своей области видимости, но не их инициализацию. Это означает, что функции могут быть вызваны до их фактического определения в коде, а переменные будут инициализированы значением undefined, если к ним обратиться до инициализации.

![logo]([https://s1.1zoom.me/big0/295/Rivers_Bridges_Sunrises_and_sunsets_Sky_Lightning_547598_1248x1024.jpg](https://avatars.mds.yandex.net/i?id=9082cdcf69fa7f72125a32998e92e0c7_l-4033943-images-thumbs&n=13))
