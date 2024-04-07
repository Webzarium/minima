#  Minima

## Внимание! Изучите инструкцию несколько раз.
- https://www.minima.global/
- https://t.me/minima_ru
- https://discord.com/invite/minima
## Прежде чем задать вопрос в чате, чтобы решить быстро вашу проблему - дайте полную информацию
- Где стоит нода?
- Подробное описание что делали.
- Какая проблема возникла?
## Уважайте своё и чужое время...
- В Телеграм канале есть бот где можете найти полезную информацию и ссылки о блокчейне Minima.
- Чтобы вызвать в телеграмм боте нужную информацию вводите следующий знак /
- И дальше выбираете что вам нужно.
![image](https://github.com/Webzarium/minima/assets/122037228/04cb3ee4-b9eb-4425-a291-80048d45b906)

## WMINIMA и MINIMA
-  WMINIMA  обёрнутый токен MINIMA в сети Эфира
- Каждый WMINIMA обеспечен 1:1 заблокированным Native Minima, Holding Wrapped фактически удерживает Native.
- Будет механизм, с помощью которого держатели Wrapped смогут конвертировать их в Native, когда мы их внесем в листинг, если захотят.
- При этом вполне возможно, что сам обёрнутый токен может найти применение в некоторых партнерских проектах, над которыми мы работаем. Хотя на данный момент я не могу сказать большего.

## Где мои монеты minima ?

- Если вы участвовали в тестнете и не следили за проектом, то сокрее всего вы не проходили верификацию и не делали запрос монет.
- Командой было выделено полгода для решения всех проблем связанный с получением наград.
- Как вы отнеслись к проекту, такой результат и получили.
- Поезд никого не ждёт ))
- https://www.youtube.com/watch?v=sdECEu5ZX7g

## График поощрительных вознаграждений:

- Начало проверки примерно в январе 2023 года.
- Распределение вознаграждений по программе поощрения 21 марта 2023 г.
- Окончание распределения 25 августа 2023 года.

График выплаты вознаграждений за лояльность от начала до конца:

- Начало подачи заявки 10 октября 2023 г.
- Окончание подачи заявки 22 октября 2023 г.
 - Начало выплат 26 октября 2023 г.
- Окончание выплаты 07 ноября 2023 г.

## Инструкция установки ноды на сервере
https://docs.minima.global/docs/runanode/get_started/


##  Восстановление ноды minima по сид фразе.

- Добавляем конекты. Заходим в Settings, Add connections, вводите ссылку https://spartacusrex.com/minimapeers.txt
- Или по команде  /peers в русском телеграмм чате
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
- 2 Проверить актуальные ли блоки на ноде.
- 3 Пробуем синхронизировать повторно через архинвый файл, повторно сид фразу вводить не нужно.
- Заходите Security - Archive reset - Chain re-sync - I have an archive file - выбираете Upload an archive file - выбирайте скаченый файл - Continue
- 4 Попробовать восстановить на другом сматфоне. более мощном и потом перенести бэкап на ваш телефон.
- [ВИДЕО. КАК ВОССТАНОВИТЬ НОДУ МИНИМА - КАК ПОДНЯТЬ ВЕРХНИЙ БЛОК | Archive reset | Chain Resync | Backup](https://www.youtube.com/watch?v=Y4V5s16ItN0) 
- [![1280](https://github.com/Webzarium/test1/assets/122037228/b74d2c9d-9840-47db-af31-fc898af0b84d)](https://www.youtube.com/watch?v=Y4V5s16ItN0 "1280")

##  Восстановление ноды minima из бэкапа
### Внимание! Если бэкап старше двух месяцев, тогда делайте синхронизацию по архивному файлу
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
- Второй вариант:  делайте полную синхронизацию  с помощью  архивного файла.
- Заходите Security - Archive reset - Chain re-sync - I have an archive file - выбираете Upload an archive file - выбирайте скаченый файл - Continue
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

## Как получить монеты Мinima за активности
- Монеты могут получить только держатели нод в тествовм периоде.
- Если вы прошли верификацию  в марте 2023 и запросили монеты, тогда у вас должна быть записана сид фраза или бэкап. Можете смело делать восстановление ноды и монеты будут у вас на кошельке.
- На решение проблем с верификацией было выделено пол года, если вы не обращались в поддержку проекта, тогда можете забыть про свои монеты minima.
- В дискорде проекта для амбасадоров проводят задания, за которые можно получить монеты minima.

## Как продать монеты Мinima
- Листинг нативной монеты MINIMA  будет в 3 квартале 2024 года
- Продать minima можно в p2p ветке дискорда прокета
- https://discord.com/channels/562272317930209280/1087641166935236638
- WTB хочу купить
- WTS хочу продать
- Очень много скамеров. Не соглашайтесь на гаранта с чужих плащадок, они могут бывть в доле. Можете поговорить с модерами и админами в дискорде по поводу гарантов.
- Второй вариант через miniswap если найдёте покупателя.
- https://www.youtube.com/watch?v=_1wUUeUrkT4

## Что делать если вы не помните пароль
- Востанавливаете ноду с нуля через сид фразу или бэкап файл и делайте синхронизацию

## Что делать если не приходят монеты на кошелёк
- Проверяете актуальную высоту блоков у того кто отправляет и тот кто получает.
- Актуальную высоту блоков можно узнать в телеграм чате в боте или в дискорд проекта.
- Не забываем делатm апрув транзакции в минидапе Pending
- Если блоки различаются, то нужно сделать синхронизацию
- При актуальной высоте блоков монеты поступают в течении 1-2 мин

## Что делать если пропали монеты с ноды которая была установлена на сервере ?
- Если вы ставили ноду на сервер с открытым портом 9005, значит вы установили ноду по не официальной инструкции и проигнорировали все предупреждения. Скорее всего ваши монеты вывели скамеры, которые сканировали порты на наличие уязвимости. 
После выявления командой MINIMA, что некоторые нерадивые люди писали инструкции с открытым портом, было выпущено оповещение о том, что необходимо закрыть этот порт у кого он открыт.
- Поэтому очень важно всегда отслеживать информацию о проекте, чтобы вовремя исправить уязвимость.
- Люди которые ставили ноду на телефон, такой проблемы не было.
- На данный момент ничем помочь нельзя в такой ситуации.
## ЗАПОМНИТЕ! Всю ответственность за сохранность своих монет несет пользователь


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


