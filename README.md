# Tugas-1-Alpro-Pak_Agung
Kelompok 6 :
""" 
1. 23091397148-Sekar Hanum Anastasya Karyanto
2. 23091397158- Firza Mushermansyah
3. 23091397162-Akhmad Fauzi
"""
#Daftar Menu Varian Pizza
print ( 
    """
===== PILIHAN VARIASI =====
1. Frankfurter BBQ  
2. Meat Monstan
3. Super Supreme 
4. Super Supreme Chicken 
""")

# Memilih Varian Pizza
pizza_varian = int(input("Pilih Varian Pizza : "))
if pizza_varian == 1 :
    pizza_varian = " Frankfurter BBQ "
elif pizza_varian == 2 : 
    pizza_varian = " Meat Monstan "
elif pizza_varian == 3 :
    pizza_varian =  " Super Supreme "
elif pizza_varian == 4 :
    pizza_varian = " Super Supreme Chicken "

# Daftar Menu Crust
print (
    """
===== PILIHAN CRUST =====
1. pan 
2. StuffedCrust Cheese
3. StuffedCrust Sausage
4. Cheesy Bites
5. Crown Crust
""")

 # Daftar Ukuran
print (
    """
===== PILIHAN UKURAN =====    
1. Personal 
2. Reguler
3. Large
""")

# Harga Sebelum Memilih Varian
total_harga = 0

# Pembeli Memilih Varian
pizza_crust = int(input("Pilih Crust : "))
pizza_ukuran = int(input(" pilih ukuran : "))

# Program Menghitung jika memilih Crust Pan
if pizza_crust == 1 :
    pizza_crust = "pan"
    # Jika ukuran personal
    if pizza_ukuran == 1 :
        pizza_ukuran = "Personal"
        total_harga = 43_637
    # jika ukuran reguler
    elif pizza_ukuran == 2 :
        pizza_ukuran = "Reguler"
        total_harga = 100_910
    # jika ukuran Large
    elif pizza_ukuran == 3 :
        pizza_ukuran = "Large"
        total_harga = 132_728

# program menghitung jika memilih curst StuffedCrust Cheese
if pizza_crust == 2 :
    pizza_crust = "StuffedCrust Cheese"
    # jika ukuran personal
    if pizza_ukuran == 1 :
        pizza_ukuran = "Personal"
        total_harga = 55_455
    # jika ukuran reguler
    elif pizza_ukuran == 2 : 
        pizza_ukuran = "Reguler"
        total_harga = 120_910
    # jika ukuran large 
    elif pizza_ukuran == 3 :
        pizza_ukuran = "Large"
        total_harga = 160_000

# program menghitung jika memilih crust StuffedCrust sausage
if pizza_crust == 3 :
    pizza_crust = "StuffedCrust Sausage"
    # jika ukuran personal
    if pizza_ukuran == 1 :
        pizza_ukuran = "Personal"
        total_harga = 52_728
    # jika ukuran reguler
        elif pizza_ukuran == 2 : 
        pizza_ukuran = "Reguler"
        total_harga = 117_273 
    # jika ukuran large
    elif pizza_ukuran == 3 :
        pizza_ukuran = "Large"
        total_harga = 155_455

# program menghitung jika memilih crust Chessy Bites
if pizza_crust == 4 :
    pizza_crust = "Chessy Bites"
    # jika ukuran personal
    if pizza_ukuran == 1 :
        pizza_ukuran = "Personal"
        total_harga = 57_273
    # jika ukuran reguler
    elif pizza_ukuran == 2 : 
        pizza_ukuran = "Reguler"
        total_harga = 123_637
    # jika ukuran large 
    elif pizza_ukuran == 3 :
        pizza_ukuran = "Large"
        total_harga = 164_546

# program menghitung jika memilih crust Crown Crust 
if pizza_crust == 5 :
    pizza_crust = "Crown Crust"
    # jika ukuran personal
    if pizza_ukuran == 1 :
        pizza_ukuran = "Personal"
        total_harga = 55_455
    # jika ukuran reguler
    elif pizza_ukuran == 2 : 
        pizza_ukuran = "Reguler"
        total_harga = 120_910
    # jika ukuran large 
    elif pizza_ukuran == 3 :
        pizza_ukuran = "Large"
        total_harga = 160_000

# total harga varian yang dipilih
print ("Total Harga : Rp.", total_harga , ("\n"))

# program jika pakai Extra Cheese
exstra_cheese = input("Apakah Mau Tambah Extra Cheese (y/t) ?")
if exstra_cheese == "y" :
    exstra_cheese = True
    total_harga += 13_636
elif exstra_cheese == "t" : 
    exstra_cheese = False

# total harga akhir
print ("Total Harga Jika Menambah : Rp. ", total_harga) 
