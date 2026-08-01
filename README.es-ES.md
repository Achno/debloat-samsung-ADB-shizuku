

<!-- PROJECT LOGO -->
<br />


   <img src="https://i.imgur.com/9w4rsiv.png" width="80" height="80">


  <h3 align="center">Eliminar bloatware de Samsung con ADB y Shizuku </h3>

  <p align="center">
    Una lista de paquetes de bloatware que tienen los teléfonos Samsung con instrucciones para eliminarlos
    <br />
    Autor: (https://github.com/Achno/)

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de Contenidos</summary>
  <ol>
    <li><a href="#Getting Started">Comenzar</a></li>
    <li><a href="#Prerequisites"> Requisitos</a></li>
    <li><a href="#Usage">Uso</a></li>
    <li><a href="#Installation">Instalación</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->

## Comenzar

Puedes eliminar el bloatware de tu teléfono obteniendo acceso root, pero como eso es una molestia, usaremos Shizuku y, con la ayuda de una shell de ADB, eliminaremos los paquetes no deseados

### Requisitos previos

- Shizuku
  ```sh
  Puedes instalar Shizuku desde Google Play Store (GRATIS), F-DROID (GRATIS)
  ```

* Ashell
  ```sh
  Puedes instalar Ashell desde Google Play Store (2.99€), F-Droid (GRATIS)
  ```

### Alternativas

Si tu objetivo es únicamente la gestión de paquetes, podrías usar una herramienta con interfaz gráfica diferente como [esta](https://github.com/SmartPack/PackageManager) en lugar de Ashell.

Aquí procederé con Ashell

### Instalación

Ashell es gratuito únicamente en F-Droid. Para descargar F-Droid:

1. [Visita aquí](https://f-droid.org/)
2. Haz clic en `descargar F-Droid`
3. Asegúrate de habilitar la opción de confiar en las descargas desde tu navegador en la configuración
4. Instala el APK

<p align="right">(<a href="#readme-top">volver al inicio</a>)</p>

<!-- USAGE EXAMPLES -->

## Uso

1. Abre Shizuku y haz clic en `emparejamiento`
2. Ve a las Opciones de desarrollador y habilita `depuración USB` y `depuración inalámbrica`
3. Haz clic en `depuración inalámbrica` y toca en `emparejar dispositivo con código de emparejamiento`
4. Introduce el código en Shizuku y haz clic en `iniciar` en la aplicación

Si has seguido todos los pasos correctamente, Ashell funcionará correctamente.

> **Advertencia** ⚠️
 Si ves una pantalla roja indicando que necesitas Shizuku y el servidor no está activo, simplemente repite los pasos.

- Abre Ashell y escribe:

```shell
pm uninstall --user 0 <package>
```

- `<package>` será reemplazado por los paquetes de la lista a continuación

**Lista de bloatware**

```shell
 com.android.bookmarkprovider
 com.samsung.android.game.gametools
 com.samsung.android.game.gamehome
 com.samsung.android.game.gos
 com.google.android.syncadapters.calendar
 com.google.android.syncadapters.contacts
 com.samsung.android.app.spage
 com.sec.android.app.billing
 com.google.android.tts
 com.sec.android.daemonapp
 com.google.ar.core
 com.samsung.android.samsungpassautofill
 com.samsung.android.livestickers
 com.samsung.android.app.cocktailbarservice
 com.samsung.android.themestore
 com.google.android.googlequicksearchbox
 com.microsoft.appmanager  | enlace a Windows
 com.google.android.feedback
 com.samsung.android.service.peoplestripe | personas
 com.samsung.android.app.taskedge
 de.axelspringer.yana.zeropage | upday (noticias)
 com.google.android.projection.gearhead | Android Auto
com.samsung.android.mobileservice | compartir en grupo
com.google.android.apps.turbo | Servicios de salud del dispositivo
com.sec.android.widgetapp.webmanual | Manual de usuario
com.samsung.android.authfw | Marco de autenticación de Samsung
com.samsung.android.forest | Bienestar digital
com.samsung.android.themecenter | Servicios de temas de Galaxy
com.samsung.android.mdx | Servicio de conexión a Windows
com.samsung.android.app.sharelive | Compartir rápido
com.samsung.android.aware.service | Compartir rápido (servicio)
com.samsung.android.app.settings.bixby | Configuración de Bixby
samsung.android.beaconmanager | Aplicación de seguimiento de usuario (sensible)
com.sec.android.app.quicktool | Herramientas
com.samsung.android.calendar | Calendario
com.samsung.providers.calendar | Almacenamiento del calendario
com.sec.android.easyMover.Agent | Agente de Smart Switch
com.samsung.android.app.appsedge | Panel lateral de aplicaciones
com.sec.android.widgetapp.easymodecontactswidget | Contactos favoritos
com.samsung.android.app.galaxyfinder | Buscador (menú de notificaciones junto a configuración)
com.sec.samsung.android.widgetapp.samsungapps | Widget de Galaxy Essentials
com.samsung.android.mdx.quickboard | Medios y servicios - Panel lateral
com.samsung.android.app.reminder | Recordatorios
com.osp.app.signin | Cuenta de Samsung
com.samsung.android.kgclient | Servicios del dispositivo (basura de Samsung Pay)
com.samsung.android.da.daagent | Mensajería dual
com.samsung.android.fmmm | Encontrar mi móvil (sistema)
com.samsung.android.rubin.app | Servicio de personalización (sistema ~ seguimiento ~bloat)
com.samsung.android.allshare.service.mediashare | Servicios de cercanía (sistema)
com.samsung.android.game.gos
com.sec.enterprise.knox.cloudmdm.smdms | Servicios de inscripción de Knox
com.samsung.android.knox.analytics.uploader | Cargador de análisis de Knox
com.android.dreams.phototable | Fundos de pantalla dinámicos de fotos
com.android.backupconfirm |restaura la configuración de Google con la función de restauración de copias de seguridad
com.android.dreams.basic | Soporte para el modo protector de pantalla en la configuración de pantalla
com.android.egg | Función huevo de Pascua de versiones de Android
com.android.managedprovisioning | Configuración de trabajo (restricciones corporativas)
com.android.providers.partnerbookmarks | Proporciona marcadores, acerca de, socios, en Chrome
com.samsung.android.app.simplesharing | Compartir enlaces
com.samsung.android.privateshare | Compartir privado
com.samsung.knox.securefolder | Carpeta segura (basura)
com.samsung.android.scloud | Samsung Cloud
com.samsung.android.game.gos
com.facebook.appmanager
com.facebook.services
com.facebook.system
com.facebook.katana
com.microsoft.appmanager
com.microsoft.skydrive
com.samsung.android.bixby.agent
com.samsung.android.bixby.service
com.samsung.android.bixby.wakeup
com.netflix.mediaclient
com.android.chrome

com.sec.android.app.kidshome
com.samsung.android.voc
com.samsung.android.voc.LauncherActivity
com.samsung.android.aremoji
com.sec.android.mimage.avatar.stickers
com.sec.android.widgetapp.easymodecontactswidget
com.samsung.android.game.gos
com.android.hotwordenrollment.xgoogle
com.android.hotwordenrollment.okgoogle
com.samsung.android.kidsinstaller
com.sec.android.easyMover


EXTRA
com.google.android.onetimeinitializer - Proporciona la configuración inicial, seguro de eliminar.
com.google.android.setupwizard | configuración inicial del primer arranque
```

<p align="right">(<a href="#readme-top">volver al inicio</a>)</p>
