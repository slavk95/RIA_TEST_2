# RIA_TEST_2
Написати функцію f2(), на вхід якій передається строка виду 'foo.bar=51ec288910b27bb92b9067a409fc1425', для заданої строки функція має вертати об'єкт {"foo":{"bar":"51ec288910b27bb92b9067a409fc1425"}}.
Загальні правила перетворення строки в об'єкт наступні:
* Строка складається з ключа та значення які розділені знаком "="
* Значення може бути взято в подвійні лапки, наприклад hello = "World". 
При цьому самі лапки в які взято значення потрібно ігнорувати в об'єкті що повертається, для даного випадку функція має повертати об'єкт:
{"hello":"World"}
* Ключ може бути поділений символом "." на секцій, які визаначають вкладеність об'єктів, наприклад this.is.my.first.app=12. В даному випадку є 5 вкладених об'єктів: {"this":{"is":{"my":{"first":{"app":"12"}}}}}
* Вкладеності може не бути зовсім