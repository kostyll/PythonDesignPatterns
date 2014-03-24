GENERATING PATTERNS (ПОРОДЖУЮЧІ ПАТЕРНИ)
========================================

So it is accepted that all design patterns are divided into three groups, and namely generating structural and behavioral. Of course, that could be delete the entry for each of the groups, but in reality, the division into groups is quite important. No wonder the guys from the " gang of four" chose 23 patterns, but no more and no less, and not surprisingly, they divided them into these groups. It's been the main goal of their work - to structure and formalize existing design patterns.

Так уже прийнято, що усі дизайн-патерни поділені на три великі групи, а саме:  породжуючі,  структурні  та  поведінкові.  Звичайно,  що  можна  було  б опустити  вступ  до  кожної  із  груп,  але,  насправді,  поділ  на  групи  має  досить велике  значення.  Не  даремно  хлопці  із  «банди  чотирьох»  вибрали  саме  23 патерни, а не більше і не менше, і недаремно вони поділили їх на ці групи. Це ж було основною метою їхньої роботи – структуризувати та формалізувати вже існуючі дизайн-патерни.


Therefore, generating patterns. The main objective of these patterns is simplify the creation of objects.

Отже,  породжуючі  патерни.  Основним  завданням  таких  патернів є спростити створення об’єктів.


Sometimes you work with a specific set of objects through a group of interfaces. Then I want to create objects only with another set to adapt your code to other conditions. Of course, a group of interfaces through which you operate, remains the same. Simplify the creation of an appropriate set of abstract factory help.

Інколи ви працюєте із певним набором об’єктів через групу інтерфейсів. А тоді хочете створювати об’єкти тільки із іншого набору, щоб пристосувати ваш код  до  інших  умов.  Звичайно,  група  інтерфейсів,  через  які  ви  оперуєте, залишається  та  ж  сама.  Спростити  створення  відповідного  набору  допоможе Абстрактна Фабрика.


And sometimes the structure of an object is very complex and depends on many factors. To simplify the creation of such a facility normally used Builder.

А  інколи структура  деякого об’єкта  дуже  складна  і  залежить  від  багатьох чинників. Щоб  спростити  створення  такого об’єкту  зазвичай використовують Будівельника. 


And to conveniently choose instantsiyuvaty its implementation and, starting from simple terms, you can use the factory method.

А щоб зручно вибрати одну реалізацію та інстанціювати її, відштовхуючись від простої умови, можна використати Фабричний Метод. 


Often there is a problem to get a copy of an existing object, or get the opportunity to quickly generate many similar instances. In this case, the prototype is just useful.

Нерідко  постає  завдання  отримати  копію  уже  існуючого  об’єкта,  або отримати  можливість  швидко  генерувати багато  подібних  екземплярів. У такому випадку Прототип якраз згодиться. 


Fastidious multiplication of objects - the only task that you have to perform the work : you often have to do everything exactly the contrary - have only one instance of the object and not, under any circumstances, to prevent the creation or reference to another instance. The functionality provided by a single instance of a loner.

Вибагливе  множення  об’єктів  —  не  єдине  завдання,  яке  вам  слід  буде виконувати у роботі: вам часто потрібно буде робити все точно навпаки – мати один-єдиний екземпляр об’єкта і, ні за яких обставин, не допустити створення або звертання до ще одного екземпляру. Функціональність єдиного екземпляра забезпечуються Одинаком. 