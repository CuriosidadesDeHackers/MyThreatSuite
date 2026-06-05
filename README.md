<div align="center">

# 🧩 MyThreatSuite

### *CTI Applications Hub — Security Tools for Defenders*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](.)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](.)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=for-the-badge)](.)

```
 ███╗   ███╗██╗   ██╗    ████████╗██╗  ██╗██████╗ ███████╗ █████╗ ████████╗
 ████╗ ████║╚██╗ ██╔╝       ██║   ██║  ██║██╔══██╗██╔════╝██╔══██╗╚══██╔══╝
 ██╔████╔██║ ╚████╔╝        ██║   ███████║██████╔╝█████╗  ███████║   ██║
 ██║╚██╔╝██║  ╚██╔╝         ██║   ██╔══██║██╔══██╗██╔══╝  ██╔══██║   ██║
 ██║ ╚═╝ ██║   ██║          ██║   ██║  ██║██║  ██║███████╗██║  ██║   ██║
 ╚═╝     ╚═╝   ╚═╝          ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝

 ███████╗██╗   ██╗██╗████████╗███████╗
 ██╔════╝██║   ██║██║╚══██╔══╝██╔════╝
 ███████╗██║   ██║██║   ██║   █████╗
 ╚════██║██║   ██║██║   ██║   ██╔══╝
 ███████║╚██████╔╝██║   ██║   ███████╗
 ╚══════╝ ╚═════╝ ╚═╝   ╚═╝   ╚══════╝
```

> **Portal hub que agrupa las aplicaciones CTI del equipo MyThreatIntel para analistas, hunters y equipos defensivos**

</div>

---

## 🗂️ Aplicaciones de la Suite

| Aplicación | Descripción | Repositorio |
|------------|-------------|-------------|
| 🛡️ **MyThreatIntel** | Tactical CTI Dashboard — Monitor de Ransomware, CVEs e IOCs en tiempo real | [Ver repo](https://github.com/CuriosidadesDeHackers/MyThreatIntel) |
| 🎯 **MyThreatHunter** | Security Visibility & Assessment Platform — M365, AD, Cloud, VM | [Ver repo](https://github.com/CuriosidadesDeHackers/MyThreatHunter) |
| 🔐 **MyThreatSecrets** | One-Time Secret Sharing con cifrado X25519 + XChaCha20-Poly1305 | [Ver repo](https://github.com/CuriosidadesDeHackers/MyThreatSecrets) |

---

## 🏗️ Estructura

```
MyThreatSuite/
├── index.html       # Portal hub principal
├── suite.css        # Estilos globales de la suite
├── styles.css       # Estilos complementarios
└── assets/          # Logos y fotos del equipo
    ├── my-threat-intel-logo.png
    ├── my-threat-hunter-logo.jpeg
    ├── my-threat-secret-logo.png
    ├── manuel-martinez-casasola.jpg
    └── javier-marti-sanz.jpg
```

---

## ⚙️ Despliegue

El portal es una SPA estática servida directamente por Apache.

```bash
# Clona el repositorio
git clone https://github.com/CuriosidadesDeHackers/MyThreatSuite.git

# Copia al directorio web
cp -r MyThreatSuite/* /var/www/suite/

# Configura Apache para servir desde /var/www/suite
# El portal estará disponible en https://mythreatsuite.com/
```

---

## 👨‍💻 Autores

<div align="center">

| | Nombre | Rol | LinkedIn |
|---|--------|-----|----------|
| 🔒 | **Manuel Martinez** | Investigador de Seguridad, Hacker & Consultor CSIRT/DFIR | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuel-mart%C3%ADnez-casasola/) |
| 🛡️ | **Javier Martí** | CISO · Especialista en GRC & COMPLIANCE · CSIRT · DFIR | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javier-marti-sanz/) |

</div>

---

<div align="center">

*Desarrollado para la comunidad de ciberseguridad.*

**Stay secure. 🛡️**

</div>
