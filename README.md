# hen 3.2.3 rus mod

![image](https://i.ibb.co/0QZBxWk/screenshot-2022-11-27-04-58-38.png)
![image](https://i1.imageban.ru/out/2022/12/04/bacc176f87f8897e1ad81ff4be2a3f67.jpg)

Cambios en 3.2.3
Se agregó la opción para habilitar las teclas de acceso rápido (L2 y R2).
Para una mayor compatibilidad, las teclas de acceso rápido están deshabilitadas de forma predeterminada.
Cambios en 3.2.2
Se agregó la limpieza de los registros que se envían al conectarse a PSN para reducir el riesgo de una prohibición.
Se agregó una visualización de si se debe borrar el caché del navegador, el historial, la autenticación. Se agregó la opción para habilitar/deshabilitar los registros de limpieza.
Manejo de claves habilitado:
R2 deshabilita dev_hdd\boot*.txt desde el arranque (puede ser necesario en caso de conflicto con los complementos)
L2 deshabilita todos los complementos, incluidos los complementos hen, por lo que la información sobre cómo habilitar hen no será visible, el icono no cambiará, pero se cargará el kernel, lo que se puede ver ejecutando el juego/software o actualizando XMB (por ejemplo , ingresando al control remoto y saliendo, luego el ícono cambiará)
Cambios en 3.2.1
Se eliminó el procesamiento de teclas de acceso rápido (para una mejor compatibilidad con algunos modelos)
Cambios en 3.2.0
Enchufar:
Agregado: reinicio automático después de la instalación inicial exitosa de HEN desde la red y USB (método 2.2)
Agregado: Acceso a la lista negra de homebrew NP0APOLLO/NP00PKGI3 cuando las llamadas del sistema CFW están deshabilitadas
Agregado: compatibilidad con Libcrypt para juegos de PS1 (archivos LSF/SBI).
Agregado: PSX Bios corregido con código de producto 0x85 para juegos PAL.
Agregado: opciones para cambiar a borrar el navegador web cuando se activa HEN. (Autenticación, caché, cookies, historial)
Carga útil:
Agregado: detección de teclas de acceso rápido:
mantenga presionado R2 para deshabilitar boot_plugins.txt (útil cuando los complementos cuelgan ps3)
Agregado: estado mejorado de open_path.
Mejorado: Map_path.
Mejorado: PS3MAPI.
Cambios en 3.1.7
Se agregaron funciones de Mamba 8.4 (se modificó ps3mapi_process_page_allocate para usar page_table como proceso de entrada y salida y la asignación de dirección de página del kernel que se asignó. Se agregó ps3mapi_process_page_free que toma una tabla de página (asignación de dirección de página de proceso/núcleo) y la libera.
Se reemplazó rco para poder actualizar desde hdd en la actualización del sistema. Para mostrar, debe habilitar dónde están las configuraciones de red (después de la combinación será más baja). Combinación de teclas: L1 + L2 + R1 + R2 + L3 + dpad_down debería aparecer un menú, hay un elemento de depuración de actualización del sistema. las actualizaciones deben colocarse en dev_hdd0\updater\01\ (puede nombrar el archivo de actualización como desee). Es suficiente encenderlo 1 vez y luego, después de activar HEN, habrá elementos adicionales disponibles.
Advertencia de epilepsia eliminada (vacío)
Cambios en 3.1.6
Recompilado para solucionar problemas con juegos de carpetas (si los problemas persisten, cambie el administrador de copias de seguridad)
Pequeños cambios en el menú.
Cambios en 3.1.5
Visualización agregada de varias tiendas a través del mantenimiento (deshabilitado por defecto)
❗ATENCIÓN❗ ¡La compatibilidad de la tienda con HEN RUS no está garantizada! Las tiendas pueden romper el menú, agregar su propio método de inicialización, así que ten cuidado ❗
el parche de audio ahora está desactivado de forma predeterminada
función agregada para eliminar HEN a través de mantenimiento
ediciones menores
Cambios en 3.1.4
Se agregó visualización de guardados de ps2 en utilidades
información actualizada del sistema (3.1.4)
Cambios en 3.1.3
Se cambiaron los íconos de HEN ON / HEN OFF para una comprensión más clara de si hyung está encendido o no (Iconos hechos por @Victoria)
Se modificó el método de restauración de copia de seguridad act.bak
Limpieza agregada (webbrowser/history.xml, http/auth_cache.dat, http/cookie.dat se eliminan);
La extensión RAP ahora puede ser rap o RAP
pantalla fija de 1080p (anteriormente se describió como 2160)
ediciones menores
Cambios en 3.1.2
Opciones añadidas a la sección de mantenimiento:
Ahora puede activar/desactivar la actualización automática a través de Internet y desde una unidad flash (dev_usb00?/HEN_UPD.pkg) (si la opción está desactivada, hyeon funciona un poco más rápido)
Ahora puede habilitar / deshabilitar el parche libaudio para auriculares, porque hay conflictos con los auriculares Sony: elija si lo necesita o no
Ahora puede habilitar/deshabilitar el elemento "habilitar gallina" (funciona después de actualizar xmb; si está habilitado, el elemento será visible y la inscripción "gallina ya está activada", si está deshabilitado, el elemento estará oculto)
Ahora puede habilitar/ocultar utilidades
Ahora puede habilitar / ocultar el elemento "Administrar archivos PKG"
Otro:
Se reemplazó el servidor de comprobación de actualizaciones
Los iconos de las opciones especificadas se alternan
Ahora puede actualizar usando el archivo HEN_UPD.pkg no solo desde el puerto derecho (dev_usb000), sino también desde el izquierdo (dev_usb001)
Traducción agregada para nuevas opciones.
xai_plugin ha sido mejorado.
Información actualizada sobre PS3HEN
Otras ediciones menores

