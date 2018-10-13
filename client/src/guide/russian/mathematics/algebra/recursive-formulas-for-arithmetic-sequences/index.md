---
title: Recursive Formulas for Arithmetic Sequences
localeTitle: Рекурсивные формулы для арифметических последовательностей
---
## Рекурсивные формулы для арифметических последовательностей

### Что такое арифметическая последовательность?

**Последовательность** - это список чисел, где одна и та же операция (ы) выполняется с одним номером, чтобы получить следующий. **Арифметические последовательности** в частности, ссылаются на последовательности, созданные путем добавления или вычитания значения, называемого **общей разницей,** для получения следующего термина. В чтобы эффективно говорить о последовательности, мы используем формулу, которая строит последовательность, когда вводится список индексов. Обычно этим формулам даются однобуквенные имена, за которыми следует параметр в круглых скобках, а выражение, которое строит последовательность с правой стороны.

`a(n) = n + 1`

Выше приведен пример формулы для арифметической последовательности.

### Примеры

Последовательность | формула --------- | --------- 1, 2, 3, 4, ... | a (n) = n + 1 3, 8, 13, 18, ... | b (n) = 5n-2

### Рекурсивная формула

Примечание. Математики начинают отсчет в 1, поэтому по соглашению `n=1` является первым членом. Поэтому мы должны определить, что такое первый термин. Тогда мы имеем выяснить и включить общую разницу. Еще раз взглянув на примеры,

Последовательность | Формула | Рекурсивная формула --------- | --------- | ------------------- 1, 2, 3, 4, ... | a (n) = n + 1 | a (n) = a (n-1) + 1, a (1) = 1 3, 8, 13, 18, ... | b (n) = 5n - 2 | b (n) = b (n-1) + 5, b (1) = 3

### Нахождение формулы (учитывая последовательность с первым членом)
```
1. Figure out the common difference 
    Pick a term in the sequence and subtract the term that comes before it. 
 2. Construct the formula 
    The formula has the form: `a(n) = a(n-1) + [common difference], a(1) = [first term]` 
```

### Найти Формулу (учитывая последовательность без первого члена)
```
1. Figure out the common difference 
    Pick a term in the sequence and subtract the term that comes before it. 
 2. Find the first term 
    i. Pick a term in the sequence, call it `k` and call its index `h` 
    ii. first term = k - (h-1)*(common difference) 
 3. Construct the formula 
    The formula has the form: `a(n) = a(n-1) + [common difference], a(1) = [first term]` 
```

#### Дополнительная информация:

Для получения дополнительной информации по этой теме посетите

*   [Википедия](https://en.wikipedia.org/wiki/Arithmetic_progression)
*   [Ханская академия](https://www.khanacademy.org/math/algebra/sequences/constructing-arithmetic-sequences/a/writing-recursive-formulas-for-arithmetic-sequences)