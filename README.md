# домашка
input_str = input("Введите список чисел разделенных пробелом: ")
numbers = list(map(int, input_str.split()))
even_numbers = [num for num in numbers if num % 2 == 0]
odd_numbers = [num for num in numbers if num % 2 != 0]
max_number = max(numbers)
min_number = min(numbers)
sum_numbers = sum(numbers)
#я устал я хочу спать
print("Четные числа:", even_numbers)
print("Нечетные числа:", odd_numbers)
print("Максимальное число:", max_number)
print("Минимальное число:", min_number)
print("Сумма всех чисел:", sum_numbers)
#у меня болит спина я как рак сижу 2 часа






# 2 домашка я не знаю как сделать другую ссылку у меня ошибка выходит
number = int(input("Введите число: "))
print(f"Таблица умножения для числа {number}:")

for i in range(1, 11):
    result = number * i
    print(f"{number} x {i} = {result}")
#пожайлуста не задавайте такие сложные дз я не успеваю и не понимаю я хочу спать я очень сильно устал
#эти 2 кода для меня очень сложные пожайлуста хватит
