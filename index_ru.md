# RCoin
**[Аирдроп: ПОЛУЧИ 25 XRX БЕСПЛАТНО](/airdrop_ru)**

**НА БЛОКЕ 40,000 СЛУЧИТСЯ ХАРД ФОРК; ПОЖАЛУЙСТА ОБНОВИТЕ ФАЙЛ “coin.conf” ИЛИ TkWallet.**

RCoin - децентрализованная пиринговая валюта , строящаяся на идеях Bitcoin. Последняя версия RCoinX - это крипто валюта на основе протокола CryptoNote, которую, я уверен, вы сочтете очень удобной и будете использовать с большим удовольствием. RCoin требует относительно большого объема памяти на хэш, что обеспечивает ее устойчивость к ASIC.

**Новости: Система анонимных сообщений в программе TkWallet3X завершена! E-Mail подобное общение, но уже на блокчейне!**

**Новости: Мы обновились до TkWallet3X и добавили поддержку легковесных кошельков (типа Electrum)**

**Новости: У нас есть IRC чат: ##ronsor на irc.freenode.net - [Веб-Чат](http://kiwiirc.com/client/irc.freenode.net/##ronsor) или Discord: [Добавить](https://discord.gg/UVcjJBb)**

## Актуальная Версия

Текущая версия RCoinX 1.1.

## Особенности и Информация

* RCoin использует алгоритм CryptoNight.
* Время блока 10 секунд.
* Доступен соло-майнинг.
* Система анонимных сообщений.

### Система анонимных сообщений

Система анонимных сообщений позволяет с помощью TkWallet пересылать анонимные сообщения любому пользователю. Получатель не сможет узнать кто отправил сообщение, чтобы идентифицировать себя нужно будет найти иной способ (если это понадобится). Стоимость отправки анонимного сообщения равна комиссии сети (примерно 0.0001 RCoin).

## Как получить кошелек

Кошелек RCoin можно загрузить по ссылкам ниже:

* Исходный код: смотри ниже
* В обычную загрузку уже включен легковесный кошелек.
* [Кошелек для Windows 64-bit](https://rcoin.surge.sh/wallet3x-win64.zip) \*(читай дополнение)
* [Кошелек для Линукс](https://rcoin.surge.sh/wallet3x-linux64.tgz)

Дополнение: Мы переключились на TkWallet3x. Кошельки от TkWallet2x импортировать невозможно -- все средства нужно перевести в новый кошелек.
TkWallet3X совместим с командной строкой кошельков типа simplewallet. TkWallet3X может быть запущен совместно с TkWallet2X. Нужно восстановить средства с TkWallet2X? Скачайте последнюю версию TkWallet2X [здесь](https://rcoin.surge.sh/wallet-win64.zip). Анонимные сообщения TkWallet2X несовместимы с новыми в TkWallet3x .

Можно использовать стандартный клиент [Forknote](http://forknote.net), для чего вам понадобится файл настроек RCoin : [coin.conf](https://github.com/tinyrcoin/tkwallet/raw/master/coin.conf).

### Исходный Код

RCoin на данный момент базируется на Forknote. Вы можете получить одобренную нами копию исходного древа [здесь](http://github.com/tinyrcoin/forknote). Скомпилировав эти данные вы получите кошелек с командной строкой и демона. Вам понадобится файл настроек RCoin "coin.conf", который доступен в [Репозиторий TkWallet3X](https://github.com/tinyrcoin/tkwallet).

Если нужен GUI-кошелек (скорее всего), загляните в репозиторий TkWallet3X -- ссылка указана выше.

## Block Explorer

[RCoinX Block Explorer](http://explorer.yt/)

## FAQ

1. Что со старым RCoin?
   > Старый RCoin имел различные проблемы, начиная от полной неработоспособности до чрезмерной инфляции.
   
2. Что такое TkWallet?
   > TkWallet (и его актуальная версия, TkWallet3X) это - GUI-кошелек для RCoin.
   
3. Как майнить?
   > Если вы используете TkWallet, можно начать майнить, перейдя в меню "Mining" и выбрав "Launch Miner", что запустит майнинг для текущего адреса.
   > Если хотите майнить на другой адрес, получить больше настроек, или не используя TkWallet, можете запустить майнер вручную:
   `./miner --address (адрес) --threads (количество потоков/CPU ядер для использования) --log-level 4 --daemon-rpc-port 12991` или посмотрите `./miner --help` для всех команд.
   > Также смотрите *Пулы*
4. Как насчет GPU майнера?
   > На ранней стадии RCoinX, GPU майнер увеличит сложность и сделает сложной добычу с помощью CPU. Стартовать GPU майнинг на раннем этапе никому не выгодно.
   > К сожалению, сейчас уже слишком поздно. 
   
5. ASIC майнинг?
   > А Вы первое предложение читали вообще!?!
   
### FAQ: Какие пулы доступны?

Доступен 1 пул:
**Активен**
* [POOL.YT](http://pool.yt)

## Дорожная карта

```
[x] Выпуск RCoinX 1.0 *Готово*
[-] Выбраться как минимум на 1 биржу. *в процессе*
[x] Доделать block explorer. *сделал @Kraken в Discord*
[x] Добавить поддержку легковесных кошельков (типа Electrum для Bitcoin) *Готово*
[x] Улучшить систему анонимных сообщений *Готово*
[ ] Создать Веб-кошелек
[ ] Добавить поддержку токенов
```
