# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил:
- Безбородов Вениамин Васильевич
- РИ-210940
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.


## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1
###Вывод Hello World на python и Unity
![Screenshot_3](https://user-images.githubusercontent.com/49115035/192161460-8e35164d-62c8-4e64-99e5-0f0fcef79141.png)
![Screenshot_1](https://user-images.githubusercontent.com/49115035/192161463-d7ac842a-20f2-42b6-ab0c-c88cebf52f80.png)
![Screenshot_2](https://user-images.githubusercontent.com/49115035/192161464-2196a84c-3e5f-456d-bef2-6268893ab6b1.png)



## Задание 2

### Выполнение раздела ход работы

Ссылка на ipynb [файл](https://github.com/VenchasS/DA-in-GameDev-lab1/blob/main/lab1.ipynb) из Jupyter notebook
Prediction с кол-вом итераций увеличивает свою точность.
![Screenshot_4](https://user-images.githubusercontent.com/49115035/192161567-5b4e01e2-2d1f-43e9-9c73-751a77d81b19.png)
![Screenshot_5](https://user-images.githubusercontent.com/49115035/192161572-0a69bc3f-7e3f-4b77-9eb6-5dc9adf7aeda.png)
![Screenshot_6](https://user-images.githubusercontent.com/49115035/192161573-016cf493-5d49-421d-9ff6-043a08380b92.png)
![Screenshot_7](https://user-images.githubusercontent.com/49115035/192161575-2c48e03c-5a95-4d0f-9d16-0f9f72fba9b5.png)
![Screenshot_8](https://user-images.githubusercontent.com/49115035/192161576-f46a38ac-b943-4593-96b8-b5d99d7f058d.png)



## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
При изменинии весов a,b с большим кол-вом итераций loss , который является разницей между предсказанным значениеми реальным, будет убывать потому что предсказанное значение будет все ближе подбираться к реальному.
Пример сравнение loss для 10000 и 1000000 итераций, где loss убывает:
![Screenshot_9](https://user-images.githubusercontent.com/49115035/192164560-3248e3e0-20ae-434c-8b82-5e5b1533f7db.png)

### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.

Lr является скоростью и точностю обучения и если оно слишком велико то мы можем пропустить оптимальные веса, однако для этого нам понадобится меньше итераций обучения.
пример для ```Lr = 0.000100 ``` , где всего после 5 итераций мы уже имеем loss 182
![image](https://user-images.githubusercontent.com/49115035/192165225-25520d04-aa6e-433f-8dda-b32486554976.png)


## Выводы
Нужно уметь балансировать кол-вом итераций и Lr параметром для достижения наиболее оптимального анализа данных.


