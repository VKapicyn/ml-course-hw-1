# ml-course-hw-1
Kaggle (house-prices-advanced-regression-techniques)

1) Данные из DataFrame приведны к числовым значениям
2) Все числовые данные приведены к числовому диапазону от 0 до 1

3) Гипотезы:  
a) признаки имеющие наибольшую корреляцию с числовым рядом цен, покажуют наилучший score  
Реузльтат: score в диапазоне от 0.4 до 0.8, в зависимости от числа признаков и числа KFold  
b) признаки имеющие наибольшую коинтеграцию с числовым рядом цен, покажуют наилучший score  
Результат: было выявлено всего 2 признака с коинтеграцией ('LotArea' и 'GrLivArea'), при KFold = 5, наилучший результат score = 0.29044  
c) чтобы улучшить результат (b), была предпринята попытка убрать 5% и 95% перцентили по цене из обучающей выборки, что могло бы улучшить score.  
Результат: показатели ухучшились до ~0.4

4) График с зависимостями кросс-валидации и результатми submition - не построил, так как эту задачу увидео в последний момент.  
Но по памяти, зависимости с score и реузльтатми rmse/mean не увидел

Ссылка на профиль kaggle
https://www.kaggle.com/vkapicyn/competitions

[![Kaggle](https://i.ibb.co/zQPGGrr/1.png)](https://www.kaggle.com/vkapicyn/competitions)
