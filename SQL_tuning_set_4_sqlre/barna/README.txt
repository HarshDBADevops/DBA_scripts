Szia Zsolt!

Mell�keltem 2 sql scriptet. Miel�tt elindulna a feldolgoz�s nyiss 2-2 sysdba session-t minden p�ld�nyhoz (CLVS1, CLVS2, CLVSDUP). El�sz�r ind�tsd el az sts.sql-t az egyik, majd a trc.sql-t a m�sik munkamenetben. Ha minden j�l megy, ezek mindaddig futnak, am�g a teszt v�g�n CTRL-C-vel le nem �ll�tod �ket.

Az sts.sql t�rli a Library Cache-b�l a figyelt 4 sql-t, l�trehoz egy SQL tuning Set-et, majd le�ll�t�sig gy�jt�geti a statiszt�kat r�luk.

A trc.sql figyeli, hogy megjelent-e egy �j child cursor a 4 sql valamelyik�hez, ha igen, akkor k�sz�t egy "Compiler" trace f�jlt r�la.

�dv.

    Barna

2016.03.31. 10:46 keltez�ssel, Nagy Zsolt �rta:
Tisztelt Support!
 
K�rem az al�bbi monitoroz�si t�m�ban a k�zrem�k�d�st.
Kiemelt fontoss�g� a jelent�s k�sz�t�s.
 
K�sz�nettel,
Nagy Zsolt Zolt�n
IT infrastrukt�ra �zemeltet�si senior szak�rt�
�gyeleti rendek
 
OTP Bank Nyrt.
DBMO-DBA 
Adatb�zis Menedzsment Oszt�ly
Telefon: +36 (1) 298 3433
Mobil: +36 (70) 708 0313
www.otpbank.hu
 
 
From: Nagy Zsolt 
Sent: Thursday, March 31, 2016 10:43 AM
To: Vicz�n B�la
Cc: Doktor J�nosn� (DoktorJ@otpbank.hu); Irimi J�nos; Anda P�ter
Subject: 30U jelent�s k�sz�t�s
 
Kedves B�la!
 
K�rj�k, hogy �prilis 4.-�n reggel a 30U jelent�st, reggel 8:30-kor egyszerre ind�ts�tok el, a DUP-on �s az �lesen.
El�tte, k�rem, hogy a DUP-ot friss�ts�tek az �lessel a szok�sos m�don, hogy min�l jobban hasonl�tson az �lesre.
A folyamatokat monitorozni fogjuk �s a fut�sok v�g�n ki�rt�kelj�k.
 
K�sz�nettel,
Nagy Zsolt Zolt�n
IT infrastrukt�ra �zemeltet�si senior szak�rt�
�gyeleti rendek
 
OTP Bank Nyrt.
DBMO-DBA 
Adatb�zis Menedzsment Oszt�ly
Telefon: +36 (1) 298 3433
Mobil: +36 (70) 708 0313
www.otpbank.hu
 
 

________________________________________

Ez az �zenet, s b�rmely mell�klete bizalmas inform�ci�kat tartalmazhat �s kiz�r�lag a c�mzettnek sz�l.
Amennyiben nem �n ennek az �zenetnek a c�mzettje, k�rj�k azonnal �rtes�tse a felad�t, s az �zenetet t�r�lje a rendszer�b�l.

This message and any attachment may be confidential and intended exclusively for the addressee.
If you are not the intended addressee please notify the sender immediately and delete this message and any attachment from your system.

OTP Bank Nyrt.
1051 Budapest, N�dor utca 16.
C�gjegyz�ksz�m: Cg.: 01-10-041585; F�v�rosi T�rv�nysz�k C�gb�r�s�ga

