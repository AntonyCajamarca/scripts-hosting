# 🌐 Proyecto: Hosting Web Multiusuario en LinuxLab

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" alt="Tux Linux" width="120"/>
  <h2>Solución Integral de Hosting Web Multiusuario</h2>
  <p><strong>Universidad Politécnica Salesiana | LinuxLab</strong></p>
</div>

---

## 📑 Tabla de Contenidos
- [¿Qué hicimos?](#qué-hicimos)
- [¿Cómo funciona el proyecto?](#cómo-funciona-el-proyecto)
- [Requisitos](#requisitos)
- [Ejecución del script](#ejecución-del-script)
- [Autores](#autores)
- [¡Gracias por visitar el proyecto!](#gracias-por-visitar-el-proyecto)

---

## 🚀 ¿Qué hicimos?

> **Desarrollamos una plataforma educativa de hosting web multiusuario, automatizada y segura, ideal para prácticas en entornos Linux.**

| Herramienta         | Función Principal                                                                 |
|---------------------|---------------------------------------------------------------------------------|
| 🌐 **NGINX**        | Aloja sitios web personales para cada estudiante                                 |
| 🛢️ **MariaDB**      | Gestiona bases de datos independientes y seguras para cada usuario               |
| 🧰 **phpMyAdmin**    | Administra bases de datos MariaDB desde el navegador                             |
| 📡 **vsftpd**        | Permite la carga y gestión de archivos web mediante FTP                          |
| ⚙️ **Script Bash**   | Automatiza la creación de cuentas, directorios, bases de datos y credenciales    |

---

## ⚙️ ¿Cómo funciona el proyecto?

El script principal realiza automáticamente:

- 👤 Creación de **usuario del sistema** en Ubuntu
- 📁 Generación de **directorio web personal** (`/home/usuarioXX/public_html`)
- 🛢️ Creación de **base de datos MariaDB** y usuario asociado
- 🔑 Generación de **contraseñas aleatorias** para FTP y base de datos
- 📡 Configuración de acceso FTP seguro con vsftpd
- 🌐 Inserción automática de configuración en NGINX para acceso web
- 📝 Entrega de archivo de credenciales personalizado para cada usuario

---

## 📋 Requisitos

<div align="center">

| Sistema Operativo | Web Server | PHP | Base de Datos | Admin DB | FTP |
|-------------------|------------|-----|--------------|----------|-----|
| Ubuntu 20.04+     | NGINX      | PHP-FPM | MariaDB | phpMyAdmin | vsftpd |

</div>

---

## ▶️ Ejecución del script

```bash
sudo ./nombre_script.sh
```

---

## 👨‍💻 Autores

- 👨‍🎓 Antony Cajamarca
- 👨‍🎓 Patricio Proaño

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" alt="Tux Linux" width="60"/>
  <br/>
  <strong>Entorno de desarrollo:</strong> LinuxLab (vhost13)<br/>
  <strong>Universidad:</strong> Universidad Politécnica Salesiana
</div>

---

## 🎬 ¡Gracias por visitar el proyecto!

<div align="center">
  <img src="https://media.newyorker.com/photos/5ba177da9eb2f7420aadeb98/master/w_800,c_limit/Cohen-Linus-Torvalds.jpg" alt="Linus Torvalds" width="300"/>
  <br/>
  <em>"Hablar es barato. Enséñame el código."</em>
  <br/>
  <sub>— Linus Torvalds</sub>
</div>
