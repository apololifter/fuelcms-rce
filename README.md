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

![image](https://github.com/user-attachments/assets/3c1a499e-0fd7-4209-8494-29b18acbc903)

