# 🕵️‍♂️🩷Arp-scan & OS detector | Autor @wvverez

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/997f8b8f-5cec-49aa-9a8c-92cede0f89c0" />


Este script en bash permite escanear interfaces de red utilizando arp-scan, identificar dispositivos dentro de la red local, obtener su dirección IP,MAC y deducir su SO mediante el TTL. Además ofrece la opción de ejecutar un escaneo nmap básico sobre los hosts encontrados

🔎 Escaneo arp : automatico por interfaz 

🧬 Deteccion de SO : basado en el TTL 

📡 Multiples interfaces: ens33, eth0, ens8 etc...

📌 Omision de la MAC local 

🚀 Escaneo opcional nmap de el resultado 

# USO
Primero clonas este repositorio
<pre>
  <code>
  git clone https://github.com/wvverez/Arp-scan-OS-detector.git
  </code>
</pre>
Te posicionas en el directorio Arp-scan-OS-detector
<pre>
  <code>
  cd Arp-scan-OS-detector
  </code>
</pre>
Le das permiso de ejecución
<pre>
  <code>
  chmod +x arpscan.sh
  </code>
</pre>
Finalmente los ejecutas
<pre>
  <code>
  ./arpscan.sh
  </code>
</pre>

# 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para cualquier mejora o correción que pueda hacer. 


# 📲 Contacto en caso de fallos 

[![Telegram](https://img.shields.io/badge/-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/wvverez)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/wvverez)


# ⚠️ Advertencia legal 

Este script es únicamente para fines educativos y auditorías en redes donde tengas autorización. El uso inapropiado no solo sería poco ético si no que además puede violar leyes de privacidad y seguridad infórmatica.
