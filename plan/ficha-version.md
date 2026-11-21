# Ficha de verificación de versión · Grupo 04 B

Distribuciones del grupo 04: 

Debian (Gráfica), Alma linux (Consola) y Rocky linux (Imagen base).

## Debian (VM de grafica)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Debian 13.7 ("Trixie"), publicada el 12 de septiembre de 2026. | https://www.debian.org/releases/trixie/ |
| Hasta cuándo recibe actualizaciones de seguridad | Recibe soporte completo de seguridad oficial hasta el 9 de agosto de 2028. | https://www.debian.org/releases/ |
| Requisitos de hardware y si funciona en VirtualBox | 1 GB de RAM (2 GB recomendados) y 10 GB de disco. Funciona en VirtualBox perfectamente (con 2 GB de RAM y 2 CPU). | https://www.debian.org/releases/trixie/amd64/ch03s04.es.html/ |
| ¿El instalador permite particionado manual? | Sí. El instalador de Debian (debian-installer) cuenta con la opción «Manual» en la etapa de Particionado de discos, permitiendo configurar particiones, puntos de montaje, LVM o RAID a medida. | https://www.debian.org/releases/trixie/amd64/ch06s03.es.html#di-partition |
| Guía oficial para instalar Docker Engine en esa familia | Docker dispone de una guía y repositorio oficial exclusivo para Debian | https://docs.docker.com/engine/install/debian/ |
| Imagen base del Dockerfile para esa versión | Existe la imagen oficial en Docker Hub (debian) con la etiqueta exacta de esta versión | https://hub.docker.com/_/debian |

## AlmaLinux (VM de consola)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | AlmaLinux 10.1 ("Purple Lion"), publicada el 24 de noviembre de 2025. | https://almalinux.org/get-almalinux/ |
| Hasta cuándo recibe actualizaciones de seguridad | Hasta el 31 de mayo de 2035. | https://wiki.almalinux.org/release-notes/ |
| Requisitos de hardware y si funciona en VirtualBox | 1.5 GB de RAM (2 GB recomendados), 1 CPU y 10 GB de disco. Sí funciona en VirtualBox (con 2 GB de RAM y 2 CPU). | https://wiki.almalinux.org/documentation/installation-guide.html |
| ¿El instalador permite particionado manual? | Sí. El instalador (Anaconda) tiene la opción «Personalizada» en Destino de la instalación. | https://wiki.almalinux.org/documentation/installation-guide.html |
| Guía oficial para instalar Docker Engine en esa familia | Docker no tiene página propia para AlmaLinux; se usa la de la familia RHEL. | https://docs.docker.com/engine/install/rhel/ |
| Imagen base del Dockerfile para esa versión | Existe la imagen oficial en Docker Hub (`almalinux`) con la etiqueta de la versión elegida (`almalinux:10.1`). | https://hub.docker.com/_/almalinux |

## Rocky Linux (Imagen base de Dockerfile)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Rocky Linux 10.1 ("Red Quartz"), publicada el 25 de noviembre de 2025. | https://rockylinux.org/download |
| Hasta cuándo recibe actualizaciones de seguridad | Hasta el 31 de mayo de 2035. | https://wiki.rockylinux.org/rocky/version/ |
| Requisitos de hardware y si funciona en VirtualBox | 2 GB de RAM, 2 CPU y 10 GB de disco (20 GB recomendados). Sí funciona en VirtualBox (con 2 GB de RAM y 2 CPU). | https://docs.rockylinux.org/guides/installation/ |
| ¿El instalador permite particionado manual? | Sí. El instalador (Anaconda) tiene la opción «Personalizada» en Destino de la instalación. | https://docs.rockylinux.org/guides/installation/ |
| Guía oficial para instalar Docker Engine en esa familia | Docker no tiene página propia para Rocky Linux; se usa la de la familia RHEL. | https://docs.docker.com/engine/install/rhel/ |
| Imagen base del Dockerfile para esa versión | Existe la imagen oficial en Docker Hub (`rockylinux`) con la etiqueta de la versión elegida (`rockylinux:10.1` o `rockylinux:10.1-minimal`). | https://hub.docker.com/_/rockylinux |
