# Política de privacidad de StockLocal

**Fecha de entrada en vigor:** 11 de noviembre de 2026

**Desarrollador y responsable de la aplicación:** Jael Crispin

**Publicada en Google Play mediante la cuenta de desarrollador:** Carlos Andrey

**Contacto:** jaelcrispin37108@gmail.com

StockLocal es una aplicación para Android que ayuda a un negocio pequeño a llevar su catálogo de productos con precios y existencias, a generar códigos QR para sus productos y a compartir su catálogo en un PDF. Esta política explica qué información maneja la aplicación y cómo la protege.

## 1. Resumen

* **Tus datos se guardan solo en tu teléfono.**
* StockLocal **no tiene servidores**, **no pide que crees una cuenta**, **no muestra anuncios**, **no usa tu ubicación** y **no recopila, vende ni comparte** la información de tu negocio.
* La información solo sale de tu teléfono cuando **tú decides compartir un PDF**.
* La aplicación **no solicita acceso a internet**.
* El componente de lectura de códigos con la cámara (ML Kit de Google) puede enviar a Google datos técnicos de diagnóstico, nunca tus productos, precios ni imágenes. Se explica en la sección 5.

## 2. Qué información maneja la aplicación

La aplicación guarda lo que tú escribes o escaneas:

* **Productos:** nombre, categoría, precio, unidad de venta, existencias, cantidad mínima para avisarte, código de barras y notas.
* **Movimientos de existencias:** ventas, reposiciones y ajustes, con su fecha y hora.
* **Datos de tu negocio:** nombre, teléfono, dirección, horario y símbolo de moneda. Estos datos aparecen en el catálogo y en los códigos QR que tú generas.
* **Preferencias de avisos:** si quieres recibir avisos y a qué hora.

Los códigos QR que genera la aplicación contienen el nombre del producto, su precio y los datos de tu negocio que hayas escrito. Esos códigos son públicos para quien los escanee: **no escribas en tu negocio datos que no quieras que otras personas vean**.

## 3. Dónde se guarda

Los datos se almacenan en una base de datos local (SQLite) dentro del almacenamiento privado de la aplicación en tu teléfono. No se envían a ningún servidor del desarrollador ni de terceros. La aplicación no necesita conexión a internet para funcionar.

## 4. Permisos que usa la aplicación

|Permiso|Para qué se usa|
|-|-|
|**Cámara**|Solo cuando abres el escáner: leer el código QR de tus etiquetas o el código de barras de un producto. La imagen se procesa en el momento en tu teléfono y **no se guarda ni se envía**.|
|**Notificaciones**|Mostrar los avisos de poco stock y el recordatorio diario que tú actives.|
|**Vibración**|Hacer vibrar el teléfono cuando llega un aviso.|
|**Iniciar al encender el teléfono**|Mantener programado el recordatorio diario cuando se reinicia el teléfono.|

La aplicación no accede a tus contactos, tu ubicación ni tu micrófono, y no lee tus fotos ni tus archivos. Para guardar un PDF usa el selector de carpetas del sistema y solo escribe en la carpeta que tú elijas.

## 5. Lectura de códigos con la cámara

La lectura de códigos QR y de barras se hace **en tu teléfono** con ML Kit de Google. La imagen no se envía a StockLocal ni a ningún servidor.

Según la documentación de ML Kit, este componente puede enviar a Google datos técnicos de diagnóstico y estadísticas de uso, como información del dispositivo y de la aplicación, identificadores del dispositivo, métricas de rendimiento y códigos de error. Estos datos **no incluyen** tus imágenes, tus productos ni tus precios. Google los cifra al enviarlos y no los transfiere a terceros. StockLocal no recibe esa información y no puede desactivarla. Puedes consultar los detalles en la [divulgación de datos de ML Kit](https://developers.google.com/ml-kit/android-data-disclosure).

## 6. Compartir información

StockLocal no comparte los datos de tu negocio con nadie. Lo único que sale de tu teléfono por tu decisión son el catálogo en PDF o las etiquetas cuando **tú** los generas y eliges compartirlos (por ejemplo, por WhatsApp o correo), guardarlos o imprimirlos. A partir de ese momento, el archivo queda bajo el control de la aplicación o persona con quien lo compartas.

## 7. Respaldo de Android

Android puede respaldar automáticamente los datos de las aplicaciones en tu cuenta de Google si tienes activado el respaldo del teléfono. Eso lo decide y lo administra tu sistema Android, no StockLocal. Puedes desactivarlo en los ajustes de tu teléfono.

## 8. Seguridad

Los datos se guardan en el almacenamiento privado de la aplicación, al que otras aplicaciones no tienen acceso en un teléfono sin modificar. StockLocal no cifra la base de datos por su cuenta, por lo que te recomendamos proteger tu teléfono con un bloqueo de pantalla.

## 9. Conservación y eliminación de tus datos

Tus datos permanecen en tu teléfono hasta que tú los borres. Puedes eliminarlos en cualquier momento:

* borrando un producto dentro de la aplicación,
* desinstalando la aplicación, o
* en los ajustes de Android: **Aplicaciones → StockLocal → Almacenamiento → Borrar datos**.

Los PDF que hayas guardado o compartido son archivos aparte y debes borrarlos tú.

## 10. Menores de edad

StockLocal está dirigida a personas adultas que administran un negocio. No está dirigida a niños y no recopila información de ellos.

## 11. Cambios en esta política

Si esta política cambia, se publicará la versión actualizada en esta misma dirección con una nueva fecha de entrada en vigor.

## 12. Contacto

Si tienes preguntas sobre esta política o sobre cómo se maneja tu información, escribe a: **jaelcrispin37108@gmail.com**.
