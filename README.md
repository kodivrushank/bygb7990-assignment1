# bygb7990-assignment1
## python program code block functions explained
#### print the following statement to display to the user
```python
print('Welcome to 2 -currency calculator!')
```
#### ask the user to enter the amount and form of currency (USD or EUR)
```python
amt1 = float(input('please enter the From amount:'))
currency = input('please enter the From currency? enter "USD" or "EUR":')
```
#### use if else statement to convert the amount from one form of currency to another (USD to EUR or vice versa) using the current exchange rate
```python
if currency.upper() == 'USD':
    amt2 = amt1 * 0.86
    print(amt1, f'USD is {amt2: .2f} EUR')
else:
    amt2 = amt1 * 1.16
    print(amt1, f'EUR is {amt2: .2f} USD')
```python
