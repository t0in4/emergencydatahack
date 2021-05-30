# emergencydatahack

Trying to predict ice jam on Lena river

Несмотря на перспективность модели VARMAX 
(Vector Auto Regression Moving Average with Exogenous Variables) 
оказалось, она не подходит для прогнозирования этой ситуации
т.к. выскакивала ошибка non-positive definite matrice
из-за минусовых температур.

Также, построение модели с помощью ARIMA(Auto-regressive moving average) 
показала свою требовательность к ресурсам. Требовалось 
много дискового пространства для размещения 
массива образа

Была попытка с помощью линейной регрессии,
потом попробовали с randomforestregressor

К сожалению, результат выборки не входил в рамки предсказательной
точности, чем подтвердил несостоятельность
подборки ограниченного количества факторов.
* [csv1](https://disk.yandex.ru/d/uClWf_18qVGMJw "csv1")

* [csv2](https://disk.yandex.ru/d/BXQAPlu6KsyY6g "csv2")
 
* [csv3](https://disk.yandex.ru/d/ZExR-M3PAqvpQw "csv3")

* [csv4]( https://disk.yandex.ru/d/RmO0bA04PJMcPw "csv4")

