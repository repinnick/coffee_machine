<ol>
	<li>Внес изменения согласно пункту 2.6 <br></li>

```text
Если денег недостаточно, то автомат генерирует сообщение: 
«Please deposit money. Pay attention that the coffee machine doesn’t give change» и кнопки выбора: 
«1 – 10 coins», «2 – 20 coins», «3 – 50 coins», «4 – 1 BYN», «5 –   2 BYN». (см. R 2.3, R 2.4, R 2.5)
```

<li>Внес изменения согласно пункту 2.7 <br></li>

```text
Если денег достаточно, то автомат делает выбранный вид кофе и подает его Покупателю. 
При этом на экране виден баланс Покупателя и фраза:
«Here is the best Espresso/Cappuccino/Latte in the City. Please, help yourself! » 
```

<li>Сделал ПИН. Для этого завел отдельно переменную <code>output</code> в цикле main()</li>
<li>Убрал меню <code>noCupsMenu</code>, закинул эту менюшку в главное меню, 
в main прописал дополнительное условие для 1, 2, 3, 4 пунктов.</li>
</ol>

P.S. На всякий случай проверь и потестируй. Потому что мог сделать ошибку. \
Если в голове есть более подходящая реализация, то тоже можешь писать.
