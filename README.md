[comment]: <> (<h3 style="text-align: center">Приложение можно просмотреть по ссылке указанной ниже</h3>)

[comment]: <> (<h1 style="text-align: center">http://millionaire-game.xyz</h1>)
<ul>
<h3 style="text-align: center">Для запуска перейдите в папку guestBook</h3>
<li>
npm install -- установить зависимости в корневой папке
</li>
<li>
npm run client:install -- установить зависимости на клиенте
</li>
<li>
npm run server:install -- установить зависимости на сервере
</li>
<li>
npm run dev -- запускает приложение
</li>
</ul>

<ul>
<h3>В разработке приложения использовал:</h3>
<li>На клиенте - библиотеку React, Axios для асинхронных запросов и Materialize для вёрстки</li>
<li>На сервере - Node.js, Express фреймворк и пакет express-validator для валидации на стороне сервера, библиотеку Mongoose для работы с MongoDB. Для кроссбраузерности ENV использовал паке cross-env, для авто-обновления сервера использовал пакет nodemon </li>
<li>Для более удобного вызова написал скрипты вызова и запустил клиен и сервер с помощью пакета concurrently</li>
</ul>

<ul>
<h3>Описание приложения и о проделанной работы:</h3>
<li>Приложение "Гостевая книга" - состоит из формы в которой есть поле с "Именем", поле textarea для тела сообщения и кнопка для отправки сообщения(комментария)</li>
<li>Ниже поле вывода комментариев. Коммунтарии выводяться из базы данных MongoDB, отсортированны - сверху новые сообщения</li>
<li>Форма отправки сообщения имееет написанную валидацию на стороне клиента и немного на стороне сервера(по мере надобности). RegExp - регулярные выражения(разрешено: латинские буквы, цифры, знак нижнего подчеркивания). Комментарии добавляються и отображаються без перезагрузки страницы. На выполнение работы было потрачено около 14 часов. Добавлена адаптация под мобильные устройства. Отображаеться в Tooltips ответ сервера при добавлении нового комментария</li>
</ul>
