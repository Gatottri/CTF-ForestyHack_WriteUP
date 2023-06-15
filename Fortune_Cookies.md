# Fortune Cookies

## About Challenge
Challenge ini mengajari kita bagaimana cara kerja cookie di sebuah website :
<img width="367" alt="Cuplikan layar 2023-06-15 124423" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/57d91ba2-6d13-430b-9b91-e02eb9660d2d">

## How to Solve
Challenge ini memberikan sebuah website : <img width="959" alt="Cuplikan layar 2023-06-15 125121" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/c82b5c60-e2df-44f7-8a49-da1dae412dbc">

Jika kita menekan tombol 'Get your fortune!' maka akan keluar tampilan :

<img width="959" alt="Cuplikan layar 2023-06-15 125645" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/ca4e19b4-1c81-4dce-ac8e-cbb1ba047667">

Untuk menemukan flag di website tersebut, mari kita gunakan Cookie Editor :

<img width="959" alt="Cuplikan layar 2023-06-15 130109" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/53a78a7c-a8e4-4488-bbb2-3ed03bcfee09">

Di dalamnya terdapat satu cookie yang langsung kita tahu yaitu ada cookie 'flag', mari ubah valuenya dari 0 ke 1

<img width="960" alt="Cuplikan layar 2023-06-15 130617" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/681d0ab3-e1ef-4685-9214-47ec4e46e0da">


lalu kita refresh situsnya dan kita dapatkan flagnya :

<img width="960" alt="Cuplikan layar 2023-06-15 130647" src="https://github.com/Gatottri/CTF-ForestyHack_WriteUP/assets/134616676/450eb93c-b10a-449c-96bb-3de20e35acf9">


## Flag

**ForestyHC{here_is_your_fortun3_cookie_4a0a47}**
