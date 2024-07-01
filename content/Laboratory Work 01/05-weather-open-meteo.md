---
title: "Exercise 05 - Wheather - open-meteo.com"
date: 2024-07-01T16:00:15Z
draft: false
weight: 30

scripts:
    - /js/01/exercise-05-wheather-open-meteo.js
---

## Exercise 05 - Wheather - open-meteo.com

* Формулировка задачи
* Моё описание задачи
* Почему
* [Ссылка на скрипт](/js/01/exercise-05-weather-open-meteo.js)

---
    <h3>Поиск погоды по городам</h3>
    <br>
    <input type="text" id="city-input" placeholder="Введите город на английском языке">
    <br>
    <button class="button button-success" onclick="loadWeather()">Получить погоду</button>
    <br>
    <div id="weather" class="panel panel-notice" style="display: none"></div>

---