import random

Welcome_Message = ("WELCOME TO SIMPLE GAME")
marsel_postion = random.randint(1, 5)

print("*******************************")
print(f"** {Welcome_Message} **")
print("*******************************")

user = input("Masukkan naman anda: ")

print(f'''
Halo {user}! Perhatikan Goa di bawah ini, Bantu Monyet untuk menemukan pisang kesukannya >-<
!_! !_! !_! !_! !_!
''')

pilihan_user = int(input("Menurut kamu di goa nomor berapa Pisang berada? [1 / 2 / 3 / 4 / 5]: "))
print(f"Pilihan kamu adalah {pilihan_user}")
SystemExit
if pilihan_user == marsel_postion:
    print(f"SELAMAT {user} kamu menang! Posisi pisang berada di goa nomor {marsel_postion}. ")
else:
    print(f" KAMU KALAH! Pisang bukan berada disitu, tetapi berada di goa nomor {marsel_postion} dan pilihan kamu adalah {pilihan_user}. ")

print(f"Terima Kasih {user} Telah Bermain. ")
