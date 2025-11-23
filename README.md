# 🕵️‍♂️🩷Arp-scan & OS detector 

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
