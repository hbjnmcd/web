---
title: Лабораторная работа 1
subtitle: Задание 1
comments: false
scripts:
    - /js/01.js
---

# Exercise 01 - Погода
* Необходимо создать приложение, которое отображает погоду в городе (а также температуру и влажность)
* После ввода города при нажатии на кнопку реализуется обращение к сайту **https://wttr.in**
* [Ссылка на скрипт](/js/01.js)


<h3>Поиск погоды по городам</h3>
<br>
<input type="text" id="city-input" placeholder="Введите город">
<br>
<button class="button button-success" onclick="loadWeather()">Получить погоду</button>
<br>
<div id="weather" class="panel panel-notice" style="display: none"></div>

