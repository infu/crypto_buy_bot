# Програма за закупуване на крипто валута

## Как работи:

При изпълнение се свързва с борса.
Прави 1 поръчка на текущата цена.

## Инсталация:

Ако се под Windows, най-добре инсталирайте и използвайте linux терминал https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview

Инсталирайте nodejs https://nodejs.org/en/

Свалете и разархивирайте този код https://github.com/infu/crypto_buy_bot/archive/refs/heads/main.zip

Влезте в директорията през терминал и напишете ```npm install```

Променете index.js с вашата борса, ключове, двойка крипто и сума за закупуване 

```npm start``` или ```node index.js``` стартират програмата

Програмата може да се сложи в *scheduler*, примерно `crontab` и да се пуска автоматично през определен период от време

