# Коды мини-программ
1

print("Имя: Зияудин")

print("Почта: ziyaudink2005@mail.ru")


2

name=input("Введите имя:")

print("Привет", name + "!" )



3

import math

a=float(input("Введите длину:"))

b=float(input("Введите ширину:"))

S=(a*b)

print("Площадь:", S, "метров")



4

import math

a=float(input("Введите длину в футах:"))

b=float(input("Введите ширину в футах:"))

S=float((a*b)*2.2956841138665E-5)

print("Площадь %.10f акров." % S)



5

a=float(input("Введите количество бутылок объемом 1 литр или меньше:"))

b=float(input("Введите количество бутылок большего объема:"))

a1=(a*0.10)

b1=(b*0.25)

c=(a1+b1)

print("Сумма выручки: %.2f $" % c)

6

import math

summa=float(input("Введите сумму заказа:"))

a=((summa/100)*15)

b=(summa-a)

c=((b/100)*18)

d=(a+c)

print("Налог: %.2f" %a)

print("Чаевые: %.2f" %c)

print("Итог: %.2f" %d)



7

import math

n=float(input("Введите число:"))

summa=((n)*(n+1))/2

print("Сумма положительных натуральных чисел:", summa)


8

import math

a=float(input("Введите количество сувенир:"))

b=float(input("Введите количество безделушек:"))

a1=(a*75)

b1=(b*112)

c=a1+b1

print("Вес сувениров:", a1)

print("Вес безделушек:", b1)

print("Общий вес:", c)  


9

import math

a=float(input("Введите счет в банке:"))

prosent=(a/100)*4

year1=(a+prosent)

year2=(year1+prosent)

year3=(year2+prosent)

print("Сумма на счету после первого года: %.2f" %year1)

print("Сумма на счету после второго года: %.2f" %year2)

print("Сумма на счету после третьего года: %.2f" %year3)



10

import math

a=float(input("Введите первое целое число:"))

b=float(input("Введите второе целое число:"))

c=(a+b)

d=(a-b)

e=(a*b)

f=(a/b)

g=(a%b)

h=math.log10(a)

i=(a**b)

print("Сумма:", c)

print("Разность:", d)

print("Произведение:", e)

print("Частное:", f)

print("Остаток от частного:", g)

print("Log10", h)

print("Результат взведения числа a d степень b:", i)


11

toplivo=float(input("Введите показатель потребления:")) 

l=(235.22/toplivo)

print("Итог",l,"Л/100")




12

a1=float(input("Введите широту 1:"))

b1=float(input("Введите долготу 1:")) 

a2=float(input("Введите широту 2:")) 

b2=float(input("Введите долготу 2:")) 

import math

distanse=round(6371.01*math.acos(math.sin(a1)*math.sin(a2)+math.cos(a1)*math.cos(a2)*math.cos(b1-b2)),2)

print("Расстояние между точками в градусах", distanse)

distanse2=round(math.radians(distanse))

print("Расстояние между точками в радианах", distanse2)





13

a=float(input("Введите рост в футах:"))

b=float(input("Введите рост в дюймах:"))

v=(a*12+b)*2.54

print("Ваш рост", v ,"см")




14

import math

a=float(input("Введите расстояние в футах:"))

b=a*12

c=float(a*3.0)

d=round(a/5.280)

print("В дюймах:", b)

print("В ярдах:", c)

print("В милях:", d)




16

import math

r=float(input("Введите радиус:"))

area=(math.pi*(r**2))

volume=(4/3*(math.pi*(r**3)))

print("Площадь круга:",area)

print("Объём шара:",volume)




17

import math

m=float(input("Введите объём воды:"))

dT=float(input("Введите разницу температур:"))

q=m*4.186*dT

cent=8.9

z=q*2.777e-7

v=z*cent

print("Количество энергии:", q, "Дж")

print("Cтоимость нагрева воды: %.10f центов." % v)




18

import math

R=float(input("Введите радиус цилиндра:"))

h=float(input("Введите высоту цилиндра:"))

V=(math.pi*R**2*h)

print("Объём цилиндра %.1f" % V)




19

import math

d=float(input("Введите дистанцию:"))

V0=0

a=9.8

Vi=math.sqrt(V0+2*a*d)

print("Скорость объекта:", Vi)




20

P=float(input("Введите давление в паскалях:"))

V=float(input("Введите лбъём в литрах:"))

T1=float(input("Введите температуру в цельсиях:"))

R=8.314

T=T1+273,15

for=P*V=n*R*T


21

NOTE = input("Введите номер ноты :")

if NOTE == "C0":
    C0 = (261.63 / 16)
    print("Частота ноты -", C0, "Гц")
if NOTE == "C1":
    C1 = (261.63 / 8)
    print("Частота ноты -", C1, "Гц")
if NOTE == "C2":
    C2 = (261.63 / 4)
    print("Частота ноты -", C2, "Гц")
if NOTE == "C3":
    C3 = (261.63 / 2)
    print("Частота ноты -", C3, "Гц")
if NOTE == "C4": 
    print("Частота ноты - 261.63")
if NOTE == "C5":
    C5 = (261.63 * 2)
    print("Частота ноты -", C5, "Гц")
if NOTE == "C6":    
    C6 = (261.63 * 4)
    print("Частота ноты -", C6, "Гц") 
if NOTE == "C7":
    C7 =  (261.63 * 8)      
    print("Частота ноты -", C7, "Гц") 
if NOTE == "C8":
    C8 = (261.63 * 16)      
    print("Частота ноты -", C8, "Гц")
if NOTE == "D0":
    D0 = ( 293.66 / 16)
    print("Частота ноты -", D0, "Гц")
if NOTE == "D1":
    D1 = ( 293.66 / 8)
    print("Частота ноты -", D1, "Гц")
if NOTE == "D2":
    D2 = ( 293.66 / 4)
    print("Частота ноты -", D2, "Гц")
if NOTE == "D3":
    D3 = ( 293.66 / 2)
    print("Частота ноты -", D3, "Гц")
if NOTE == "D4": 
    print("Частота ноты - 293.66")
if NOTE == "D5":
    D5 = ( 293.66 * 2)
    print("Частота ноты -", D5, "Гц")
if NOTE == "D6":    
    D6 = ( 293.66 * 4)
    print("Частота ноты -", D6, "Гц") 
if NOTE == "D7":
    D7 =  ( 293.66 * 8)      
    print("Частота ноты -", D7, "Гц") 
if NOTE == "D8":
    D8 = ( 293.66 * 16)      
    print("Частота ноты -", D8, "Гц") 
if NOTE == "E0":
    E0 = ( 329.63 / 16)
    print("Частота ноты -", E0, "Гц")
if NOTE == "E1":
    E1 = ( 329.63 / 8)
    print("Частота ноты -", E1, "Гц")
if NOTE == "E2":
    E2 = ( 329.63 / 4)
    print("Частота ноты -", E2, "Гц")
if NOTE == "E3":
    E3 = ( 329.63 / 2)
    print("Частота ноты -", E3, "Гц")
if NOTE == "E4": 
    print("Частота ноты - 329.63")
if NOTE == "E5":
    E5 = ( 329.63 * 2)
    print("Частота ноты -", E5, "Гц")
if NOTE == "E6":    
    E6 = ( 329.63 * 4)
    print("Частота ноты -", E6, "Гц") 
if NOTE == "E7":
    E7 =  ( 329.63 * 8)      
    print("Частота ноты -", E7, "Гц") 
if NOTE == "E8":
    E8 = ( 329.63 * 16)      
    print("Частота ноты -", E8, "Гц") 
if NOTE == "F0":
    F0 = ( 349.23 / 16)
    print("Частота ноты -", F0, "Гц")
if NOTE == "F1":
    F1 = (349.23  / 8)
    print("Частота ноты -", F1, "Гц")
if NOTE == "F2":
    F2 = (  349.23 / 4)
    print("Частота ноты -", F2, "Гц")
if NOTE == "F3":
    F3 = (  349.23 / 2)
    print("Частота ноты -", F3, "Гц")
if NOTE == "F4": 
    print("Частота ноты - 349.23 ")
if NOTE == "F5":
    F5 = ( 349.23  * 2)
    print("Частота ноты -", F5, "Гц")
if NOTE == "F6":    
    F6 = ( 349.23  * 4)
    print("Частота ноты -", F6, "Гц") 
if NOTE == "F7":
    F7 =  ( 349.23  * 8)      
    print("Частота ноты -", F7, "Гц") 
if NOTE == "F8":
    F8 = ( 349.23  * 16)      
    print("Частота ноты -", F8, "Гц")  
if NOTE == "G0":
    G0 = ( 392.00 / 16)
    print("Частота ноты -", G0, "Гц")
if NOTE == "G1":
    G1 = (  392.00  / 8)
    print("Частота ноты -", G1, "Гц")
if NOTE == "G2":
    G2 = (  392.00  / 4)
    print("Частота ноты -", G2, "Гц")
if NOTE == "G3":
    G3 = (  392.00  / 2)
    print("Частота ноты -", G3, "Гц")
if NOTE == "G4": 
    print("Частота ноты -  392.00 ")
if NOTE == "G5":
    G5 = ( 392.00 * 2)
    print("Частота ноты -", G5, "Гц")
if NOTE == "G6":    
    G6 = (  392.00  * 4)
    print("Частота ноты -", G6, "Гц") 
if NOTE == "G7":
    G7 =  (  392.00  * 8)      
    print("Частота ноты -", G7, "Гц") 
if NOTE == "G8":
    G8 = ( 392.00  * 16)      
    print("Частота ноты -", G8, "Гц") 
if NOTE == "A0":
    A0 = (440.00 / 16)
    print("Частота ноты -", A0, "Гц")
if NOTE == "A1":
    A1 = (440.00  / 8)
    print("Частота ноты -", A1, "Гц")
if NOTE == "A2":
    A2 = (440.00  / 4)
    print("Частота ноты -", A2, "Гц")
if NOTE == "A3":
    A3 = (440.00  / 2)
    print("Частота ноты -", A3, "Гц")
if NOTE == "A4": 
    print("Частота ноты -  440.00 ")
if NOTE == "A5":
    A5 = (440.00 * 2)
    print("Частота ноты -", A5, "Гц")
if NOTE == "A6":    
    A6 = (440.00  * 4)
    print("Частота ноты -", A6, "Гц") 
if NOTE == "A7":
    A7 =  (440.00  * 8)      
    print("Частота ноты -", A7, "Гц") 
if NOTE == "A8":
    A8 = (440.00  * 16)      
    print("Частота ноты -", A8, "Гц") 
if NOTE == "B0":
    B0 = (493.88 / 16)
    print("Частота ноты -", A0, "Гц")
if NOTE == "B1":
    B1 = (493.88  / 8)
    print("Частота ноты -", B1, "Гц")
if NOTE == "B2":
    B2 = (493.88  / 4)
    print("Частота ноты -", B2, "Гц")
if NOTE == "B3":
    B3 = (493.88  / 2)
    print("Частота ноты -", B3, "Гц")
if NOTE == "B4": 
    print("Частота ноты -  493.88 ")
if NOTE == "B5":
    B5 = (493.88 * 2)
    print("Частота ноты -", B5, "Гц")
if NOTE == "B6":    
    B6 = (493.88  * 4)
    print("Частота ноты -", B6, "Гц") 
if NOTE == "B7":
    B7 =  (493.88  * 8)      
    print("Частота ноты -", B7, "Гц") 
if NOTE == "B8":
    B8 = (493.88  * 16)      
    print("Частота ноты -", B8, "Гц") 
    
    
    
................................................
z=float(input("Введите рейтинг сотрудника: "))

if z * 2400.00 == 0 :

    print("Низкий уровень.\nСумма прибавки - 0$.")
    
elif z * 2400.00 ==960 :

    print("Удовлетворительный уровень.\nСумма прибавки - 960$.") 
    
elif z * 2400.00 == 1440 :

    print("Высокий уровень.\nСумма прибавки - 1440$.")
    
elif z * 2400.00 > 1440 :

    print("Высокий уровень.\nСумма прибавки -", z * 2400.00 ,"$")
else: 

    print("Введите корректный рейтинг!")
    
    
    
...............................................
boc=input("Введите буквенную оценку: ")

if boc == "A+" :

    print("Числовая оценка - 4.0")
    
elif boc == "A" :

    print("Числовая оценка - 4.0")
    
elif boc == "A-" :

    print("Числовая оценка - 3.7")
    
elif boc == "B+" :

    print("Числовая оценка - 3.3")
    
elif boc == "B" :

    print("Числовая оценка - 3.0")
    
elif boc == "B-" :

    print("Числовая оценка - 2.7")
    
elif boc == "C+" :

    print("Числовая оценка - 2.3")
    
elif boc == "C" :

    print("Числовая оценка - 2.0")
    
elif boc == "C-" :

    print("Числовая оценка - 1.7")
    
elif boc == "D+" :

    print("ЧИсловая оценка - 1.3")
    
elif boc == "D" :

    print("ЧИсловая оценка - 1.0")
    
elif boc == "F" :

    print("ЧИсловая оценка - 0")
    
else:

    print("Введите правильную буквенную оценку!")
    
    
    
.........................................
MAG=float(input("Введите магнитуду: "))

if MAG < 2.0:

    print("Минимальное.")
    
elif MAG >= 2.0 and MAG <= 3.0:

    print("Очень слабое.")
    
elif MAG >= 3.0 and MAG <= 4.0:

    print("Слабое.")
    
elif MAG >= 4.0 and MAG <= 5.0:

    print("Промежуточное.")
    
elif MAG >= 5.0 and MAG <= 6.0:

    print("Умеренное.")
    
elif MAG >= 6.0 and MAG <= 7.0:

    print("Сильное.")
    
elif MAG >= 7.0 and MAG <= 8.0:

    print("Очень сильное.")
    
elif MAG >= 8.0 and MAG <= 10.0:

    print("Огромное.")
    
elif MAG >= 10.0:

    print("Разрушительное.")
    
    
    
    
..................................

import math

a=float(input("Введите значение a: "))

b=float(input("Введите значение b: "))

c=float(input("Введите значение c: "))

D1=((b**2)-4*a*c)

if D1 < 0:

    print("Функция не имеет корней.")
    
elif D1 == 0:

    D = math.sqrt(D1)
    
    x1 =(-b+D)/(2*a)
    
    x2 =(-b-D)/(2*a)
    
    print("Функция имеет один корней.")
    
    print ("x=", x1)
    
else:

    D = math.sqrt(D1)
    
    x1 =(-b+D)/(2*a)
    
    x2 =(-b-D)/(2*a)
    
    print("Функция имеет два корня.")
    
    print ("x1=", x1, "x2=", x2)



...................................

choc=float(input("Введите числовую оценку: "))

if choc == 0 :


    print("Буквенная оценка - F ")
    
elif choc >= 0 and choc < 1.0:

    print("Буквенная оценка - D ")
    
elif choc >= 1.0 and choc < 1.3:

    print("Буквенная оценка - D+ ")
    
elif choc >= 1.3 and choc < 1.7:

    print("Буквенная оценка - C- ")
    
elif choc >= 1.7 and choc < 2.0:

    print("Буквенная оценка - C")
    
elif choc >= 2.0 and choc < 2.3:

    print("Буквенная оценка - C+")
    
elif choc >= 2.3 and choc < 2.7:

    print("Буквенная оценка - B- ")
    
elif choc >= 2.7 and choc < 3.0:

    print("Буквенная оценка - B")
    
elif choc >= 3.0 and choc < 3.3:

    print("Буквенная оценка - B+")
    
elif choc >= 3.3 and choc < 3.7:

    print("Буквенная оценка - A- ")
    
elif choc >= 3.7 and choc < 4.0:

    print("Буквенная оценка - A ")
    
elif choc >= 4.0:

    print("Буквенная оценка - A+ ")
    
...................................




fraza = input("Введите фразу: ")

sh = 3

B = " "

for i in fraza:

    if i.isupper():
    
        i1 = ord(i)
        
        i2 = ord(i) + ord("A")
        
        i3 = (i2 + sh) % 26
        
        i4 =  i3 + ord("A")
        
        i5 = chr(i4)
        
        B = B + i5
        
    else:
    
        i1 = ord(i)
        
        i2 = ord(i) + ord("A")
        
        i3 = (i2 + sh) % 26
        
        i4 =  i3 + ord("A")
        
        i5 = chr(i4)
        
        B = B + i5
        
print("Шифр:",B)

......................................




fraza = input("Введите фразу: ")

shag = 3

B = ""

for i in fraza :

        i1 = ord(i)
        
        i2 = ord(i) - ord("A")
        
        i3 = (i2 - sh) % 26
        
        i4 =  i3 + ord("A")
        
        i5 = chr(i4)
        
        B = B + i5
        
print("Шифр:",  B)   

.......................................








