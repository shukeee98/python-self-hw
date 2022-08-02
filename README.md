# python-self-hw
Ushbu repasitory da python darslari bo'yicha vazifa kodlari joylashgan

"""
Created on Wed Jul 20 10:58:59 2022

@author: shuke

Homeworks
"""


# =============================================================================
# 03 Print(), Sinteks va Arifmetik amallar
# 
# 
# AMALIYOT
# 
# Quyidagi matnni aynan shunday ko'rinishda konsolda chiqaring:
# "Nexia", "Tico", 'Damas' ko'rganlar qilar havas
# Quyidagi misollarga yechimni Pythonda chiqaring. Har bir misoldan avval misol matnini izoh ko'rinishida yozing:
# 
# 5 ning 4-darajasini toping
# 
# 22 ni 4 ga bo'lganda qancha qoldiq qoladi?
# 
# Tomonlari 125 ga teng kvadratning yuzi va perimetrini toping
# 
# Diametri 12 ga teng bo'lgan doiraning yuzini toping  ( deb oling)
# 
# Katetlari 6 va 7 bo'lgan to'g'ri burchakli uchburchakning gipotenuzasini toping
# 
# 
# print('"Nexia", "Tico", Damas, ko\'rganlar qilas havas.')
# 
# print("5 ning 4-darajasi", 5**4)
# 
# print("22 ni 4 g bo'lganda qoldiq", 24%4)
# =============================================================================


# =============================================================================
# 04 O'zgaruvchilar
# 
# print("Hello World!")
# 
# xabar = 'Hello World!'
# 
# print(xabar)
# =============================================================================


# =============================================================================
# 05 String (Matn)
# 
# kocha = "Bog'bon"
# 
# mahalla = "Sog'bon"
# 
# tuman = "Bodomzor" 
# 
# viloyat = "Samarqand"
# 
# print(kocha + ' ko\'chasi, ' + mahalla + ' mahallasi, ' + tuman + ' tumani, ' + viloyat + ' viloyati!')
# 
# print("Iltimos quyidagi ma'lumotlarni kiriting:")
# 
# kocha = input("Ko'changiz: \n>>> ")
# 
# mahalla = input("Mahallangiz: \n>>> ")
# 
# tuman = input("Tumaningiz: \n>>> ")
# 
# viloyat = input("Viloyatingiz: \n>>> ")
# 
# manzil = f"{kocha} ko'chasi, {mahalla} mahallasi, {tuman} tumani, {viloyat} viloyati."
# 
# print(manzil.title())
# print(manzil.upper())
# print(manzil.lower())
# print(manzil.capitalize())
# 
# print(kocha + ' ko\'chasi, ' + mahalla + ' mahallasi, ' + tuman + ' tumani, ' + viloyat + ' viloyati!' )
# 
# =============================================================================


# =============================================================================
# 06 Sonlar
# 
# son = int(input("Istalgan sonni kiriting:\n>>> "))
# 
# print(son, "ning kvadrati", + son**2, "ga teng")
# 
# print(son, "ning kubi", + son**3, "ga teng")
# 
# yosh = int(input("Yoshingiz nechchida?\n>>> "))
# 
# t_yil = 2022 - yosh
# 
# print("Siz ", t_yil, " da tug'ilgansiz")
# 
# 
# a = float(input("Birinchi sonni kiriting:\n>>> "))
# 
# b = float(input("Ikkinchi sonni kiriting:\n>>> "))
# 
# print(f"{a}+{b}=", a+b)
# 
# print(f"{a}-{b}=", a-b)
# 
# print(f"{a}*{b}=", a*b)
# 
# print(f"{a}/{b}=", a/b)
# =============================================================================


# =============================================================================
# #07 List (Ro'yhatlar)
# 
# ismlar = ['Ali', 'Doni', 'Izzat', 'Mirzo', 'Qori', 'Tuya']
# 
# print("Salom " + ismlar[0] + " choyxonaga boramizmi?")
# 
# print(ismlar[2] + ' qo\'ydi qo\'ltig\'i nima gap? ')
# 
# t_shaxslar = ['Amir Temur', 'Boburchik', 'Luppillo']
# 
# z_shaxslar = ['Qo\'ydiki', 'Moldiki', 'Ittiki']
# 
# tshaxs = t_shaxslar.pop(2)
# 
# zshaxs = z_shaxslar.pop(1)
# 
# print("Men tarixi shaxslarndan ", tshaxs + " bilan, zamonaviy shaxslardan ", zshaxs + " bilan suhbat qilishni xohlardim!")
# 
# friends = []
# 
# friends.append('Ali')
# friends.append('Kalish')
# friends.append('Tesha')
# friends.append('Qahhor')
# friends.remove("Qahhor")
# friends.remove("Tesha")
# friends.append('Jumavoy')
# friends.insert(2, 'Joja')
# print(friends)
# 
# mehmonlar = []
# 
# mehmonlar.append('Ali')
# mehmonlar.append('Jora')
# mehmonlar.append('Abc')
# mehmon = mehmonlar.pop(2)
# print("Kela olmaydigon mehmonlar: ", mehmon)
# print("Kela oladigonlar: ", mehmonlar)
# =============================================================================


# =============================================================================
# #08 Ro'yxatlar bilan ishlash 
# 
# # davlatlar = ['amerika', 'canada', 'new zealand', 'netherland']
# 
# # # print(len(davlatlar))
# 
# # davlatlar.sort()
# 
# # # print(sorted(davlatlar, reverse=True))
# 
# # davlatlar.reverse()
# 
# # print(davlatlar)
# 
# # davlatlar = ['amerika', 'canada', 'new zealand', 'netherland']
# 
# # davlatlar.sort()
# # print(davlatlar)
# # davlatlar.sort(reverse=True)
# # print(davlatlar)
# 
# # sonlar = list(range(120,1200,20))
# # print(sonlar)
# # print(sum(sonlar))
# # print(min(sonlar))
# # print(max(sonlar))
# # print(sonlar[:20])
# # print(sonlar[-20:])
# # print(sonlar[530:550])
# 
# taomlar = ['osh','somsa','norin','shashlik','qozonkabob']
# 
# nonushta = taomlar[:]
# 
# nonushta.remove('osh')
# nonushta.remove('somsa')
# nonushta.remove('qozonkabob')
# nonushta.remove('shashlik')
# nonushta.append('non')
# nonushta.append('qaymoq')
# 
# print(taomlar)
# print(nonushta)
# 
# nonushta[0] = 'qaymoq va non'
# 
# nonushta = tuple(nonushta)
# 
# print(nonushta[0])
# =============================================================================


# =============================================================================
# #09 For takrorlash operatori:
#     
# # dostlar = ['Ali', 'Vali', 'Hasan', 'Husan', 'Olim']
# 
# # for dost in dostlar:
# #     print(dost)
# 
# # print("Kod 5 marta takrorlandi")
# 
# # kinolar = []
# # print("5 ta sevimli kinoyingiz: \n>>> ")
# # for k in range(5):
# #     kinolar.append(input(f"{k+1}-kino: "))
# # print(kinolar)
#  
# n_people = int(input("Bugun nechta odam bilan suhbat qurdingiz?: \n>>> "))
# ismlar = []
# for n in range(n_people):
#     ismlar.append(input(f"{n+1}-suhbat qilgan odamingizni kim edi: \n>>> "))
# print(ismlar)
# =============================================================================


# =============================================================================
# 10 If-else
# 
# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#     if car == 'gm':
#         print(car.upper())
#     else:
#         print(car.title())
#         
# login = input("Ismingiz nima? \n>>> ")
# if login.lower() == 'rusik':
#         print("Xush kelibsiz Admin")
# else:
#         print(f"Sorry {login.title()}, get out here!")
#         
# x = float(input("Son kirit: \n "))
# y = float(input("Son kirit: \n "))
# if x==y: 
#     print(f"Sonlar teng: {x}={y}") 
# else: 
#     print("Notog'ri")
# =============================================================================



















































