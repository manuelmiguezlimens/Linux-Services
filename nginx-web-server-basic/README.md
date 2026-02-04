# 🌐 Nginx Web Server Basic

## 📌 Descripción

Este laboratorio consiste en la **instalación, configuración y validación de un servidor web Nginx en Linux**, desplegado sobre un **Debian Server** sin entorno gráfico y administrado remotamente mediante **SSH**.

El objetivo es simular un escenario real de **administración de servicios web**, sirviendo contenido estático y validando el acceso desde un equipo cliente externo (host).

---

## 🎯 Objetivos del laboratorio

- Instalar y configurar Nginx en Linux

- Administrar un servidor sin entorno gráfico

- Configurar un sitio web personalizado

- Servir contenido HTML estático

- Gestionar permisos del sistema de archivos

- Validar el acceso HTTP desde el equipo host

- Analizar logs del servicio

- Documentar el servicio correctamente

---

## 🧱 Configuración aplicada

Se ha configurado un virtual host personalizado con las siguientes características:

- Escucha en el puerto 80

- Documento raíz personalizado

- Página HTML estática

- Logs de acceso y error específicos

- Desactivación del sitio por defecto

El archivo de configuración de Nginx utilizado se incluye en este repositorio.

---

## 🗂️ Contenido del sitio web

El sitio web incluye:

- Página index.html personalizada

- Contenido estático simple para validación del servicio

- Estructura de directorios acorde a buenas prácticas

- El fichero HTML se incluye en el repositorio.

---

## 🧪 Validación del servicio

El funcionamiento del servidor web se ha validado mediante:

- Comprobación del estado del servicio Nginx

- Acceso HTTP desde el navegador del equipo host

- Visualización correcta del contenido HTML

- Revisión de logs de acceso y error

- Capturas de pantalla del resultado en el navegador

---

## 🔐 Consideraciones de seguridad

- Servicio accesible únicamente por HTTP (laboratorio básico)

- Permisos de archivos configurados correctamente

- Administración remota mediante SSH

- No se incluyen datos sensibles en el repositorio

- Este laboratorio está diseñado para entornos de pruebas y aprendizaje.

---

## 👤 Autor

Manuel Míguez Liméns

[GitHub](https://github.com/manuelmiguezlimens) | [LinkedIn](https://www.linkedin.com/in/manuelmiguezlimens/) | [Gmail](mailto:miguezlimensmanuel@gmail.com)