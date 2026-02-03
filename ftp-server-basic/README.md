# 📁 FTP Server Basic (vsftpd)

## 📌 Descripción
Este laboratorio consiste en la instalación, configuración y validación de un servidor FTP en Linux, utilizando vsftpd sobre un Debian Server sin entorno gráfico y administrado de forma remota mediante SSH.

El objetivo es simular un escenario real de administración de servicios Linux, aplicando buenas prácticas de seguridad, permisos, operación y documentación.

---

## 🎯 Objetivos del laboratorio

- Instalar y configurar un servicio FTP en Linux

- Administrar un servidor sin entorno gráfico

- Acceder y gestionar el sistema mediante SSH

- Configurar usuarios locales para FTP

- Restringir usuarios mediante chroot

- Gestionar permisos correctamente

- Validar el funcionamiento del servicio

- Analizar logs del sistema

- Documentar el servicio

---

## 🧱 Configuración aplicada

Principales medidas configuradas en vsftpd.conf:

- Acceso anónimo deshabilitado

- Acceso mediante usuarios locales

- Escritura habilitada

- Usuarios confinados en su directorio (chroot)

- Permisos seguros

- Registro de transferencias habilitado

- Lista blanca de usuarios permitidos

El archivo de configuración utilizado se incluye en este repositorio.

---

## 👤 Gestión de usuarios FTP

- Creación de usuario local dedicado

- Directorio específico para subida y descarga de archivos

- Restricción de acceso al sistema

- Permisos configurados siguiendo buenas prácticas

---

## 👤 Gestión de usuarios FTP

- Creación de usuario local dedicado

- Directorio específico para subida y descarga de archivos

- Restricción de acceso al sistema

- Permisos configurados siguiendo buenas prácticas

---

## 🧪 Validación del servicio

El funcionamiento del servidor FTP ha sido validado mediante:

- Conexión desde un cliente FTP

- Autenticación correcta del usuario

- Subida de archivos

- Descarga de archivos

- Verificación de permisos

- Revisión de logs del servicio

---

## 👤 Autor

Manuel Míguez Liméns

[GitHub](https://github.com/manuelmiguezlimens) | [LinkedIn](https://www.linkedin.com/in/manuelmiguezlimens/) | [Gmail](mailto:miguezlimensmanuel@gmail.com)