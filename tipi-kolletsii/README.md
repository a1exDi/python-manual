# Типы коллекций

> Если вы нашли ошибку, неточность в описании, опечатку или у вас есть чем дополнить описание, вы можете отправить мне письмо на email: alexsey.shirkin@gmail.com или написать в Telegram - [https://telegram.me/a1exDi](https://telegram.me/a1exDi)

### Какой тип коллекций выбрать для данных?

{% tabs %}
{% tab title="IN" %}
```python
import sys

x = [1,2,3,4,5,6]
y = (1,2,3,4,5,6)
z = {1,2,3,4,5,6}

print(sys.getsizeof(x))
print(sys.getsizeof(y))
print(sys.getsizeof(z))
```
{% endtab %}

{% tab title="OUT" %}
```
152
88
472
```
{% endtab %}
{% endtabs %}

