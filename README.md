1. Открываем браузер Google Chrome 
   -> Настройки и управления Google Chrome 
     -> Дополнительные Инструменты 
       -> Инструменты Разработчика
2. Переходим в на страницу https://vk.com/friends?act=find
3. Копируем скрипт без ковычек и вставляем в поле для ввода скрипта
  "javascript:var interval = setTimeout(function () {
    var time_limit = 2500;
    var tm = 0;
    for (var i = 0; i < 40; i++) {
        setTimeout('document.getElementsByClassName("friends_find_user_add")['+i+'].click()', tm);
        tm += time_limit;
    }
});"
4. Нажимаем Enter
