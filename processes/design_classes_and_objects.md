**Спроектировать классы и объекты** <br>
**Design classes and objects**

# Принципы проектирования классов и объектов

- Инкапсулируйте то, что меняется. Определите аспекты программы, класса или метода, которые меняются чаще всего, и отделите их от того, что остаётся постоянным.
- Программируйте на уровне интерфейса. Программируйте на уровне интерфейса, а не на
уровне реализации. Код должен зависеть от абстракций, а не конкретных классов.
- Предпочитайте композицию наследованию.
- Принципы SOLID.
  - Принцип единственной ответственности (Single Responsibility Principle). У класса должен быть только один мотив для изменения.
  - Принцип открытости/закрытости (Open/Closed Principle). Расширяйте классы, но не изменяйте их первоначальный код
  - Принцип подстановки Лисков (Liskov Substitution Principle). Подклассы должны дополнять, а не замещать поведение базового класса.
  - Принцип разделения интерфейса (Interface Segregation Principle). Клиенты не должны зависеть от методов, которые они не используют.
  - Принцип инверсии зависимостей (Dependency Inversion Principle). Классы верхних уровней не должны зависеть от классов нижних уровней. Оба должны зависеть от абстракций. Абстракции не должны зависеть от деталей. Детали должны зависеть от абстракций.

# Паттерны проектирования

Используйте [паттерны проектирования](/words/design_patterns.md).