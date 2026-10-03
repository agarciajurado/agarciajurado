## Alejandro García Jurado

Técnico en sistemas orientándome a **Blue Team**. Busco mi primer puesto como **analista SOC N1**.

Ahora mismo estoy con el Curso de Especialización en Ciberseguridad en Entornos de las TI y con
el camino SOC Level 1 de TryHackMe.

---

### Home SOC Lab

**[→ agarciajurado/home-soc-lab](https://github.com/agarciajurado/home-soc-lab)**

Laboratorio montado desde cero y documentado paso a paso: Wazuh 4.14.7 sobre Ubuntu Server 24.04
con un Windows 10 como agente.

Dentro hay una investigación completa de un ataque de fuerza bruta contra una cuenta local:

- El SIEM registró los intentos fallidos pero la cuenta nunca se bloqueó. Planteé dos
  explicaciones y las descarté comprobándolas contra los datos.
- La causa estaba en la línea temporal: un inicio de sesión correcto en mitad del ataque
  reiniciaba el contador de intentos fallidos, así que nunca llegaba al umbral.
- Después bajé el umbral de bloqueo a lo que recomienda el benchmark CIS y repetí el mismo
  ataque. La cuenta se bloqueó, pero la regla de correlación de Wazuh dejó de dispararse: con el
  bloqueo cortando antes, ya no llegaban suficientes eventos al SIEM.

Los errores de análisis que cometí por el camino están documentados con su corrección, no
borrados.

---

### Con lo que trabajo

**Detección y respuesta**

![Wazuh](https://img.shields.io/badge/Wazuh-00A9E5?style=for-the-badge&logoColor=white)
![TheHive](https://img.shields.io/badge/TheHive-F57C00?style=for-the-badge&logoColor=white)
![Kaspersky](https://img.shields.io/badge/Kaspersky-00834D?style=for-the-badge&logoColor=white)
![CIS Benchmarks](https://img.shields.io/badge/CIS_Benchmarks-1A3A6B?style=for-the-badge&logoColor=white)

**Sistemas y automatización**

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

### Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alejandro-garc%C3%ADa-jurado)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ale33.gar33@gmail.com)
