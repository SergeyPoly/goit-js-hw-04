# HW4

**Завдання 1. Пакування товарів**

Напиши функцію isEnoughCapacity(products, containerSize), яка обчислює, чи
помістяться всі товари в контейнер при пакуванні.\
Функція оголошує два параметри:

- products — об’єкт, у якому ключі містять назви товарів, а їхні значення —
  кількість цих товарів. Наприклад, { apples: 2, grapes: 4 }.
- containerSize — число, максимальна кількість одиниць товарів, яку в себе може
  вмістити контейнер.

Функція має повернути результат перевірки, чи помістяться всі товари в
контейнер. Тобто порахувати загальну кількість товарів в об’єкті products і
повернути true, якщо вона менше або дорівнює containerSize, і false, якщо ні.

**Завдання 2. Розрахунок калорій**

Напиши функцію calcAverageCalories(days), яка повертає середньодобове значення
кількості калорій, які спортсмен споживав протягом тижня. Функція очікує один
параметр: days — масив об’єктів. Кожен об’єкт описує день тижня та кількість
калорій calories, спожитих спортсменом, у цей день.

**Завдання 3. Профіль гравця**

Об’єкт profile описує профіль користувача на ігровій платформі. У його
властивостях зберігається ім’я профілю username та кількість активних годин
playTime, проведених у грі.

Доповни об’єкт profile методами для роботи з його властивостями.

- Метод changeUsername(newName) повинен приймати рядок (нове ім’я) в параметр
  newName та змінювати значення властивості username на нове. Нічого не
  повертає.
- Метод updatePlayTime(hours) повинен приймати число (кількість годин) у
  параметр hours та збільшити на нього значення властивості playTime. Нічого не
  повертає.
- Метод getInfo() має повертати рядок формату _Username_ has _amount_ active
  hours!, де _Username_ — це ім’я профілю, а _amount_ — кількість ігрових годин.
