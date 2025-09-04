# 🌍 La Odisea — Servidor Minecraft Crossplay (Spigot + Geyser)

**Servidor profesional de Minecraft diseñado para jugadores Bedrock, con compatibilidad Java opcional.**  
Este proyecto combina estabilidad, seguridad y personalización, integrando plugins esenciales y una arquitectura lista para escalar.

---

## 🚀 Características principales

- **Crossplay Bedrock ↔ Java** mediante [GeyserMC](https://geysermc.org/) + [Floodgate](https://github.com/GeyserMC/Floodgate)
- **Plugins esenciales**:
  - `LuckPerms` – Sistema de permisos granular
  - `EssentialsX` – Comandos básicos y utilidades
  - `Vault` – Soporte para economía y permisos
  - `CoreProtect` – Protección contra griefing
  - `WorldEdit` + `WorldGuard` – Herramientas de construcción y protección
- **Spawn protegido** con comandos básicos listos
- **Configuración modular** y documentación clara
- **Acceso Java opcional**, enfocado en jugadores Bedrock

---

## 📁 Estructura del repositorio
La-Odisea/ ├── configs/ │   ├── geyser/ │   ├── floodgate/ │   ├── plugins/ │   └── server.properties ├── docs/ │   ├── instalación.md │   ├── permisos.md │   ├── comandos.md │   └── mantenimiento.md ├── scripts/ │   └── start.sh / start.bat ├── .gitignore └── README.md


> ⚠️ Este repositorio **no incluye archivos .jar, mundos ni datos sensibles**. Todo está gestionado mediante un `.gitignore` optimizado.

---

## 🎯 Objetivo del proyecto

Entregar al cliente un servidor **seguro, estable y personalizable**, listo para crecer según sus necesidades.  
Este proyecto también forma parte de mi portafolio como ejemplo de:

- Diseño de sistemas automatizados y trazables
- Integración de plugins en entornos productivos
- Documentación clara y mantenible
- Aplicación de principios de modularidad y control de versiones

---

## 🛠️ Instalación rápida

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/La-Odisea.git
   - Descarga los .jar necesarios desde sus fuentes oficiales.
- Coloca los archivos en la carpeta correspondiente (plugins/, geyser/, etc.).
- Ejecuta el servidor con el script incluido (start.sh o start.bat).
- Configura los permisos y zonas protegidas según los archivos en docs/.

📚 Documentación incluida
- instalación.md – Guía paso a paso para levantar el servidor
- permisos.md – Roles y configuración base con LuckPerms
- comandos.md – Comandos útiles para moderadores y jugadores
- mantenimiento.md – Buenas prácticas para mantener el servidor estable

🧠 Roadmap (ideas futuras)
- Sistema de misiones o logros con plugins como Quests
- Economía avanzada con tiendas físicas (Shopkeepers) o virtuales
- Integración con Discord para moderación y notificaciones
- Plugin propio para trazabilidad de eventos y validación de configuraciones

👤 Autor
Mario – Desarrollador especializado en automatización, trazabilidad y diseño modular.
Este proyecto refleja mi enfoque práctico y colaborativo, aplicando principios de robustez y claridad al mundo del game modding.

📜 Licencia
Este repositorio está bajo la licencia MIT.
Los plugins utilizados mantienen sus propias licencias, disponibles en sus respectivos sitios oficiales.

---