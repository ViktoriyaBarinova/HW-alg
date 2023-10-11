# HW-alg

Результаты:
Arrays.sort(): 1363900 нс
Пузырьком: 9709100 нс
Быстрая сортировка: 547200 нс

Как видно из результатов, стандартный метод Arrays.sort() работает намного быстрее, чем реализованные мной методы bubbleSort() и quickSort(). При этом quickSort() работает быстрее, чем bubbleSort(). 
При работе с большими объемами данных (100_000 и более элементов) использование стандартного метода Arrays.sort() является наиболее оптимальным вариантом. Если же необходимо реализовать свой метод сортировки, то quickSort() будет работать быстрее, чем bubbleSort().
