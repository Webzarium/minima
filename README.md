#  Minima
##  Восстановление ноды minima

- Добавляем конекты
- https://spartacusrex.com/minimapeers.txt
- Архивные файлы
- https://eurobuddha.com/archive.raw.dat
- https://spartacusrex.com/archive/
- 1 СКАЧАТЬ (https://www.dropbox.com/scl/fi/usgnwtqgj8jqy95akbnfk/archive.raw.dat?rlkey=0th0ll83nlmi0mqwt9yan2cmh&dl=1) архивный файл
- 2 3айти в минидап Security-Archive reset-import seed prase-Upload archive file(Выбрать скачанный файл)
- 3 Указать сид фразу и запустить синхронизацию
- 4 По завершению синхронизации перезагрузить ноду.
- [ВИДЕО. КАК ВОССТАНОВИТЬ НОДУ МИНИМА - КАК ПОДНЯТЬ ВЕРХНИЙ БЛОК | Archive reset | Chain Resync | Backup](https://www.youtube.com/watch?v=Y4V5s16ItN0) 
- [![1280](https://github.com/Webzarium/test1/assets/122037228/b74d2c9d-9840-47db-af31-fc898af0b84d)](https://www.youtube.com/watch?v=Y4V5s16ItN0 "1280")

##  Восстановление ноды minima из бэкапа
### Внимание! Данный метод работает если у вас бэкап не старше двух месяцев.
- Заходим в меню Security
- Restore from backup, Restore, Continue
- Upload an external backup
- Выбираете файл
- Вводите логин от файла backup,  который вы создавали раньше при создании backup файла
- Внимание всегда храните свои пароли в надёжных местах. Компьютер и телефон не надёжные места.
- В поле Archive node host вводите один из портов из файла  https://spartacusrex.com/minimapeers.txt
  Пример host  123.123.123.123:9001
- Жмёте Restore и ждёте  завершения. Можете наблюдать в логах как происходит синхронизация  
- После завершения перезагрузите приложение, необходимо закрыть приложение в фоне и запустить заново.
- В настройке смартфона дайте права запускаться приложению в фоне.
- При синхронизациии убедитесь что у вас стабильный интернет, желательно делать через wi-fi
- Если восстановление не произошло, попробуйте подставить другой ip из файла https://spartacusrex.com/minimapeers.txt
- Или делайте полную синхронизацию  с помощью  архивного файла.
- Рекомендация: делате бэкапы переидически. Хотябы раз в месяц. 

##  Как застейкать монеты minima ?
- Заходим в минидап Maximize
- Выбираете кол-во монет от 1 до 25000
- На какой период будете стейкать и жмёте Maximize my Minima
- Переходите в минидап Pending и делает апрув транзакции
- Ждёте 10 блоков  и можете увидить ваши застейканые монеты в Future Cash
- Пока не прошло 10 блоков в блокчейне, стейкинг можно отменить в минидап Maximize сверху будет колёсико
- Отменяете и делаете апрув транзакции в минидап Pending 
- Увидеть свои застейканые монеты можете в минидапе Future Cash в подменю Future
- Забрать свои монеты можно будет только по истечению срока стейкинга во вкладке Ready
- Раньше срока монеты забрать нельзя

##  Что делать если вы выключаете ноду на месяц и после включения  блоки не могут догнать
- Добавляте пиры в add connections и ждёте 
- https://spartacusrex.com/minimapeers.txt
- Если не получается, тогда делаете полную синхронизацию.
#### Рекомендация 
- Если выключаете ноду, делайте бэкап
- Из бэкапа можно быстро восстановить указав один  хост из файла https://spartacusrex.com/minimapeers.txt
- Схема работает если бэкап не старше 2 месяцев
- 
##  Как поссмотреть сид фразу
- Заходите в Security, Manage seed phrase, Show seed phrase
- Спускаетесь в низ и жмёте Hold to view. Нужно нажать и держать.

##  Инструкция проверки баланса без синхронизации
- Восстанавлиеваем из бэкапа ноду или восстанавлиеваем по сид фразе в меню securtity
- Важно!  Перед проверкой баланса убедитесь что сид фраза на ноде верная. Сравните с той что записано у вас
- Скачиваем файл
- [Mininfo.zip](https://minima.kz/Mininfo.zip)
- Добавляем его в Dapp
- Выбираете скачанный файл [Mininfo.zip](https://minima.kz/Mininfo.zip) и жмёте install
- Заходите в дапку
- Жмёте Balance и ждёте когда обработается команда. Может занять несколько минут
- Если баланс показывает 0 то поссмотрите на транзакции. Если был вывод тогда можете забыть про монеты
- Если баланс 0 и в транзакциях нету вывода монет, значит не правильная сид фраза. Ищите бэкапы, если делали
- Если баланс показывает, тогда делайте повторную синхронизацию... Если после повторной синхронизации нету монет, повторяем синхронизацию до тех пор как монеты отобразяться в вашем колешьке. Можно попробовать сделать на другом телефоне и бэкап перенести  на свой телефон.

- ![image](https://github.com/Webzarium/minima/assets/122037228/ea86b178-a842-446e-aef1-5148d489c211)
- ![image](https://github.com/Webzarium/minima/assets/122037228/305ccd54-3b76-49e1-996f-cbf26ecdd966)
- ![image](https://github.com/Webzarium/minima/assets/122037228/88103175-6de9-4218-8cb7-8ac3bad85668)
- ![image](https://github.com/Webzarium/minima/assets/122037228/cb81feb5-4de4-464a-825b-d767d2010dbe)
- ![image](https://github.com/Webzarium/minima/assets/122037228/e9ca4bb6-95df-4d2b-b279-4c6b1267db52)


