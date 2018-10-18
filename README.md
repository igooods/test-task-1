# Задание 1 — создать меню

По предоставленным макетам создать меню (react-компонент) типа аккордеон, хорошо работающий на мобильных устройствах. 

Основные требования:

1. Использовать yarn, webpack, babel(7), postcss, css-modules, react, mobx, остальное по вкусу.
1. После вызова `yarn run start-dev-server` по адресу http://localhost:8000 должно открываться меню.
1. Должно соответствовать макету, картинки не важны, можно заменить серыми квадратами.
1. Должно хорошо работать на мобильных устройствах.
1. Компонент меню должен принимать в `props` как минимум `data` и `onPressItem`. В `data` передаются данные, на основе которых происходит генерация меню. В `onPressItem` колбэк, который вызывается с объектом категории (где есть поля `id` и `name`), на которую происходило нажатие.
1. Не должно быть лишнего кода.
1. Все должно быть в едином codestyle.

Данные, на основе которых происходит генерация меню, находятся в файле DATA.js.

Макет: https://scene.zeplin.io/project/5bc83ba5c5588f18fa4f870b
