
Результат будет: `match:123 4`.

Первый, ленивый шаблон, `pattern:\d+?` попытается получить как можно меньше цифр до первого пробела, поэтому совпадением будет `match:123`.

Тогда второй `\d+?` возьмёт только одну цифру, потому что этого будет достаточно.