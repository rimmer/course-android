﻿# Занятие 10. Фрагменты.

1. Понятие фрагментов и зачем они нужны
2. Приложение в несколькими фрагментами 
3. Транзакции фрагментов 
4. ViewPager
5. TabViewPager

## Что нужно знать
*Фрагменты* -- это переиспользуемая часть логики активити. То есть, это класс, который содержит в себе как представление, так и бизнес логику какого-то отдельной логической части приложения. Фрагменты позволяют: 

1. Разделить логику на более мелкие части и заодно лучше спроектировать архитектуру.
2. Переиспользовать фрагменты в разных местах приложения.
3. Связывать между собой фрагменты через `Activity`.

Как обычно, основной материал тут https://github.com/codepath/android_guides/wiki/Creating-and-Using-Fragments.
Про сохранение состояния фрагмента (немного теории) вот тут http://inthecheesefactory.com/blog/fragment-state-saving-best-practices/en.

### Результаты
* Уметь добавлять фрагменты *статически* и *динамически*.
* Знать, чем отличается `FragmentTransaction.hide` от `FragmentTransaction.remove`.
* Уметь коммуницировать с Activity и другими фрагментами.
* Использовать аргументы.
* *Advanced* Использовать франгмент, как хранилище временных данных приложения.


### Задание 
Пишем приложение для редактирования текстовых файлов. В приложении два фрагмента - один выводит короткие аннотации всех файлов (или отрывков, которые в базе данных), второй позволяет их редактировать и сохранять.
На больших экранах и в альбомной ориентации на экране должно присуствовать два фрагмента -- фрагмент со списком и фрагмент с редактором. На экранах телефонов в портретной ориентации на экране должен быть только список, а при нажатии на элемент списка открывается редактор в отдельном окне.





