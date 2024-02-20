#Ro'yxatlarni qo'shish
#Pythonda ikki yoki undan ko'p ro'yxatlarni o'zaro qo'shishning turli usullari bor. Eng oson yo'li
#"+" operatoridan foydalanishdir
a=[1, 2, 3, 4, 5]
b=[5, 6, 7]
c=a+b
print(c)
# 
mashina1=["Audi", "Mustang", "Ferrari"]
mashina2=["BMW", "Mercedes", "Porsche"]
for x in mashina2:
    mashina1.append(mashina2)
print(mashina1)

# extend()  funksiyasi ham biror ro'yxatdagi elementlarni ikkinchisiga qo'shib chiqadi. Ro'yxat oxiridan qoshiladi
d=[1,2,3,4,5]
e=[5,6,7]
d.extend(e)
print(d)
