# test-2-technology_company
В рамках тестового задания №2, я провела анализ двух баз: клиентов и сделок технологической компании. Были рассмотрены следующие вопросы:

  1. Проведите анализ клиентов и классифицируйте их по следующим признакам: пол, возраст, семейное положение, наличие детей. Проиллюстрировать на графике сколько клиентов у вас принадлежит к каждой группе, какое процентное соотношение, каких клиентов у вас больше всего в базе. Сделайте выводы и проиллюстрируйте на диаграмме.
  2. Проанализируйте какой процент клиентов из базы уже делали покупки, а какие клиенты еще являются потенциальными. Сделайте выводы и проиллюстрируйте на диаграмме.
  3. Проанализируйте какие продукты наиболее пользуются наибольшей популярностью у клиентов? 
  4. Какие продукты приносят самую большую прибыль компании?
  5. В каких магазинах совершаются наибольшее количество сделок? В каких магазинах совершаются самые крупные сделки?
  6. Посчитайте размер среднего чека для всей компании в целом и отдельно для каждого магазина (год). Средний чек = Общая выручка за период /Количество сделок за период
  7. Какие клиенты покупают наиболее часто? 
  8. Рассчитать следущие показатели для текущей базы клиентов:
Churn (отток) - показатель ушедших из компании клиентов и связанных с ними доходов и обычно выражается в процентном или денежном отношении.\
Customer churn % = количество клиентов, которые вы потеряли за указанный месяц, деленное на количество клиентов, которые у вас были в конце прошлого месяца.\
MRR churn % = доход, потерянный из-за оттока клиентов и их переходов на более дешевые тарифные планы, в указанном месяце, деленная на доход, который вы имели в конце прошлого месяца.\
Коэффициент удержания = (количество клиентов на конец периода – количество новых клиентов)/количество клиентов на начало периода.
  9. Используя данные в столбце «Обратная связь» рассчитайте Индекс Чистой Поддержки (Net Promoter Score).\
Согласно данной концепции в зависимости от поставленной оценки клиенты классифицируются на три группы:\
Промоутеры. Люди, которые ставят оценку 9 или 10 баллов, ведут себя как лояльные клиенты.\
Пассивные. Люди, которые ставят оценку 8 или 7 баллов, считают, что получили то, за что заплатили и не более. Пассивно удовлетворенные клиенты, их нельзя назвать лояльными, редко рекомендуют компанию, делают это с оговоркой и без энтузиазма, могут уйти к конкурентам.\
Детракторы. Люди, которые ставят оценку 6 и менее. Взаимодействие с компанией им не понравилось, они не удовлетворены, не довольны. Не рекомендуют компанию, а наоборот ухудшают ее рейтинг.\
Индекс Чистой Поддержки (Net Promoter Score) = % клиентов-промоутеров минус % клиентов детракторов. 

В рамках задания использовала библиотеки pandas, matplotlib.pyplot, seaborn, plotly.express, numpy. Были получены ответы на  Ad-Hoc запросы, построены диаграммы для анализа клиентуры, рассчитан показатель NPS, а также проведен когортный анализ (Customer churn, MRR churn, retention rate).
