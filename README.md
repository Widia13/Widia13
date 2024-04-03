  nama=input("maaukkan nama = ")
nim=input("masukkan nim = ")
absen=int(input("masukkan jumlah absen = "))
uts=int(input("masukkan nilai uts = "))
uas=int(input("masukkan nilai uas = "))
nilai_batas=60
jumlah=absen + uts + uas
rata_rata=jumlah / 3
print("nama = ",nama)
print("nim = ",nim)
print("jumlah nilai = ",jumlah)
print("nilai rata-rata = ",rata_rata)

if rata_rata >= 100:
 print("anda mendapatkan nilai A+")
elif rata_rata >= 80 <= 90:
  print("anda mendapatkan nilai A")
elif rata_rata >= 70 <= 80:
  print("anda mendapatkan nilai B+")
elif rata_rata >= 60 <= 70:
  print("anda mendapatkan nilai B")
elif rata_rata >= 50 <= 60:
  print("anda mendapatkan nilai C")
elif rata_rata >= 40 <= 50:
  print("anda mendapatkan nilai D")
elif rata_rata >= 30 <= 40:
  print("anda mendapatkan nilai E")
else:
  print("nilai kamu jelek")
  
if rata_rata >= nilai_batas:
  print("selamat kamu mendapatkan nilai yg bagus")
else:
  print("kamu gagal mendapatkan nilai bagus dan kamu harus ikut remedial")                   