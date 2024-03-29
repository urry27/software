**Паттерны проектирования**<br>
**Design Patterns**

# Пораждающие
Связанные с процессом создания объектов

## Класс
- Фабричный метод (Factory Method). Определяет общий интерфейс для создания объектов в суперклассе, позволяя подклассам изменять тип создаваемых объектов.

## Объект
- Абстрактная фабрика (Abstract Factory). Позволяет создавать семейства связанных объектов, не привязываясь к конкретным классам создаваемых объектов.
- Одиночка (Singleton). Гарантирует, что у класса есть только один
экземпляр, и предоставляет к нему глобальную точку доступа.
- Прототип (Prototype). Позволяет копировать объекты, не вдаваясь в
подробности их реализации.
- Строитель (Builder). Позволяет создавать сложные объекты пошагово.
Строитель даёт возможность использовать один и тот же код строительства для получения разных представлений объектов.

# Структурные
Связанные с композицией объектов и классов

## Класс
- Адаптер (Adapter). Позволяет объектам с несовместимыми
интерфейсами работать вместе.

## Объект
- Адаптер (Adapter). Позволяет объектам с несовместимыми
интерфейсами работать вместе.
- Декоратор (Decorator). Позволяет динамически добавлять объектам новую
функциональность, оборачивая их в полезные «обёртки»
- Заместитель (Proxy). Позволяет подставлять вместо реальных объектов
специальные объекты-заменители. Эти объекты перехватывают вызовы к оригинальному объекту, позволяя сделать что-то до или после передачи вызова оригиналу.

- Компоновщик (Composite). Позволяет сгруппировать множество объектов в
древовидную структуру, а затем работать с ней так, как будто это единичный объект
- Мост (Bridge). Разделяет один или несколько классов на две отдельные
иерархии — абстракцию и реализацию, позволяя изменять их независимо друг от друга.
- Приспособленец (Flyweight). Позволяет вместить бóльшее количество объектов
в отведённую оперативную память. Легковес экономит память, разделяя общее состояние объектов между собой, вместо хранения одинаковых данных в каждом объекте.
- Фасад (Facade). Предоставляет простой интерфейс к сложной системе
классов, библиотеке или фреймворку.

# Поведения
Как классы или объекты взаимодействуют

## Класс
- Интерпретатор (Interpreter).
- Шаблонный метод (Template Method). Определяет скелет алгоритма, перекладывая ответственность за некоторые его шаги на подклассы. Паттерн позволяет подклассам переопределять шаги алгоритма, не меняя его общей структуры

## Объект
- Итератор (Iterator). Даёт возможность последовательно обходить элементы составных объектов, не раскрывая их внутреннего представления.
- Команда (Command). Превращает запросы в объекты, позволяя передавать их как аргументы при вызове методов, ставить запросы в очередь, логировать их, а также поддерживать отмену операций
- Наблюдатель (Observer). Создаёт механизм подписки, позволяющий одним объектам следить и реагировать на события, происходящие в других объектах
- Посетитель (Visitor). Позволяет добавлять в программу новые операции, не изменяя классы объектов, над которыми эти операции могут выполняться.
- Посредник (Mediator).Позволяет уменьшить связанность множества классов между собой, благодаря перемещению этих связей в один класс-посредник.
- Состояние (State). Позволяет объектам менять поведение в зависимости от своего состояния. Извне создаётся впечатление, что изменился класс объекта.
- Стратегия (Strategy). Определяет семейство схожих алгоритмов и помещает каждый из них в собственный класс, после чего алгоритмы можно взаимозаменять прямо во время исполнения программы.
- Хранитель (Memento). Позволяет сохранять и восстанавливать прошлые состояния объектов, не раскрывая подробностей их реализации.
- Цепочка обязанностей (Chain of Responsibility). Позволяет передавать запросы
последовательно по цепочке обработчиков. Каждый последующий обработчик решает, может ли он обработать запрос сам и стоит ли передавать запрос дальше по цепи.