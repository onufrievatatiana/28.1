# 28.1
Итоговый проект по автоматизации тестирования
Тестировщик Татьяна Онуфриева QAP 1034
Тестирование нового интерфейса авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии. 
→ Объект тестирования: https://b2c.passport.rt.ru

Тест-кейсы и Баг-репорт доступны по ссылке https://docs.google.com/spreadsheets/d/1Apt-dGdexj2qutfu1QAyaHD3j6UjFTK-sy8WokfUtiE/edit?usp=sharing
В работе были использованы ручные и автоматизированные тесты.
Применялись Smoke testing, разбиеение на классы эквивалентности, проводились положительные и отрицательные тесты.

Клонировать репозиторий
Установить pytest-selenium >>> pip install pytest-selenium
В Python Interpreter добавляем pytest-selenium
Запустить тесты через консоль >>> pytest
Запускаем тесты с помощью:
python -m pytest -v --driver Chrome --driver-path /path/to//chromedriver test_selenium_passport
/path/to/ -  путь к драйверу браузера Chrome
