Јана Јовчевска, 213002

Control Flow Graph 

![SI_lab2](https://github.com/janajovchevska/SI_2023_lab2_213002/assets/128175593/ce98189b-03ba-4743-95dd-ca25c23eb380)

Цикломатска комплексност

Цикломатската комплексност на овој код е 11 и истата ја добив со броење на рагионите од Control Flow Graph-от, и ја потврдив со формулата за предикатни јазли+1.

Тест случаи според критериумот Every Branch

![image](https://github.com/janajovchevska/SI_2023_lab2_213002/assets/128175593/72dd3b6e-070f-4816-9906-cb60aef214f6)

-> Во првиот тест случај user==null, затоа се фрла exception.

-> Во вториот тест случај username e janaj, password е 123+56789 (содржи специјален знак), email е jana@gmail.com

-> Во третиот тест случај username е null (ќе се стави email како username), password е 123 (краток, <8 карактери), email janagmail.com (не содржи @)

-> Во четвртиот тест случај username e ninah, password е si+ a12345 (содржи празно место), email е nina@gmail.com, се тестира случај кога имаме ист username и email со веќе постоечки корисник

-> Во петтиот тест случај username е јанај, password е 123456789 (не содржи специјален знак), email е jana@gmailcom (не содржи .)

Tест случаи според критериумот Multiple Condition

![image](https://github.com/janajovchevska/SI_2023_lab2_213002/assets/128175593/1f3b1e8f-fc88-4493-9547-08338560e185)


-> Во првиот тест случај првиот услов (user==null) ќе се исполни и ќе се фрли exception, не се важни останатите два

-> Во вториот тест случај вториот услов (user.getPassword()==null) ќе се ислполни и повторни ќе се фрли exception,
при што не е важен третиот услов, а првиот нема да биде точен

-> Во третиот тест случај третиот услов (user.getEmail()==null) ќе се исполни и ќе се фрли exception, а претходните два ќе бидат неточни

-> Во четвртиот и последен тест случај ниеден од условите нема да се исполни и нема да се фрли exception, ќе продолжи да се извршува кодот



