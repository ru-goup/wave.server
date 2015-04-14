in-wave.server
==============

Доброе утро!

Во славу Лулза Священного и воистину just for fun приглашаю тебя принять участие в дурацкой проделке: надо сделать facebook.

Сделать facebook - это не значит сделать ещё один [вКонтактик](http:/vk.com). Это значит обойти facebook.com в произвольном рейтинге. Например, на сайте [mysitecost.com](http://mysitecost.ru/battle/facebook.com:in-wave.com/). Или, иначе говоря, сделать сайт с миллиардной аудиторией. В срок до февраля 2020 года, поэтому времени пока достаточно.

Это репозиторий прототипа Волны (http://in-wave.com) - проекта децентрализованного веба, написанного на javascript. Представь, что репозиторий - это учебное пособие для начинающих, поэтому пожалуйста, комментируй код подробно. Прототип будет у нас на русском языке, а в первой версии комментарии надо интернационализировать.
 
Соглашения о написании кода [idiomatic.js](https://github.com/rwldrn/idiomatic.js/tree/master/translations/ru_RU), описание объектной модели ты найдёшь в файле ~АРХИТЕКТУРА~ (когда она будет готова).

Но прежде всего тебе надо согласиться с [~самым главным~](https://github.com/in-wave/wave.server), запомнить, что чем проще, тем лучше и вообще: **~in lulz we Ъ~**

Установка
--------

1. Установить [bitnami-mean-stack](https://bitnami.com/stack/mean) 
2. Создать {installation directory}/apps/ 

  **Например windows**:  
    D:\bitnami\meanstack-2.6.7-0\apps   
  **Например  linux**:  
    /opt/bitnami/meanstack-2.6.7-0/apps
   
3. Склонировать сабжевый репозиторий в каталог *apps*  

    git clone https://github.com/in-wave/wave.server  
  
4. Установить зависимости  

    cd apps/wave.server  
    npm install  
    bower install  
    
5. Отредактировать файл hosts   

    127.0.0.1   in-wave.com  
    127.0.0.1   wave.server  
    
6. ... 
7. PROFIT:  
    **windows** d:\bitnami\meanstack-2.6.7-0\apps\wave.server\wave-server.cmd  
    **linux**  node wave-server.js  
    
Ели всё нормально, то по адресу <http://in-wave.com> или <http://wave.server> можно будет увидеть концептуальную кнопку.
    