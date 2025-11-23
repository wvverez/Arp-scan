# 🕵️‍♂️🩷Arp-scan & OS detector | Autor @wvverez

<img width="285" height="177" alt="image" src="https://github.com/user-attachments/assets/309601f4-85cb-4760-bd9f-ca1e09ba225d" />

Este script en bash permite escanear interfaces de red utilizando arp-scan, identificar dispositivos dentro de la red local, obtener su dirección IP,MAC y deducir su SO mediante el TTL. Además ofrece la opción de ejecutar un escaneo nmap básico sobre los hosts encontrados

🔎 Escaneo arp : automatico por interfaz 

🧬 Deteccion de SO : basado en el TTL 

📡 Multiples interfaces: ens33, eth0, ens8 etc...

📌 Omision de la MAC local 

🚀 Escaneo opcional nmap de el resultado 

# USO

<pre>
  <code>
  git clone https://github.com/wvverez/Arp-scan-OS-detector.git
  </code>
</pre>

<pre>
  <code>
  cd Arp-scan-OS-detector
  </code>
</pre>

<pre>
  <code>
  chmod +x arpscan.sh
  </code>
</pre>

<pre>
  <code>
  ./arpscan.sh
  </code>
</pre>


# ⚠️ Advertencia legal 

Este script es únicamente para fines educativos y auditorías en redes donde tengas autorización. El uso inapropiado no solo sería poco ético si no que además puede violar leyes de privacidad y seguridad infórmatica.
