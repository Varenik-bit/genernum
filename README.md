import random

user_choice = input('Введите три цифры оператора сотовой связи: ')

random_number = '+7'
random_number += user_choice

for i in range(7):
    random_1num = random.randint(0, 9)
    random_number += str(random_1num)

print(random_number)