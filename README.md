=======================<br>
Nama: Fikri Armia Fahmi<br>
NIM: 2023071018<br>
=======================<br>
<br>
======================<br>
PSEUDOCODE KELIPATAN 2<br>
======================
1. Start
2. Input angka
4. For i in range(2, angka+1, 2)
6. If i<angka, Print i
7. End

=================================<br>
PSEUDOCODE MENCARI ANGKA TERBESAR<br>
=================================
1. Start
2. Input Angka1
3. Input Angka2
5. If Angka1>Angka2, print "Angka yang lebih besar adalah {Angka1}"
7. If Angka2>Angka1, print "Angka yang lebih besar adalah {Angka2}"
8. If Angka1==Angka2, print "Angkanya sama besar"
9. End

===================================<br>
PSEUDOCODE MENCARI KPK DARI 3 DAN 4<br>
===================================
1. Start
2. a = 3 dan b = 4
3. Def fpb():<br>
   -If a < b, smaller=a<br>
   -Else, smaller=b<br>
   -For i in range (1,smaller+1)<br>
     -If a%i == 0 and b%i == 0<br>
        fpb = i<br>
     -Return fpb<br>
4. Def kpk(a,b)<br>
   -kpk = int(a*b/fpb(a,b))<br>
   -Retur kpk<br>
5. Print kpk(a,b)
6. End

============================================<br>
PSEUDOCODE MENUKAR POSISI MANGGIS DAN PISANG<br>
============================================
1. Start
2. Piring1 = "Manggis"
3. Piring2 = "Pisang"
4. Piring3 = "Kosong"
5. Piring1, Piring2 = Piring2, Piring1
6. Print Piring1
7. Print Piring2
8. Print Piring3
9. End

================================<br>
PSEUDOCODE MENCARI LUAS SEGITIGA<br>
================================
1. Start
2. alas = 25
3. tinggi = 30
5. luas_segitiga = 1/2 * alas * tinggi
6. Print luas_segitiga
7. End

====================================<br>
PSEUDOCODE MENCARI LUAS JAJAR GENJANG<br>
=====================================
1. Start
2. panjang = 25
3. tinggi = 30
5. luas_jajargenjang = panjang * tinggi
6. Print luas_jajargenjang
7. End

================================<br>
PSEUDOCODE MENCARI VOLUME TABUNG<br>
================================
1. Start
2. jari = 3
3. tinggi = 5
5. volume_tabung = 3.14 * jari*jari * tinggi
6. Print volume_tabung
7. End

=================================<br>
PSEUDOCODE MENCARI VOLUME KERUCUT<br>
=================================
1. Start
2. diameter = 5
3. tinggi = 4
5. volume_kerucut = 1/3 * 3.14 * (diameter/2) * (diameter/2) * tinggi
6. Print volume_kerucut
7. End
