# Ozlem
cevap_ver= input("Diktörtgenin mi Üçgenin mi tipini hesaplamak istiyorsunuz? ")
cevap1= "Dikdörtgen"
cevap2= "dikdörtgen"
cevap3= "Dikdortgen"
cevap4= "dikdortgen"

if(cevap_ver==cevap1 or cevap_ver==cevap2 or cevap_ver==cevap4 or cevap_ver==cevap3):
    print("Dikdörtgenin kenar uzunluklarını giriniz")

kenar1= int(input("1. kenar uzunluğu girin: "))
kenar2= int(input("2. kenar uzunluğu girin: "))
kenar3= int(input("3. kenar uzunluğu girin: "))
kenar4= int(input("4. kenar uzunluğu girin: "))
if(kenar1==kenar2==kenar3==kenar4):
    print("Kare")
else:
    print("Dikdörtgen")
    



cevapa= "Üçgen"
cevapb= "üçgen"
cevapc= "Ucgen"
cevapd= "ucgen"
if(cevap_ver==cevapa or cevap_ver==cevapb or cevap_ver==cevapc or cevap_ver==cevapd):
    print("kenar sayılarını giriniz")

kenara= int(input("üçgenin a kenarını girin"))
kenarb= int(input("üçgenin b kenarını girin"))
kenarc= int(input("üçgenin c kenarını girin"))

if(kenara==kenarb) or (kenarb==kenarc) or (kenarc==kenara):
    print("İkizkenar Üçgen")
elif(kenara==kenarb==kenarc):
    print("Eşkenar Üçgen")
else:
    print("Sıradan Üçgen")



































    '''
vize1= int(input("Vize1 Notunuzu Giriniz: "))
vize2= int(input("Vize2 Notunuzu Giriniz: "))
final= int(input("Final Notunuzu Giriniz: "))

gecmenotu= vize1 * 0.3 + vize2 * 0.3 + final * 0.4

if(gecmenotu>= 90):
    print("AA ile Gectiniz")
elif(gecmenotu>= 85):
    print("BA ile Gectiniz")
elif(gecmenotu>= 80):
    print("BB ile Gectiniz")
elif(gecmenotu>= 75):
    print("CB ile Gectiniz")
elif(gecmenotu>= 70):
    print("CC ile Gectiniz")
elif(gecmenotu>= 65):
    print("DC ile Gectiniz")
elif(gecmenotu>= 60):
    print("DD ile Gectiniz")
elif(gecmenotu>= 55):
    print("FD ile Gectiniz")
elif(gecmenotu< 55):
    print("FF ile Gectiniz")
else:
    print("Sınıfta Kaldınız")
'''


'''
kilo= int(input("Kilonuzu Giriniz"))
boy= float(input("Boyunuzu Giriniz"))

BKI = kilo / (boy * boy)

if(BKI<=18.5):
    print("zayıf")
elif(BKI>18.5 and BKI<25):
    print('Normal')
elif(BKI>25 and BKI<30):
    print("Fazla Kilolu")
elif(BKI>=30):
    print("Obez")
'''

'''
sayi1= int(input("Bir sayı giriniz: "))
sayi2= int(input("Bir tane daha sayı giriniz: "))
sayi3= int(input("Bu son:) bir tane daha giriniz: "))

if(sayi1 >= sayi2) and (sayi1 >=sayi2):
  print("En Buyuk sayi: Birinci Sayıdır.")
elif(sayi2 >= sayi2) and (sayi2 >= sayi3):
  print("En Buyuk Sayi: İkinci Sayıdır.")
else:
    print("En Buyuk Sayı: Üçüncü Sayıdır.")
'''



cevap_ver= input("Diktörtgenin mi Üçgenin mi tipini hesaplamak istiyorsunuz? ")
cevap1= "Dikdörtgen"
cevap2= "dikdörtgen"
cevap3= "Dikdortgen"
cevap4= "dikdortgen"

if(cevap_ver==cevap1 or cevap_ver==cevap2 or cevap_ver==cevap4 or cevap_ver==cevap3):
    print("Dikdörtgenin kenar uzunluklarını giriniz")

kenar1= int(input("1. kenar uzunluğu girin: "))
kenar2= int(input("2. kenar uzunluğu girin: "))
kenar3= int(input("3. kenar uzunluğu girin: "))
kenar4= int(input("4. kenar uzunluğu girin: "))
if(kenar1==kenar2==kenar3==kenar4):
    print("Kare")
else:
    print("Dikdörtgen")




cevapa= "Üçgen"
cevapb= "üçgen"
cevapc= "Ucgen"
cevapd= "ucgen"
if(cevap_ver==cevapa or cevap_ver==cevapb or cevap_ver==cevapc or cevap_ver==cevapd):
    print("kenar sayılarını giriniz")

kenara= int(input("üçgenin a kenarını girin"))
kenarb= int(input("üçgenin b kenarını girin"))
kenarc= int(input("üçgenin c kenarını girin"))

if(kenara==kenarb) or (kenarb==kenarc) or (kenarc==kenara):
    print("İkizkenar Üçgen")
elif(kenara==kenarb==kenarc):
    print("Eşkenar Üçgen")
else:
    print("Sıradan Üçgen")
