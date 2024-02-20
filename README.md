#  Minima

## Внимание! Изучите инструкцию несколько раз. Данный гайд создан только для смартфонов.
## Прежде чем задать вопрос в чате, чтобы решить быстро вашу проблему - дайте полную информацию
Где стоит нода?
Подробное описание что делали.
Какая проблема возникла?
## Уважайте своё и чужое время...
- В Телеграм канале есть бот где можете найти полезную информацию и ссылки о блокчейне Minima.
- Присоединятесь https://t.me/minima_ru
- Чтобы вызвать в телеграмм боте нужную информацию вводите следующий знак /
- И дальше выбираете что вам нужно. 

![image](https://github.com/Webzarium/minima/assets/122037228/04cb3ee4-b9eb-4425-a291-80048d45b906)



##  Восстановление ноды minima по сид фразе.

- Добавляем конекты. Заходим в Settings, Add connections, вводите ссылку https://spartacusrex.com/minimapeers.txt
- Можете попросить в дискорде или телеграмме проекта чтобы кто-нибудь поделился актуальными пирами.
- Скачиваете архивные файлы.  Желательно скачивать псоледний. Ниже ссылки где можно скачать.
- https://spartacusrex.com/archive/  Выбирайте по датам более свежий архивный файл.
- https://eurobuddha.com/archive.raw.dat
- 1 СКАЧАТЬ архивный файл
- 2 3айти в минидап Security - Archive reset - import seed prase - I have an archive file - Select archive file - Upload archive file(Выбрать скачанный файл)
- 3 Указать сид фразу и запустить синхронизацию
- 4 По завершению синхронизации перезагрузите приложение, необходимо закрыть приложение в фоне и запустить заново.
В настройке смартфона дайте права запускаться приложению в фоне.  Как это сделать ищите в интернет, т.к. для каждой модели смартфона это делается по разному

#### Что делать если не получается восстаноить ноду.
- 1 Проверяем правильная ли сид фраза на ноде. Где поссмотреть сид фразу, читайте ниже.
- 2 Пробуем синхронизировать повторно через архинвый файл, повторно сид фразу вводить не нужно.
- Заходите Security - Archive reset - Chain re-sync - I have an archive file - выбираете Upload an archive file - выбирайте скаченый файл - Continue
- 3 Попробовать сделать на другом сматфоне. более мощном и потом перенести бэкап на ваш телефон.
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

- Заходим в Settings, Add connections, вводите ссылку https://spartacusrex.com/minimapeers.txt или 
- Можете попросить в дискорде или телеграмме проекта чтобы кто-нибудь поделился актуальными пирами.
- Желаетльно чтобы интернет был стабильный и через wifi .
- Можно попробовать перезапустить приложение и подождать немного.
- Если нода не может догнать актуальные блокои, тогда делаете полную синхронизацию.
#### Рекомендация 
- Если выключаете ноду, делайте бэкап
- Из бэкапа можно быстро восстановить указав один  хост из файла https://spartacusrex.com/minimapeers.txt
- Схема работает если бэкап не старше 2 месяцев

##  Как посмотреть сид фразу
- Заходите в Security, Manage seed phrase, Show seed phrase
- Спускаетесь вниз и жмёте Hold to view. Нужно нажать и держать.

##  Что делать если не можете отправить все монеты которые отображены на балансе ?
![image](https://github.com/Webzarium/minima/assets/122037228/4428b9c8-d6ad-4cdf-b75c-41c0fc68c023)
- У вас на ноде 64 адреса и на  балансе показывает общую сумму. Отправлять монеты можете не переключаясь между кошельками.
- Если вам не даёт отправить все монеты которые доступны  на балансе сделайте консолидацию
- Как сделать консолидацию монет на ноде?
- Заходите в wallet - send - сверху меняете с Value transfer на Consolidate - Review
- После заходите в Pending и делаете апрув транзакции. 
- Остаётся подождать, когда закончится консолидация.
####  Внимание! 
- Если монеты в стейкинге или в смартконтракте Vestr, эти монеты вы не сможете отправить. Отправить сможете только не заблокированые монеты




##  Инструкция проверки баланса без синхронизации
- Восстанавливаем из бэкапа ноду или восстанавливаем  по сид фразе в меню securtity
- Важно! Перед проверкой баланса убедитесь, что сид фраза на ноде верная. Сравните с той что записано у вас
- Скачиваем файл [Mininfo.zip](https://minima.kz/Mininfo.zip)
- Добавляем его в Dapp
- Выбираете скачанный файл [Mininfo.zip](https://minima.kz/Mininfo.zip) и жмёте install
- Заходите в дапку
- Жмёте Balance и ждёте, когда обработается команда. Может занять несколько минут
- Если баланс показывает 0, то посмотрите на транзакции. Если был вывод тогда можете забыть про монеты
- Если баланс 0 и в транзакциях нету вывода монет, значит не правильная сид фраза. Ищите бэкапы, если делали
- Если баланс показывает, тогда делайте повторную синхронизацию. Если после повторной синхронизации нету монет, можно попробовать сделать на другом телефоне и бэкап перенести на свой телефон


- ![image](https://github.com/Webzarium/minima/assets/122037228/ea86b178-a842-446e-aef1-5148d489c211)
- ![image](https://github.com/Webzarium/minima/assets/122037228/305ccd54-3b76-49e1-996f-cbf26ecdd966)
- ![image](https://github.com/Webzarium/minima/assets/122037228/88103175-6de9-4218-8cb7-8ac3bad85668)
- ![image](https://github.com/Webzarium/minima/assets/122037228/cb81feb5-4de4-464a-825b-d767d2010dbe)
- ![image](https://github.com/Webzarium/minima/assets/122037228/e9ca4bb6-95df-4d2b-b279-4c6b1267db52)


