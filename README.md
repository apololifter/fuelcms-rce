# fuelCMS 1.4.1 - Remote Code Execution (RCE) Exploit

Exploit para la vulnerabilidad de ejecución remota de comandos (RCE) en [fuelCMS](https://www.getfuelcms.com/) versión 1.4.1.

- **CVE:** CVE-2018-16763  
- **Afecta a:** fuelCMS <= 1.4.1  
- **Tipo:** Remote Code Execution (RCE)  
- **PoC por:** [Tu nombre o alias]  
- **Fecha del exploit:** [Fecha]

## 🧠 Descripción

Este exploit permite ejecutar comandos de forma remota en servidores que corren fuelCMS 1.4.1, aprovechando una mala validación en el parámetro `filter` de `fuel/pages/select`.

## 💻 Requisitos

- Python 3
- `requests` instalado (`pip install requests`)

## 🚀 Uso

![Captura](https://github.com/user-attachments/assets/239d5466-fed9-4689-a975-8df9fc05a234)
![Captura2](https://github.com/user-attachments/assets/293149e5-6209-4001-829c-3d8520e755aa)


⚠️ Advertencia
Este exploit es solo para fines educativos y de pruebas en entornos controlados (CTFs, laboratorios personales, Hack The Box, TryHackMe, etc).
No lo uses contra sistemas sin autorización. El uso indebido puede ser ilegal.

📜 Referencias
https://www.exploit-db.com/exploits/47138

https://github.com/daylightstudio/FUEL-CMS/releases/tag/1.4.1
