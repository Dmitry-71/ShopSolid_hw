# Используемые принципы:

* Liskov substitution principle - наследники класса Product полностью играют роль предка;
* принцип DRY - повторяющийся вывод списка продуктов на экран выносим в отдельный метод printProucts(products);
* Single Responsibility Principle - класс Milk описывает только молоко, а не все продукты;
* В классе Phone:
   Interface Segregation Principle - применяем разные интерфейсы вместо одного большого;
   Dependency Inversion Principle - разделив интерфейсы мы не зависим от их общей функциональности, мы можем поменять один интерфейс на другой;
* В классе Apple:
   Open Closed Principle - имплементируя интерфейс Food мы добавляем классу функциональности, не изменяя его код;
