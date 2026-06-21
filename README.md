<div align="center">

# 📌 Sistemas Operativos - Manejo de un Sistema Operativo en PowerShell  

## 📖 Descripción

</div>

---

Proyecto que explora el uso avanzado de PowerShell para la administración de sistemas operativos Windows.

## 🛠️ Funcionalidades  
- Automatización de tareas del sistema.  
- Gestión de procesos y servicios en Windows.  
- Configuración y monitoreo del rendimiento.  
- Creación de scripts para la administración de usuarios.  

## 🚀 Tecnologías utilizadas  
- Windows PowerShell  
- Scripting en PowerShell  

## ▶️ Cómo ejecutar el proyecto  
1. Abrir PowerShell en modo administrador.  
2. Ejecutar los scripts con:  
   ```powershell
   .\script.ps1
   ```
3. Observar los resultados en la consola.  
4. Modificar los scripts para personalizar la configuración del sistema.  

## 📌 Autor  
👨‍💻 **Alejandro De Mendoza**

---

## Arquitectura

```mermaid
flowchart TD
    A[Administrador Windows - modo admin] --> B[Scripts PowerShell .ps1]
    B --> C[Gestion de Procesos - Get-Process / Stop-Process]
    B --> D[Gestion de Servicios - Get-Service / Start/Stop-Service]
    B --> E[Monitoreo de Rendimiento - Get-Counter / Performance]
    B --> F[Administracion de Usuarios - Get-LocalUser / New-LocalUser]
    B --> G[Automatizacion de Tareas - Task Scheduler]
    C & D & E & F & G --> H[Consola PowerShell - Salida y resultados]
```

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
