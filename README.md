# Guide2011-3

Общий гайд по 2011-3 сокету:
*Специально для Зионотреда на 2ch.hk/hw*

# Общие моменты:
1) Пока что дороговато
2) Пока китайплаты особо не нужны ибо в наличие новые/бу платы от брендов
3) Не всем это нужно.

# Олдовый гайд с Зионотреда:
2011-3
Пока неактуален по причине высоких цен. Впрочем, картина потихоньку меняется: в продаже появились серийные 1650v3 по цене в районе 8 т.р: Анлоченый хасвел, в разгоне до 4.5 догоняет i7 8700 non-k. Брендовые маптплаты можно найти от 7 тысяч рублей на тао и ибей до 10 тысяч на авито, дешевые китайские матплаты (HUANAN X99-8M, RUNING X99) на тао от 4 тысяч рублей (от 6 на али). Информации по возможностям китайских плат пока нет. Основная завоздка в данный момент в дорогой DDR4 памяти - комплект самсунгов 4х4 с ибей обходится в 4.5к. 
Так же в продаже можно найти матплату HUANANZHI X99-AD3 на LGA2011-3 с DDR3 по демократичной цене. Однако, Внимание, данная мамка работает только с процессорами, кп которых поддерживает ddr3: E5-2678v3, E5-2629v3, E5-2649v3, E5-2669v3, E5-2696v3, E5-2686v3 (возможно есть и другие):
https://zhuanlan.zhihu.com/p/54821568?edition=yidianzixun&yidian_docid=0L5g3AHy
[YouTube] Предварительный обзор BIOS Huananzhi X99-AD3 Gaming
Для гейминга подходят: 5820к/5960х, E5-1650/1660/1680 v3 (модели с разблокированным множителем), модели 26хх v3 под хаком турбобуста (брать минимум QS, версии с высокими значением турбо-частот (уточнять по cpu-world).
Анонам, которые хотят приличного разгона, стоит брать плату исключительно с OC-сокетом.
Ос-сокет имеет дополнительные ножки питания, на обычном сокете будут заметны фигурные "выемки" на серединах сторон.
4S зионы работают только на Асроке (проверено на QS 4620 v3) и Асусе (тут не 100%, смотрите QVL и гуглите).
Предпочтительно брать Асрок/Асус, особенно если берётся pre-QS или ES камень, для 14/28 и выше под хак лучше всего средний-старший Асус из-за хороших питальников.
Будь осторожнее анон с любым Асусом x99 и Broadwell i7, при разгоне есть риск спалить цпу
Ссылки на темы на Оверах:
https://forums.overclockers.ru/viewtopic.php?f=1&t=577523
https://forums.overclockers.ru/viewtopic.php?f=2&t=517465
Не вошедшее в шапку: https://pastebin.com/NJFQVgE4
Пошаговая инструкция и софт для анлока турбобуста на все ядра для Xeon v3: https://goo.gl/CHSBKV

#Новинка:

И так на июнь 2019 года 2011-3 стал дешеветь ибо поплыли Б/У 1650 в3/5820к/26хх в3 и прочие зионы, а так же память ддр4 б/у - б/у ецц рег.
# Материнские платы

Для этого сокета родными являются только два чипсета под кодовым именем Wellsburg это Десктопный HEDT X99 и серверный C612. 

**Вставить скриншот с характеристиками чипсетов**

## По десктопным и серверным платам:
**ASUS** Десктопные платы: одни из лучших материнских плат для этого сокета. Отличный питальник даже на дешёвых платах. Съёменая флешка BIOS и возможность прошить BIOS при выключенном пк на плдатах подороже. Наличие OC сокета  с доп питанием позоляющего лучше гнать цпу. 

**Из минусов:** 
1. Анон будь с ним осторожен при разгоне Broadwell-E i7 6800k/6850k/6900k/65950x ибо при неправильном разгоне со временем выгорает контроллер памяти в ЦПУ.
2. E5 V4 ES не работают. Циклический ребут. POST не проходит.

Серверные платы: Не самое хорошее качество плат. Есть проблемы с BIOS но и при этом есть 2 платы которые лучше всего подходят для разблокировки турбобуста на 2 ЦПУ: ASUS Z10PE-D16 WS/ASUS Z10PE-D8 WS. Есть проблемы с работой E5 V4 ES но их можно запустить в отличие от десктопных плат.

**ASROCK** Десктопные платы: Идут после Асуса по качеству и взоможностям. Питальник похуже чем у ASUS но всё равно всё хорошо. Брать тоже можно. Серверные платы: Ничего не знаю кроме того что есть платы с DDR3 памятью. 

**GIGABYTE-AORUS:** Многие платы rev 1.0 имеют проблемы которые либо пофиксили новыми версиями BIOS либо же выпуском новой ревизии. E5 V4 ES не работают. Циклический ребут. POST не проходит.

**MSI:** Имеют проблемы с запуском инженерников v3 и памятью которая выше 2133.

**EVGA:** Вроде как проблем нет, кроме FTW-K у которой могут быть проблемы c V4 ES.

**SuperMicro:** Серверные платы, проблем особых с ними нет, но для анлока турбобуста не рекомендуются из-за скудного питальника плат и его охлада. Десктопные платы, ничего не известно в СНГ фактически не встречаются, ну разве что пару раз в Московском регарде. 

**TYAN:** Серверные платы, ничего лично нен знаю. Поэтому дайте инфы...

## Китайплаты:

Полноценной информации нет но как смогу накину тут:
 
 **HUANANZHI X99-AD3:** Плата с чипсетом X99/C612 и с DDR3 памятью. Работает данная плата только с определёнными процессорами E5 v3. А именно: E5-2678v3, E5-2629v3, E5-2649v3, E5-2669v3, E5-2696v3, E5-2686v3.
 
 **Running X99:** Плата с чипсетом X99/C612 и DDR4 памятью. Есть несколько вариантов, с радиатором и без. И разной разцветки. 
 
 **HUANANZHI X99-8M:** Плата с неизвестным чипсетом и DDR4 памятью. Безсмысленный огрызок с 2 каналами, не нужен. 
 
 **PlexHD X99:** Плата с неизвестным чипсетом, вероятнее всего X99/C612. 
 
 По другим платам от китайцев пока ничего не известно.
 
 ## Платы от брендовых серверов/рабочих станций:
 
 Это HP/HPE, Dell, Lenovo/IBM, Cisco, Fujitsu и подобные. У этих плат 100% проприетраные фронт панели, подключение вентиляторов, блока питания. Возможен белый лист на оперативную память и накопители, велика вероятность проприетарного форм-фактора плат и крепления охлаждения цпу.
 
# Оперативная память
 
Подходит любая DDR4 память. У E5 26xx V3 память не гонится т.е. предел для E5 V3 - 2133 и у E5 V4 - 2400. Но разве что чуть-чуть накинуть по шине, но можно снизить тайминги. 
 
 Важный момент: Подтверждено что на 2011v3 десктопных платах от ASUS и ASROCK есть поддержка ECC REG памяти, возможно и на других платах серверная память работает. Так же подтверждено что i7 Haswell-EP i7 5820k, 5930k, 5960x работают с ECC REG памятью. Возможно и на Broadwell-E i7 серверная память работает. 
 
 # Процессоры:
 
Предисловие: 

Для 2011v3 было выпущено два поколения цпу. Haswell-E/EP E5 V3 и Broadwell-E/EP E5 V4. [Про различия в архитектуре можно прочитать на 3DNews](https://3dnews.ru/933795).

Разблокирование турбобуста на все ядра возможно только на процессорах Haswell-E/EP E5 V3.


Существуют 5 видов степпингов процессоров линейки Haswell-E/EP E5 V3:
1. A0 ES0 пример QDCU 2695v3 - обходить стороной ибо самый ранний степпинг, глючный;
2. B0 ES1 пример Q8YG(QFGH) 2695v3, QEYG 2650v3 - так же рекомендуется обходить стороной;
3. L0 ES2 пример QEY6 2695v3, QEYN 2650v3, QF18 2630v3, QEYP 2658v3 - можно рекомендовать к покупке если они очень дешёвые. Турбобуст на них нельзя разблокировать;
4. M0/C0 Pre-QS пример QG7R 2695v3, QG7U 2696v3, QFQK 2683v3 - можно покупать;
5. M1/C1/R2 - QS/OEM-RETAIL пример QGN4 2695v3, QGN7 2696v3, QGN5 2683v3 - 100% можно покупать, фактически это тот же степпинг который продаётся в магазинах, поставляется по OEM каналам производителям оборудования(серверов, рабочих станций).

Для Broadwell-E/EP E5 V4 существуют 2 вида степпингов процессоров:
ES0 и QS-OEM-RETAIL. Брать особого смысла нет.

Ниже находятся таблица со списком существующих финальных Xeon E5 V3 и E5 V4.

**Вставить скриншот таблицы со списком цпу в3 и в4**

**Расписать за оптимальный выбор, расписать за анлок турбобуста и по охладу**
