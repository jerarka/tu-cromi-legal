---
layout: default
title: Política de Privacidad — Tu Cromi
---

# Política de Privacidad — Tu Cromi

**Última actualización:** 30 de octubre de 2026
**Vigente desde:** 30 de octubre de 2026

Tu Cromi es una aplicación de transporte público para Santa Cruz de la Sierra,
Bolivia, desarrollada por Gerald Avalos. Esta política explica qué información
trata la aplicación y cómo lo hace.

En resumen: **Tu Cromi no tiene cuentas de usuario, no guarda datos personales
y no almacena información tuya en ningún servidor propio.** La aplicación funciona
sin conexión. Hay una única excepción, y está a la vista: cuando escribes el
nombre de un lugar o eliges un punto en el mapa, ese texto o esa coordenada se
envían a un servicio público de mapas (OpenStreetMap) para traducirlo en una
dirección. Esa consulta no está vinculada a tu identidad y la aplicación no
guarda la respuesta. El detalle completo está en la sección «Servicio de mapas».

---

## 1. Información que NO recopilamos

Tu Cromi no recopila ni almacena, en ningún servidor propio, los siguientes datos:

- Nombre, correo electrónico, teléfono ni documento de identidad.
- Cuentas de usuario, perfiles ni credenciales de acceso.
- Contactos, archivos, calendario, mensajes ni fotografías.
- Identificadores de publicidad ni identificadores de seguimiento.
- Datos de uso, estadísticas ni telemetría.
- Datos de diagnóstico, reportes de fallos ni registros de errores.

Tampoco guardamos un historial de búsquedas ni de las rutas que consultas. El
texto que escribes en el buscador de lugares se envía en el momento al servicio
de mapas y no se almacena (ver la sección «Servicio de mapas»); la búsqueda de
rutas se resuelve enteramente en tu dispositivo y no transmite nada.

No utilizamos herramientas de análisis, publicidad, perfilado ni seguimiento de
terceros. La aplicación no contiene anuncios.

La única información que sale de tu dispositivo es la descrita en las secciones
«Conexiones a internet» y «Servicio de mapas»: la descarga del paquete de datos y
las consultas de direcciones. Ninguna de las dos está vinculada a tu identidad.

## 2. No se requiere cuenta

Tu Cromi no tiene registro, inicio de sesión ni cuentas de usuario. Todas sus
funciones están disponibles sin identificarte de ninguna manera.

## 3. Ubicación

Con tu permiso, la aplicación accede a tu ubicación aproximada o precisa para tres
funciones concretas:

- Mostrar tu posición actual sobre el mapa.
- Calcular la distancia a pie entre tu ubicación y los puntos de subida o bajada
  de las líneas.
- Proponer tu posición actual como punto de origen del viaje.

En las dos primeras, **la ubicación se procesa exclusivamente en tu dispositivo**:
no se guarda en ningún registro de la aplicación.

La tercera es la excepción, y solo ocurre con tu acción explícita. Al pulsar el
botón de ubicación, la aplicación obtiene tu posición y la muestra en el mapa,
pero **todavía no la envía a ningún sitio**. Solo si confirmas ese punto como
origen o destino del viaje, la coordenada se envía al servicio de mapas para
obtener la dirección que aparece escrita en el campo (ver la sección «Servicio de
mapas»). Si no confirmas el punto, tu coordenada no sale del dispositivo.

Puedes usar Tu Cromi sin conceder el permiso de ubicación. En ese caso las
funciones anteriores no estarán disponibles, pero la búsqueda de rutas, los
planos y las líneas funcionan con normalidad.

Puedes revocar el permiso en cualquier momento desde **Ajustes → Aplicaciones →
Tu Cromi → Permisos** en tu dispositivo Android.

## 4. Conexiones a internet

La aplicación está diseñada para funcionar sin conexión: los datos de líneas y el
mapa están dentro de la propia aplicación y no requieren internet. La búsqueda de
rutas, el mapa y el detalle de cada línea funcionan sin conexión.

Existen dos tipos de conexión de salida. Ninguna se realiza al abrir la
aplicación ni en segundo plano:

1. **Actualización del paquete de datos.** Ocurre únicamente cuando pulsas
   **Ajustes → Datos sin conexión → Actualizar datos**. Descarga un archivo
   público con información de transporte desde Cloudflare R2, nuestro proveedor
   de alojamiento. Es una solicitud HTTPS para obtener un archivo público.

2. **Consultas de direcciones.** Ocurren mientras usas el buscador de lugares o
   eliges puntos en el mapa. Se detallan en la sección «Servicio de mapas».

Como en cualquier solicitud web, Cloudflare y el servicio de mapas reciben la
dirección IP desde la que se hace la petición, junto con las cabeceras estándar
del protocolo HTTP, y pueden conservarlas en sus registros de servidor según su
propia política de privacidad. No se envía ningún otro dato, y ninguna de estas
conexiones está vinculada a tu identidad.

Ninguna otra función de la aplicación abre conexiones a internet.

## 5. Servicio de mapas (OpenStreetMap)

Para traducir el nombre de un lugar a un punto del mapa, y un punto del mapa a una
dirección legible, Tu Cromi consulta **Nominatim**, un servicio público de
geocodificación de la **OpenStreetMap Foundation**.

La consulta ocurre cuando escribes en el campo de origen o destino (se envía el
texto, con «Santa Cruz de la Sierra, Bolivia» añadido) y cuando eliges un punto en
el mapa o confirmas tu ubicación como origen o destino (se envían la latitud y la
longitud). Se envían además los parámetros técnicos de cualquier petición: formato
de respuesta, límite de resultados, un cuadro delimitador fijo del área de la
ciudad y el identificador `TuCromiApp/1.0`, todo por HTTPS. **No se envía tu
nombre, tu correo, un identificador de dispositivo ni uno de seguimiento, y la
consulta no está vinculada a ninguna cuenta, porque no hay cuentas.**

La respuesta se usa para rellenar un rótulo en pantalla: no se guarda en el
dispositivo ni en ningún servidor propio. La OpenStreetMap Foundation puede
conservar registros de las peticiones según su propia
[política de privacidad](https://osmfoundation.org/wiki/Privacy_Policy).

El plano de la ciudad se genera a partir de datos de OpenStreetMap, se distribuye
dentro de la aplicación y se usa bajo la licencia ODbL
(<https://www.openstreetmap.org/copyright>). Los datos de líneas, recorridos y
puntos de transbordo provienen del operador de transporte y también viajan dentro
de la aplicación.

## 6. Información almacenada en tu dispositivo

La aplicación guarda lo siguiente, únicamente en el almacenamiento interno de tu
dispositivo:

- El paquete de datos de transporte (líneas, recorridos y puntos de transbordo).
- El plano de la ciudad en formato de mapas sin conexión.
- Preferencias locales mínimas, como si ocultaste el aviso de sincronización o si
  activaste el modo sin conexión.

Esta información no contiene datos personales, no se transmite a terceros y se
elimina por completo al desinstalar la aplicación.

## 7. Menores de edad

Tu Cromi no está dirigida a menores de 13 años y no recopila conscientemente
información de menores, por la sencilla razón de que no guarda información
personal de ningún usuario y no tiene cuentas.

## 8. Permisos que solicita la aplicación

| Permiso | Para qué se usa |
|---------|-----------------|
| Ubicación (aproximada y precisa) | Mostrar tu posición en el mapa, calcular distancias a pie y proponer tu origen. Opcional. Se procesa en el dispositivo, salvo la coordenada que confirmes como origen o destino, que se envía al servicio de mapas para obtener la dirección. |
| Acceso a internet | Descargar actualizaciones del paquete de datos cuando tú lo solicitas, y consultar direcciones en el buscador de lugares. Opcional, y sin conexión el resto de la aplicación sigue funcionando. |
| Estado de la red | Adaptar el comportamiento de la actualización y de las consultas según si hay conexión. |

## 9. Tus derechos y control

Como no guardamos datos personales tuyos en ningún servidor, no existe
información que podamos consultar, corregir, exportar ni eliminar. Puedes ejercer
control total de la siguiente manera:

- **Revocar el permiso de ubicación** desde los ajustes de Android. Las funciones
  de ubicación dejan de estar disponibles y no se envía ninguna coordenada tuya.
  El buscador de lugares seguirá enviando el texto que escribas, como se explica
  en la sección «Servicio de mapas».
- **Borrar todos los datos locales** desinstalando la aplicación.
- **Escribirnos** a la dirección de la sección de contacto para cualquier consulta
  sobre el tratamiento de datos.

## 10. Cambios en esta política

Si en el futuro la aplicación incorpora funciones que traten datos personales,
esta política se actualizará antes de que dichas funciones se publiquen, y la
fecha de «última actualización» reflejará el cambio.

## 11. Contacto

Para cualquier consulta sobre esta política o sobre el tratamiento de datos en
Tu Cromi:

**Correo:** avaloss.gerald@gmail.com

**Responsable:** Gerald Avalos — Santa Cruz de la Sierra, Bolivia

---

*Tu Cromi · `com.tucromi.app`*
