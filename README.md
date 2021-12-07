Требования к структуре кода:
-	У каждого животного должен быть свой класс
-	Все животные должны восходить по иерархии к классу или интерфейсу Животное
-	У животного должны быть кличка и дата рождения. Эти значения должны задаваться при создании объекта и нужно, чтобы их было невозможно изменить после этого. Нужно, чтобы их можно было получить через getter-методы
-	В классе животного должны быть определены константы (static final), описывающие общие свойства животных этого класса класса (в какой среде живет, тип питания травоядное/мясоядное/всеядное животное, максимальный вес, сколько нужно площади для обитания). Эти свойства должны быть доступны для получения другими классами.
-	Пользователь класса должен иметь возможность накормить животное. Для этого, животные должны иметь метод "кушать", принимающий значение "трава", "мясо". Если животному дают тип пищи, который оно ест, то в консль нужно вывести "Я буду есть ...", иначе вывести "Я не буду есть..."
-	Нужно избежать дублирования свойств/действий животных, используя наследование    
-	Использовать java collections
-	Где имеет смысл, использовать ENUM
-	Предпочтительно использовать функции java 8
Список животных:
      - Рысь - живет на земле, ест мясо, вес до 30 кг, нужно 200 кв.м. для обитания
      - Енот - живет на земле, ест мясо, вес до 9 кг, нужно 50 кв.м. для обитания
      - Кенгуру - живет на земле, ест растения, вес до 85 кг, нужно 300 кв.м. для обитания
      - Орел - летающее животное, ест мясо, вес до 7 кг, нужно 100 кв.м. для обитания
      - Страус - живет на земле, ест растения, вес до 140 кг, нужно 150 кв.м. для обитания
      - Карп - живет в воде, ест водоросли и насекомых, вес до 4 кг, нужно 8 кв.м. для обитания
      - Тарань - живет в воде, ест моллюсков и ракообразных, вес до 2 кг, нужно 5 кв.м. для обитания

Требования к расчетам:
      - 1. Нужно создать список, в котором будет храниться по одному экземпляру каждого из животных.         
      - Пройдясь по списку животных, нужно:
            - вывести на консоль все свойства каждого из животных. То есть, для каждого конкретного животного выводим его имя и дату рождения, и общие свойства животных этого класса
            - вызвать метод животного "кушать" для каждого животного два раза (один раз со строкой "трава", другой - со строкой "мясо") 
      - 2. Рассчитать минимальное необходимое место (кв.м.) нужное в зоопарке, если в нем живут 5 рысей, 4 енота, 2 кенгуру, 7 орлов, 3 страуса, 15 карпов и 7 тараней. Результат вывести на консоль
Оба пункта расчетов должны быть реализованы в отдельных методах и вызываться из метода main
Опционально:
- Рассчитать грузоподъемность автомобиля, который должен будет перевозить всех сухопутных животных. То же самое для летающих животных. То же самое для плавающих животных. Результаты вывести на консоль