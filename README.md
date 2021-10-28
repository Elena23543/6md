# 6md

PI = 3.14
R = int (input("Введите радиус круга: "))
L = 2 * PI * R
print("Длина окружности:",L)
S = PI * R ** 2
print("Площадь:",S)




a = int(input("Введите двузначное число: "))
print("Сумма его цифр:",a % 50 + a // 50)
print("Произведение его цифр:", (a % 50) * (a // 50))
print("Результат перестановки цифр:", a % 50 * 50 + a// 50)



a, b, c = int(input())
if(a < b < c) or (c < b < a):
    print("верно")
else:
    print("неверно")
    
    
    
a, b = int(input())
if a < b:
    print("1")
elif a > b:
    print("2")
