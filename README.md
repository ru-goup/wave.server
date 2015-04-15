in-wave.server
==============

Доброе утро!

Во славу Лулза Священного и воистину just for fun приглашаю тебя принять участие в дурацкой проделке: надо сделать facebook.

Сделать facebook - это не значит сделать ещё один <a href="http:/vk.com" target="_blank">вКонтактик</a>. Это значит обойти facebook.com в произвольном рейтинге (<a href="http://mysitecost.ru/battle/facebook.com:in-wave.com/" target="_blank">например</a>). Иначе говоря, надо сделать сайт с миллиардной аудиторией. 

В этом репозитории находится исходный код волнового сервера - веб приложения, которое обслуживает запросы по адресу http://in-wave.com 

Представь, что репозиторий - это учебное пособие для начинающих, поэтому пожалуйста, комментируй код подробно. Прототип будет  на русском языке, а к первой версии комментарии надо бы интернационализировать.
 
Соглашения о написании кода <a href="https://github.com/rwldrn/idiomatic.js/tree/master/translations/ru_RU" target="_blank">idiomatic.js</a>, описание объектной модели ты найдёшь в файле ~архитектура~, сразу же когда она будет готова.

Прежде чем  окунутся в Волну тебе надо бы согласиться с [~самым главным~](https://github.com/in-wave/wave.server/blob/master/~%D1%81%D0%B0%D0%BC%D0%BE%D0%B5%20%D0%B3%D0%BB%D0%B0%D0%B2%D0%BD%D0%BE%D0%B5~), вспомнить, что чем проще, тем лучше и не забывать, что **~in lulz we Ъ~**

Как поднять Волну у себя на локалхосту
--------------------------------------
<ol start="0">
  <li>Если у тебя Windows, то можно скачать <a href="https://drive.google.com/open?id=0B1tUuLIAHGr0flo3RUNTZkNMU2RaYXNzZl9WSGJUTF9haDhsMWJRbXpVSjFiQVlvOVRXcXM&authuser=0" target="_blank">portableApps</a>. Это не обязательно, но удобно.</li>
</ol>

1. Установить <a href="https://bitnami.com/stack/mean" target="_blank">bitnami-mean-stack</a>, затем доработать напильником: обновить нужное - <a href="https://nodejs.org/" target="_blank">node.js</a>, <a href="https://www.mongodb.org/downloads" target="_blank">mongoDB</a>, <a href="http://git-scm.com/download/" target="_blank">git</a> - и убрать ненужное.

2. Создать `{{installDir}}/apps/`. Например:  

        windows: d:\wave.server\apps  
        linux:  /opt/wave.server/apps
   
3. Склонировать туда сабжевый репозиторий  

        git clone https://github.com/in-wave/wave.server  
  
4. Установить зависимости  

        cd apps/wave.server  
        npm install  
        bower install  

5. Отредактировать файл hosts   

        127.0.0.1   in-wave.com  
        127.0.0.1   wave.server  
    
6. `...`  
7. PROFIT:  

        windows: d:\wave.server\apps\wave.server\wave.server.cmd  
        linux:  node /opt/wave.server/apps/wave.server/wave.server.js  
 
 
Если всё нормально, то по адресу <a href="http://in-wave.com" target="_blank">http://in-wave.com</a> (или  <a href="http://wave.server" target="_blank">http://wave.server</a>) можно будет увидеть концептуальную кнопку.
    
