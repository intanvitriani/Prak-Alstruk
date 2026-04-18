#B.1 Implementasi Kode Pyton
class Kendaraan(object):
    bahan_bakar = "bensin"
    
    def __init__(self):
        self.nama='mobil'
        self.merk='Toyota'
        self.ban=6
        self.asalpabrik='jepang'

    def cetak(self):
        print('kendaraan ', mobil.nama, mobil.merk,"memiliki roda",mobil.ban,"berasal",mobil.asalpabrik)

mobil = Kendaraan() # obyek atau instance

print (mobil.nama)
print (mobil.merk)
print (mobil.ban)
print (mobil.asalpabrik)
print (mobil.bahan_bakar)
print (mobil.bahan_bakar)
mobil.cetak()
