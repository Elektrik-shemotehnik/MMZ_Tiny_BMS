Система контролю і захисту акмулятора від перерозряду та перезаряду
розроблена на базі Малоходачківського машинобудівного заводу імені Ілона Маска
Для захисту від занадто великого струму і короткого замикання використовуйте звичайний 
автоматичний вимикач фірми PromFactor серії Standart або EVO
Функції BMS:
1) Захист від перерозряду акумулятора, в даному випадку при досягненні напруги 2,9В 
виключиться транзистор управління навантаженням по мінусу живлення і зникне +REM
2) Гістерезис по напрзі і затримка по часу - навантаження і +REM включаться тільки після того, 
як напруга на акумуляторі підніметься вище 3,1В і пройде 2с (захист від блимання). 
Коли навантаження i +REM включені засвічується світлодіод HL11, коли виключені - світлодіод погашений.
3) Балансування. Замінивши балансючі резистори можна збільшити струм аж до 5А, 
використовуючи зазначені на схемі деталі. Але не забувайте, що цей струм повінні витримати балансуючі проводи 
і балансуючий роз'єм! Також на резисторах буде виділятися багато тепла, яке слід якось відвести! 
Під час балансування відбувається падіння напруги на балансуючих проводах, через це неможливо виміряти 
справжню напругу на акумуляторі і можна "пропустити" момент перезаряду акумулятора. Цоб цього не відбулося,
балансування включається на 0,5с, після проходження 0,5с виключається на 0,03с для того, щоб зарядилися
фільтруючі конденсатори по живленню і на вході АЦП, і тільки після того проводиться вимірювання і обчислення напруги.
В даному скетчі балансування відбувається на напрузі 4,08В. Під час балансування світиться відповідний світлодіод.
4) Захист від перезаряду - при досягненні напруги 4,15В транзистор відключає мінус зарядного пристрою.
Також подається + батареї на зовнішнє реле, це дозволяє в випадку повного заряд акумулятора, шо стоїть на СЕС,
підключити сонячні панелі до іншого навантаження, наприклад, бойлера, щоб енергія не пропадала надаремно.
Вкрючення заряду відбудеться тоді, коли напруга знизиться до 4,08В, і пройде 20с часу.
Якщо BMS відключає зарядний пристрій засвічується світлодіод HL15
Рекомендований струм через силові транзистори до 15А в випадку використання алюмінієвої плати, через сигнальні - до 2А
Зворотній зв'язок https://t.me/Dj_Elektrik
Мій сайт https://www.elektrik-shemotehnik.pp.ua/
