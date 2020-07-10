# 1.SORU
# import locale
# from datetime import datetime
# dir(datetime)
#
# s = input('Tarihi Gün-Ay-Yıl şeklinde giriş yapınız : ')
# # s = "08-03-2017"
# d = datetime.strptime(s, '%d-%m-%Y')
# try:
#     locale.setlocale(locale.LC_ALL, 'Turkish_Turkey.1254')
# except locale.Error:
#     locale.setlocale(locale.LC_ALL, 'Turkish_Turkey.1254')
# print(d.strftime('%d %B %Y'))


# 2.SORU
# w, h = 3, 3;
# a = [[0 for x in range(w)] for y in range(h)]
# top = 0
# top2 = 0
# a[0][0] = 1
# a[0][1] = 2
# a[0][2] = -1
# a[1][0] = 2
# a[1][1] = 5
# a[1][2] = 2
# a[2][0] = -1
# a[2][1] = -2
# a[2][2] = 2
# w, h = 3, 3;
# b = [[0 for x in range(w)] for y in range(h)]
# w, h = 4, 3;
# sonuc = [[0 for x in range(w)] for y in range(h)]
# c = [1, 2, 3]
# y1 = [2, 5, 20]
# y2 = [21, 12, 1]
# y3 = [25, 7, 21]
# y4 = [14, 2, 1]
#
#
# def sifre():
#     x1 = [18, 21, 20]
#     x2 = [11, 1, 25]
#     x3 = [4, 21, 18]
#     x4 = [14, 1, 1]
#     for i in range(3):
#         for j in range(3):
#             top = a[i][j] * x1[j]
#             sonuc[i][j] = top
#     top = 0
#     top += sonuc[0][1]
#     top += sonuc[0][2]
#     top += sonuc[0][0]
#     c[0] = top
#     top = 0
#     top += sonuc[1][1]
#     top += sonuc[1][2]
#     top += sonuc[1][0]
#     c[1] = top
#     top = 0
#     top += sonuc[2][1]
#     top += sonuc[2][2]
#     top += sonuc[2][0]
#     c[2] = top
#     print("<<< RUT >>>")
#     print(c)
#     for i in range(3):
#         for j in range(3):
#             top = a[i][j] * x3[j]
#             sonuc[i][j] = top
#     top = 0
#     top += sonuc[0][1]
#     top += sonuc[0][2]
#     top += sonuc[0][0]
#     c[0] = top
#     top = 0
#     top += sonuc[1][1]
#     top += sonuc[1][2]
#     top += sonuc[1][0]
#     c[1] = top
#     top = 0
#     top += sonuc[2][1]
#     top += sonuc[2][2]
#     top += sonuc[2][0]
#     c[2] = top
#     print("<<< KAY >>>")
#     print(c)
#     for i in range(3):
#         for j in range(3):
#             top = a[i][j] * x1[j]
#             sonuc[i][j] = top
#     top = 0
#     top += sonuc[0][1]
#     top += sonuc[0][2]
#     top += sonuc[0][0]
#     c[0] = top
#     top = 0
#     top += sonuc[1][1]
#     top += sonuc[1][2]
#     top += sonuc[1][0]
#     c[1] = top
#     top = 0
#     top += sonuc[2][1]
#     top += sonuc[2][2]
#     top += sonuc[2][0]
#     c[2] = top
#     print("<<< DUR >>>")
#     print(c)
#     for i in range(3):
#         for j in range(3):
#             top = a[i][j] * x4[j]
#             sonuc[i][j] = top
#     top = 0
#     top += sonuc[0][1]
#     top += sonuc[0][2]
#     top += sonuc[0][0]
#     c[0] = top
#     top = 0
#     top += sonuc[1][1]
#     top += sonuc[1][2]
#     top += sonuc[1][0]
#     c[1] = top
#     top = 0
#     top += sonuc[2][1]
#     top += sonuc[2][2]
#     top += sonuc[2][0]
#     c[2] = top
#     print("<<< NAA >>>")
#     print(c)
# sifre()



# SORU3
# def a(n):
#    if n == 1:
#        return n
#    else:
#        return n*a(n-1)
# top= 0
# no = int(input("Sayi Giriniz : "))
# if no>=9 and no<16:
#   for no in range((no*2)+1):
#     if no%2==0:
#       top+=no
#   print("sonuc:",top)
#
# elif no<9:
#   print (a(no))
# elif no>=16:
#   print("Lutfen 16 dan dusuk bır sayı gırınız")



# SORU4
# no = int(input("Öğrenci Numaranızı girin: "))
# # Öğrenci No 1904107020;
#
# length = len(str(no))
# strno = str(no)
# sonikihane = strno[length - 2:]
# sayac = 0;
# ust = 100
#
# for sayi in range(int(sonikihane), ust + 1):
#     if sayi > 1:
#         for i in range(2, sayi):
#             if (sayi % i) == 0:
#                 break
#         else:
#             print(sayi)
#             sayac = sayac + 1
# print("Toplam asal sayı:" + str(sayac))






