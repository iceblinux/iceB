# iceB
# Комплекc бухгалтерских программ iceB

## Краткое описание системы

Открытая бухгалтерия “iceB” разработана для работы под управлением POSIX - совместимых операционных систем (POSIX - название международного стандарта на операционные системы). Для разработки использовался язык “С++”. Находится в промышленной эксплуатации с 1992 года. В качестве базы данных используется база данных «MySQL»(R) или «MariaDB»(R). База данных устанавливается на сервере под управлением POSIX - совместимой операционной системы. Доступ к базе данных может осуществляться с любого количества клиентских рабочих мест и с использованием ИНТЕРНЕТ.

Система является универсальной и готова к эксплуатации без доработок на любом предприятии с любым характером деятельности этого предприятия.

### Существует две версии системы:

[iceB_terminal - система с терминальным интерфейсом.](https://iceblinux.github.io/iceB_teminal/)

[iceBw_GTK - система с графическим интерфейсом.](https://iceblinux.github.io/iceBw_GTK)

Функционально обе версии системы идентичны. База данных “MySQL” является клиент-серверной. Это позволяет любому количеству бухгалтеров одновременно работать в одних и тех же подсистемах. Система с терминальным интерфейсом позволяет на клиетском рабочем месте использовать любое оборудование и любую операционную систему. Для осуществления доступа к серверу например из под Windows можно использовать программу «putty». Кроме того терминальный интерфейс позволяет осуществлять доступ к серверу используя Интернет. Система хорошо работает на медленных линиях связи. Терминальная версия работает без проблем и в X-WINDOWS (запускается в консоли «xterm», «gnome-terminal» или любой другой). Система с графическим интерфейсом будет работать только на компъютерах с POSIX - совместимой (Linux/Unix и др.) операционной системой. Также можно запускать в графических терминальных программах в любой операционной системе.

Система распространяется в исходных текстах бесплатно. Кто угодно может скачать исходные тексты собрать систему из исходных текстов и установить систему на своём оборудовании совершенно бесплатно на свой страх и риск. Все консультации по эксплуатации системы могут быть даны разработчиком. Система обеспечивает экспорт данных (платёжные поручения и платёжные ведомости) в подсистемы Клиент-Банк а также бухгалтерскую отчётность в подсистемы Medok и ОПЗ.

### Головная подсистема «Главная книга» не имеет привязки к законодательству и может быть использована в любой стране мира.

## Перечень подсистем

[Главная книга](https://github.com/iceblinux/iceB/wiki/%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F-%D0%BA%D0%BD%D0%B8%D0%B3%D0%B0)

[Материальный учёт](https://github.com/iceblinux/iceB/wiki/%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D1%83%D1%87%D1%91%D1%82)

Платёжные документы

Заработная плата

Учёт основных средств

Учёт услуг

Учёт кассовых ордеров

Учёт командировочных расходов

Учёт путевых листов

Реестр налоговых накладных

Учёт доверенностей

