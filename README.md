# Bit-cora-T-cnica-IV-Laboratorio-de-Teletransportaci-n-Digital-SSH-y-RDP-Nu-ezGarciaJuanLuis

Pego el docker-compose en el visual una vez que he creado la carpeta indicada y se guarda el docker dentro de la carpeta creada
<img width="584" height="632" alt="image" src="https://github.com/user-attachments/assets/0d94314e-2212-4ca2-8da9-63c13bd3adb0" />




terminal dentro de esa carpeta y ejecuto: docker-compose up -d
<img width="582" height="175" alt="image" src="https://github.com/user-attachments/assets/4386c37e-0055-4c79-b562-b296ec8d3c60" />



Verifico que los contenedores están corriendo con docker ps 
<img width="583" height="161" alt="image" src="https://github.com/user-attachments/assets/24f73136-4e10-4d56-8d2a-b525743df777" />


Me conecto al contenedor usando ssh alumno@localhost -p 2222. La contraseña es sistemas_informaticos.
<img width="586" height="159" alt="image" src="https://github.com/user-attachments/assets/84127934-1908-442c-8caa-0f8453dcb5b0" />


En la máquina anfitriona, genera un par de llaves: ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"
<img width="592" height="78" alt="image" src="https://github.com/user-attachments/assets/86ec209f-0bc1-4e07-ada3-b91ca587043c" />


Copia la llave pública al servidor. Puedes usar ssh-copy-id -p 2222 alumno@localhost o hacerlo manualmente pegando el contenido en ~/.ssh/authorized_keys dentro del contenedor.
<img width="579" height="313" alt="image" src="https://github.com/user-attachments/assets/fdb200f7-4fff-4d48-a7d7-5d19cbe036c8" />

1234



Al abir el escritor remoto y apuntar localhost:3389 me sale este error por lo que voy a aqui:  ve a http://localhost:3000
<img width="448" height="389" alt="image" src="https://github.com/user-attachments/assets/29095260-b88e-43e4-87c7-09389fcd94c6" />
<img width="425" height="407" alt="image" src="https://github.com/user-attachments/assets/01813e26-9c48-478f-aaf3-070b9e4802cd" />


Creo un archivo de texto en el escritorio del contenedor llamado PRUEBA_LOGRADA.txt con un mensaje para el profesor
<img width="440" height="418" alt="image" src="https://github.com/user-attachments/assets/247f36ee-b0da-492b-8aac-592809280472" />

