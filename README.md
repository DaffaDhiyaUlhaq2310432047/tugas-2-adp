# tugas 2 adp
1.bahasa c++



#include<iostream>

using namespace std;

int main(){
    int tujuan, kelas, tiket, harga, hkelas, hargad;
    string ntujuan, nclass, ndiskon;
    cout<< "Selamat datang di pemesanan tiket Bus PT ANS Lintas-Sumatera\n";
    cout<< "Tujuan yang dipilih:\n1.Medan:Rp100000\n2.Padang:Rp50000\n3.Bukittingi:Rp30000\n4.Jakarta:Rp400000\n5.Bandung:Rp500000\n6.Surabaya:Rp700000\nPilih(1-6):\n";
    cin>>tujuan;
    if (tujuan==1){harga=100000;ntujuan="Medan";}
    else if (tujuan==2){harga=50000;ntujuan="Padang";}
    else if (tujuan==3){harga=30000;ntujuan="Bukittinggi";}
    else if (tujuan==4){harga=400000;ntujuan="Jakarta";}
    else if (tujuan==5){harga=500000;ntujuan="Bandung";}
    else if (tujuan==6){harga=700000;ntujuan="Surabaya";}
    else {"error";}
cout<<"---------------------------------------------------------------------------------------------------------------\n";


    cout<< "Kelas yang dipilih:\n1.Ekonomi Class:Rp10000\n2.Bisnis Class:Rp20000\n3.First Class:Rp30000\n(Pilih 1-3):\n";
    cin>> kelas;
    if (kelas==1){hkelas=10000;nclass="Ekonomi Class";}
    else if (kelas==2){hkelas=20000;nclass="Bisnis Class";}
    else if (kelas==3){hkelas=30000;nclass="First Class";}
    else {"error";}

cout<<"---------------------------------------------------------------------------------------------------------------\n";
    cout<< "Jumlah Tiket: ";cin>>tiket;
    cout<<"---------------------------------------------------------------------------------------------------------------\n";

    if (tiket>=3&&tiket<=5){hargad=tiket*(harga+hkelas)*95/100;ndiskon="5%";}
    else if (tiket>5){hargad=tiket*(harga+hkelas)*90/100;ndiskon="10%";}
    cout<< "Tujuan               : "<<ntujuan<<endl;
    cout<< "Kelas                :"<<nclass<<endl;
    cout<< "Jumlah Tiket         : "<<tiket<<endl;
    cout<< "Total                : Rp"<<tiket*(harga+hkelas)<<endl;
    cout<< "Diskon"<<ndiskon<<endl;
    cout<< "Total Setelah Diskon :Rp"<<hargad;




2.bahasa phyton

   
    print("Selamat datang di pemesanan tiket Bus PT ANS Lintas-Sumatera")
print("Tujuan yang dipilih:")
print("1. Medan: Rp100000")
print("2. Padang: Rp50000")
print("3. Bukittingi: Rp30000")
print("4. Jakarta: Rp400000")
print("5. Bandung: Rp500000")
print("6. Surabaya: Rp700000")
tujuan = int(input("Pilih (1-6): "))

if tujuan == 1:
    harga = 100000
    ntujuan = "Medan"
elif tujuan == 2:
    harga = 50000
    ntujuan = "Padang"
elif tujuan == 3:
    harga = 30000
    ntujuan = "Bukittinggi"
elif tujuan == 4:
    harga = 400000
    ntujuan = "Jakarta"
elif tujuan == 5:
    harga = 500000
    ntujuan = "Bandung"
elif tujuan == 6:
    harga = 700000
    ntujuan = "Surabaya"
else:
    print("error")

print("---------------------------------------------------------------------------------------------------------------")

print("Kelas yang dipilih:")
print("1. Ekonomi Class: Rp10000")
print("2. Bisnis Class: Rp20000")
print("3. First Class: Rp30000")
kelas = int(input("Pilih (1-3): "))

if kelas == 1:
    hkelas = 10000
    nclass = "Ekonomi Class"
elif kelas == 2:
    hkelas = 20000
    nclass = "Bisnis Class"
elif kelas == 3:
    hkelas = 30000
    nclass = "First Class"
else:
    print("error")

print("---------------------------------------------------------------------------------------------------------------")

tiket = int(input("Jumlah Tiket: "))
print("---------------------------------------------------------------------------------------------------------------")

if tiket >= 3 and tiket <= 5:
    hargad = tiket * (harga + hkelas) * 95 / 100
    ndiskon = "5%"
elif tiket > 5:
    hargad = tiket * (harga + hkelas) * 90 / 100
    ndiskon = "10%"

print("Tujuan               :", ntujuan)
print("Kelas                :", nclass)
print("Jumlah Tiket         :", tiket)
print("Total                : Rp", tiket * (harga + hkelas))
print("Diskon               :", ndiskon)
print("Total Setelah Diskon : Rp", hargad)
    







}
