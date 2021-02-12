import json
print("Выберете продукт:")
price = dict()
price["Tomato"] = 100
price["Cabbage"] = 10
price["Eggplant"] = 200
price["Cucumber"] = 95
price["Avocado"] = 500
price["Carrot"] = 120
price["Pumpkin"] = 100
price["Squash"] = 150
price["Mushroom"] = 100
price["Parsley"] = 10
print(price)
a = input()
val=0
d = price.get(a,val)
print(price.get(a))
while d == 0:
    print("Такого продукта не существует, попробуйте еще раз")
    a = input()
    d = 1
    d = price.get(a, val)
print("Сколько кг ")
kg = int(input())
print(kg*price[a])
print("Вы можете изменить цену за товар, введите строку написанную выше изменив цену, заменив ' на двойнные ковычки")
new_price = input()
price = json.loads(new_price)
print("Выберете продукт:")
print(price)
a = input()
print("Сколько кг ")
kg = int(input())
print(kg*price[a])
