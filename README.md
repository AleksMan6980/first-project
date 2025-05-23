# Проект «Обучение с учителем: качество модели»

**Цель и задачи проекта**

Целью настоящего проекта являлась разработка решения которое позволит персонализировать предложения постоянным клиентам интернет-магазина «В один клик» для увеличения их покупательной активности.
   
   Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.

   В начале проекта после подготовки данных к исследованию производилась маркировка уровней финансовой активности постоянных покупателей: «снизилась» и «прежний уровень».

   Собирались данные по клиентам по следующим группам: 
   * признаки, которые описывают коммуникацию сотрудников компании с клиентом;
   * признаки, которые описывают продуктовое поведение покупателя;	
   * признаки, описывающие покупательское поведение клиента;
   * признаки, описывающие поведение покупателя на сайте. 

   После чего проводился корреляционный анализ признаков в количественной шкале в итоговой таблице для моделирования. Был  сделан вывод о наличии мультиколлинеарности.

   Далее применялись модели KNeighborsClassifier, DecisionTreeClassifier, LogisticRegression, SVC для предсказания вероятности снижения покупательской активности клиентов в последующие три месяца. Для каждой модели подбирался как минимум один гиперпараметр. Для установления лучшей модели осуществлялся аргументированный выбор метрики.
   
   Также была оценена важность признаков для лучшей модели и построен график важности с помощью метода SHAP. После чего были сделаны выводы о значимости признаков.
   
   При выполнении сегментации покупателей использовались результаты моделирования и данные о прибыльности покупателей.
   
   В ходе дальнейшей работы над проектом была выбрана произвольная группа покупателей для формирования ей предложений с целью увеличения покупательной способности. Для этого предварительно проводилось графическое и аналитическое исследование групп.
   
   В заключении проекта были сделаны выводы о сегментах:
   * какие сегменты были выбраны для дополнительного исследования;
   * какие предложения были сделаны покупателям и почему.
