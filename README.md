# Описание

## Оптимизация кода с использованием паттерна Worker Pool.

default (default.go)
Time Elapsed: 110.72 seconds

with chan
Time Elapsed: 10.08 seconds

with worker (main.go)
Time Elapsed: 0.13 seconds


Прирост получаем за счёт распределения задач (генерации и записи) по потокам (worker'ам). В данном примере количество потоков совпадает с количеством пользователей.
