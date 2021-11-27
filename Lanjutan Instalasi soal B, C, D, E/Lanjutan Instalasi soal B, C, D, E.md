# Instalasi Active Directory Domain Services

Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”
![A1](assets/Picture1.png)

Kemudian masuk ke server manager pilih menu manage
![A1](assets/Picture2.png)

Kemudian pilih Add Roles and Features dan next

![A1](assets/Picture3.png)

Pilih Role-Based or feature-based installation kemudian next

![A1](assets/Picture4.png)
Setelah itu pilih select a server from the server pool

![A1](assets/Picture5.png)
Lalu pilih active directory domain server

![A1](assets/Picture6.png)
Kemudain klik add features and next

![A1](assets/Picture7.png)

![A1](assets/Picture8.png)
Kemudian ke features lalu centang Group Policy Management dan next

![A1](assets/Picture9.png)
Install

![A1](assets/Picture10.png)

![A1](assets/Picture11.png)
Setting ip static di cmd menggunakan command> sconfig

![A1](assets/Picture12.png)

Pilih 8
![A1](assets/Picture13.png)

Pilih 1
![A1](assets/Picture14.png)

Setting IP menjadi 192.168.1.10
![A1](assets/Picture15.png)


# INSTALLASI DNS
Kemudian install DNS server sama seperti menginstal domain
16
![A1](assets/Picture16.png)
17
![A1](assets/Picture17.png)
18
![A1](assets/Picture18.png)

# INSTALLASI NET FRAMEWORK 3.5

![A1](assets/Picture19.png)

![A1](assets/Picture20.png)

![A1](assets/Picture21.png)

# Promote Server to a Domain Controller
Kemudian Promote Server to a Domain Controller dengan menekan tanda seru

![A1](assets/Picture22.png)
Pilih add new forest dan beri nama

![A1](assets/Picture23.png)

![A1](assets/Picture24.png)

![A1](assets/Picture25.png)

![A1](assets/Picture26.png)

![A1](assets/Picture27.png)

![A1](assets/Picture28.png)


