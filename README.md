# TreeFrogUI Archivos de configuración - Variante de Gestión para Android (USB/OTG) 
**Modificacion basada y orientada al sistema TreeFrogUI del desarrollador zubertowski. "https://github.com/tzubertowski/TreeFrogUI"

Esta modificación está pensada para poder gestionar nuestra consola desde cualquier dispositivo con Android, como teléfonos celulares o tabletas, de forma totalmente independiente y sin la necesidad obligatoria de una computadora.
Codigo y mejoras creadas por un servidor Jose Silva en colaboración con MartStartIV "https://www.youtube.com/@MartStartIV"


## 📌 Compatibilidad

* **Aversional:** Esta modificación es compatible con cualquier versión de TreeFrogUI, por lo que no depende de una actualización específica para funcionar.
* **Recomendación:** Aunque funciona en cualquier versión, se recomienda utilizar la versión estable más reciente de TreeFrogUI instalada en la consola para garantizar el mejor rendimiento.

---

## 🚀 Características del Sistema

* **Jugar vía USB:** Permite la ejecución de juegos (ROMs) directamente desde la memoria USB conectada al puerto OTG de tu consola, permitiéndote jugar sin tener que copiar los archivos a la consola.
* **Reproducción Multimedia:** Añade compatibilidad completa para reproducir música, videos e imágenes almacenados en tu memoria USB.
* **Instalación Automatizada de Juegos:** Incluye un sistema automatizado para instalar y transferir tus juegos directamente desde la memoria USB hacia la tarjeta MicroSD de la consola.
* **Compatibilidad con Actualizaciones Oficiales:** El sistema está diseñado para respetar las actualizaciones oficiales de la consola sin alterar su funcionamiento base.
* **Sistema de Restauración:** Incluye un script de restauración del sistema (aún en beta funcional) para diagnosticar o reparar archivos esenciales en caso de fallos.


## 🛠️ Archivos Modificados

* **zhijack.sh:** Optimizado y adaptado por completo para funcionar de forma correcta con los archivos inyectados directamente al arranque de la consola.
 
* **tfupdate.sh:** Modificado específicamente para actuar como el lanzador principal de los archivos `.sh` inyectados durante el arranque del sistema.
 
* **upload.sh:** Script encargado de la subida, copia automática y transferencia de contenido desde el almacenamiento externo.
  
* **replace.sh:** Script automatizado para la sustitución segura de archivos del sistema sin necesidad de usar una PC.

* **update.sh:** Script dedicado a la gestión y aplicación de actualizaciones directamente desde el dispositivo móvil vía USB.

