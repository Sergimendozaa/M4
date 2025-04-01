Activitat 1

Crea una carpeta a la MV Linux a /srv/samba/compartida1 amb els permisos necessaris perquè pugui accedir tothom.
![image](https://github.com/user-attachments/assets/192b08eb-8d10-4d1f-8b21-dc0d3dc6737b)

Crea la configuració de SAMBA per compartir la carpeta per a convidats (sense autenticació) amb lectura i escriptura.
![image](https://github.com/user-attachments/assets/ddf78f31-eb26-4d2d-b523-984929609443)

Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/008f2d87-a5e3-4ca0-bc08-4fa88c510f6d)

Comprova que tens accés des de Windows.
![image](https://github.com/user-attachments/assets/fded37cf-b187-4e0e-ae30-247bddc78e34)

Crea algun fitxer a la carpeta.
![image](https://github.com/user-attachments/assets/26ae9c5e-0a60-49b4-9468-f9dcd43a036b)

Comprova que s'ha creat a Linux.
![image](https://github.com/user-attachments/assets/83419bc5-5436-4c10-a94a-a323c16b5a26)


Activitat 2

Crea una carpeta a la MV Linux a /srv/samba/compartida2 amb els permisos necessaris.
![image](https://github.com/user-attachments/assets/b1754bf8-8f00-430a-bda3-416220afd8c1)

Crea un usuari local anomenat user1_X (on X és el teu cognom).
![image](https://github.com/user-attachments/assets/02dd6129-b2d5-499b-8b8a-0652567b3791)

Afegeux l'usuari anterior a SAMBA.
![image](https://github.com/user-attachments/assets/2f128221-10ef-42d8-bed0-4a626052d4ae)

Crea la configuració de SAMBA per compartir la carpeta per a l'usuari anterior amb lectura i escriptura amb màscara de fitxers 755.
![image](https://github.com/user-attachments/assets/0e9bb50e-079d-462a-92a4-d562db67f494)

Reinicia el servei SAMBA.
![image](https://github.com/user-attachments/assets/55efdf76-6b7f-467d-9160-8870edef6742)

Comprova que tens accés des de Windows amb les credencials de l'usuari.
![image](https://github.com/user-attachments/assets/0195264c-d93b-45b6-9801-823e9714d113)

Crea algun fitxer a la carpeta.
![image](https://github.com/user-attachments/assets/72cef686-22f6-4457-b4fb-60ff9da12e04)

Comprova que s'ha creat a Linux i té els permisos 755.
![Uploading image.png…]()
