# Política de privacidad — Cavila

**Última actualización: 2026-10-15**

Cavila es una aplicación de acertijos para niños desde los 6 años. Esta política explica qué guarda la app en el teléfono, qué datos de uso y de fallos manda, para qué y cuánto tiempo se guardan. Revisión del 15 de octubre de 2026: pagar ya no pasa por la puerta de adultos, y se detalla qué se mide cuando una compra no se completa (ver «Cambios en esta política»).

---

## Lo corto

No hay cuentas ni registro, no pedimos el nombre del niño ni ningún dato de contacto, no hay publicidad y no hay chat. El avance del niño y sus perfiles se guardan en el teléfono.

Para saber cuántas familias instalan Cavila, de qué app hermana o anuncio nuestro llegan, qué partes usan y qué compran, la app manda datos de uso a Google Analytics para Firebase, sin nombres y sin el identificador de publicidad del teléfono. Y si la app se cierra por un error, o si una compra con Google Play no se completa (por un error, porque se agotó el tiempo o porque se canceló), Firebase Crashlytics manda un informe técnico para poder arreglarlo. Las dos cosas están explicadas una por una en «Estadísticas y fallos».

El juego funciona entero con el teléfono en modo avión: los desafíos, el avance y la voz salen del propio teléfono. Sin conexión, los datos de uso pueden esperar y mandarse después. Para jugar no hace falta red; para pagar Premium, que cobra Google Play, sí.

---

## Qué se guarda en el teléfono

Lo que la app guarda vive en el almacenamiento del propio teléfono:

- El avance del juego (niveles, estrellas, monedas, racha, medallas), para que el niño siga donde quedó.
- El apodo y el emoji de cada perfil, para distinguir a los hermanos que comparten el teléfono.
- La banda de edad, que es opcional, para ajustar la dificultad.
- Los ajustes: sonido, narración, idioma y recordatorio.
- Unas pocas fechas y marcas que solo sirven para decidir qué mostrarle al adulto: cuándo se instaló la app, cuándo empezó la prueba de 3 días del Faro Criterio, qué ofertas de Premium ya vio y si hay acceso Premium.

El apodo lo escribe la familia y puede ser cualquier cosa. No pedimos nombre real, apellido, correo, teléfono, dirección, foto ni fecha de nacimiento: no hay ninguna cuenta que crear.

El informe de la Zona de Papás —en qué avanza y qué le cuesta más— se calcula en el teléfono con ese mismo avance. La analítica no copia el apodo, el emoji, la banda de edad ni el avance: solo anota los hechos sueltos de «Estadísticas y fallos», como que se terminó un nivel y con cuántas estrellas, el idioma de la app y si hay Premium.

La copia de seguridad automática de Android está desactivada a propósito, así que el avance no viaja a tu cuenta de Google.

---

## Estadísticas y fallos (Firebase)

Cavila usa Google Analytics para Firebase en modo infantil. No usa el identificador de publicidad del teléfono (AdID) ni el ANDROID_ID, no registra las pantallas por su cuenta y no permite personalizar anuncios. La analítica funciona con un identificador de instancia de la app: un número aleatorio que se crea al instalarla y que cambia si la desinstalas.

Lo que se manda:

- Cuándo se abre la app y cuánto se usa, y la primera vez que se abre.
- El modelo del teléfono, su idioma y las versiones de Android y de la app.
- Una ubicación aproximada (el país o la ciudad), que Google deduce de la dirección IP. No hay ubicación precisa ni permiso de ubicación.
- Si la instalación llegó desde un enlace nuestro —otra app de la familia o un anuncio nuestro—, el nombre de ese enlace (como «promo-matibu»). La app lo lee del «install referrer» de Google Play, se queda solo con ese nombre y descarta lo demás, incluido el identificador del clic. Aparte, Google Analytics lee por su cuenta ese mismo dato la primera vez que se abre la app, para saber de qué campaña llegó la instalación.
- El idioma de la app y si está en el plan gratis o en cuál de pago.
- Una lista cerrada de hechos de uso: que se terminó o se saltó la bienvenida; que se terminó un nivel, de qué isla y con cuántas estrellas; que se terminó una isla o el reto del día; que se abrió o se cerró la prueba de 3 días del Faro Criterio; que se llegó a un límite del plan gratis (los perfiles o el informe); la entrada a la Zona de Papás y el paso por la puerta de adultos (si se pasó, si la huella respondió o si se tocó un número equivocado; nunca la huella ni el número); los candados tocados y desde qué pantalla; la pantalla de planes, el plan elegido, cómo se cerró y a los cuántos segundos, y si la compra empezó, falló o se restauró; que se pidió una reseña en Google Play; y qué otra app de la familia se vio o se tocó en la Zona de Papás.
- Si un adulto compra Premium: el plan, el precio y la moneda, y si el pago se confirmó más tarde (por ejemplo, uno en efectivo). Ningún dato de pago.
- Si una compra no se completó: el motivo y el código que dio Google Play (por ejemplo, que se canceló, que se acabó el tiempo o que el pago fue rechazado por falta de fondos) y en qué paso de la compra pasó.
- Al cargar los planes: si se pudieron traer los precios de Google Play, si la app se instaló desde Google Play o desde otra fuente, y si corre en un equipo de pruebas de Google (Firebase Test Lab). Sirve para separar las pruebas automáticas de las familias de verdad.

Si la app se cierra por un error, Firebase Crashlytics manda un informe técnico: la traza del error, el modelo del teléfono, las versiones de Android y de la app y la hora. Sin ningún dato del niño. Además, cuando una compra o una consulta a Google Play falla por un error de la tienda, Crashlytics recibe un informe aunque la app no se cierre, con el código y el mensaje que dio Google Play, el paso de la compra, el producto y el plan; tampoco lleva nada del niño.

Lo que nunca va en estos datos: el apodo o el emoji de un perfil, la edad o la banda de edad, las respuestas a los desafíos, nada que se escriba en la app ni el identificador de publicidad. Cada evento tiene una lista cerrada de valores permitidos y lo que no está en esa lista se descarta antes de salir; una prueba automática del código lo vigila en cada versión.

Para qué: para saber cuántas familias instalan la app y se quedan, qué partes se usan, qué app hermana o anuncio nuestro trae familias que compran, y para encontrar y arreglar fallos. Medir de dónde llegan las instalaciones es lo que Google Play llama «publicidad o marketing»; la app no muestra anuncios. No vendemos estos datos y no se comparten con terceros para publicidad. Los de Analytics se borran solos a los 2 meses y los informes de fallos a los 90 días. Google los trata como proveedor de Firebase: firebase.google.com/support/privacy

---

## Qué NO hace la app

- No tiene publicidad, de ningún tipo ni de ninguna red, y no hay perfiles publicitarios ni seguimiento entre aplicaciones.
- No hay cuentas, registro ni inicio de sesión, y no hay servidores nuestros: los datos de uso van a Firebase, que es de Google.
- No hay chat, ni contenido de otros usuarios, ni forma de que el niño le escriba a alguien o reciba mensajes.
- No hay artículos a la venta dentro del juego: las monedas se ganan resolviendo desafíos y no se pueden comprar con dinero real. Lo único que se paga es Premium, y ningún pago se hace sin la ventana de Google Play, que muestra el precio y pide confirmar.
- No usa inteligencia artificial. Hubo un chat con IA durante el desarrollo y se retiró antes de publicar; el diálogo de Gus está escrito a mano.
- No vende información a nadie.

---

## El cobro

La app se puede usar sin pagar nada. Premium, que es opcional, abre el resto del contenido y se paga como suscripción, mensual o anual, o con un pase de pago único; en los dos casos quien cobra es Google Play, con tu cuenta: nosotros no vemos ni recibimos tu tarjeta, tu nombre ni tu dirección.

Para saber si hay acceso Premium, la app le pregunta a Google Play si hay una suscripción activa o un pase comprado. Esa consulta no lleva ningún dato del niño ni de su avance, y si el teléfono está sin conexión el juego sigue funcionando igual. Cuando un adulto compra, la analítica anota el plan, el precio y la moneda (ver «Estadísticas y fallos»), nunca datos de la tarjeta.

No hay compras sorpresa: la pantalla de planes se abre sin la puerta de adultos, pero nada se cobra sin la ventana de pago de Google Play, que muestra el precio y pide confirmar. Si tu hijo usa el teléfono solo, en los ajustes de Google Play puedes pedir tu contraseña o tu huella para cada compra, o usar Google Family Link.

La suscripción se gestiona o se cancela desde Google Play, no desde acá. Restaurar una compra sigue en la Zona de Papás, detrás de la puerta de adultos.

---

## Permisos que pide la app

- Huella o reconocimiento facial (opcional, se puede apagar): sirve para que un adulto abra la Zona de Papás sin tocar los números. Lo verifica el sistema operativo del teléfono; la app nunca ve ni guarda tu huella, solo recibe un "sí" o un "no".
- Notificaciones (opcional, viene apagado): un único recordatorio diario que programa el propio teléfono, sin pasar por ningún servidor.

La app no pide micrófono, ni cámara, ni ubicación, ni contactos, ni acceso a tus archivos. La ubicación aproximada de «Estadísticas y fallos» no sale de ningún permiso: Google la deduce de la dirección IP.

---

## La biblioteca de avisos y los identificadores

El recordatorio diario opcional usa el componente de notificaciones de Android, que trae dentro una biblioteca de Google —Firebase Cloud Messaging— que otras aplicaciones usan para recibir mensajes enviados desde un servidor y que, para eso, registra un identificador del aparato.

Cavila no usa esa función: no hay mensajes desde ningún servidor, la app nunca pide ese identificador de envío, el arranque automático de la biblioteca está apagado y el permiso para recibir esa clase de mensajes está bloqueado. El aviso se arma entero dentro del teléfono y funciona en modo avión.

Lo que sí usa la app son dos identificadores técnicos de Firebase: el de instancia de Analytics y el de instalación que usa Crashlytics para agrupar los informes de fallos. Los dos son números aleatorios que crea la app, no van unidos a ningún nombre, no son el identificador de publicidad y se reinician si la desinstalas. Por eso declaramos «IDs de dispositivo o de otro tipo» en el formulario de seguridad de los datos de Google Play.

---

## Lectura en voz alta

La app puede leer los textos en voz alta usando el motor de texto a voz que ya viene instalado en el teléfono. Lo único que se le entrega a ese motor son los textos de la propia app —los desafíos y los datos del Nido de Gus—: nunca nada que el niño haya escrito.

Ese motor es parte del sistema operativo y se rige por la política de privacidad del fabricante del teléfono.

---

## Niños

Cavila está pensada para niños y cumple las normas de Google Play para familias. No recogemos el nombre del niño, ni su correo, ni su ubicación precisa, ni su edad: la analítica mide cómo se usa la app con un número de instalación aleatorio, sin saber quién la usa, y su avance se queda en el teléfono. No hay publicidad, ni perfiles publicitarios, ni seguimiento entre aplicaciones, ni contenido generado por otros usuarios, ni forma de que un niño contacte con un desconocido dentro de la app.

Las secciones para adultos —el informe, los ajustes y restaurar una compra— están detrás de una puerta que exige tocar el número más grande o confirmar con la huella. La pantalla de planes no tiene esa puerta, pero ningún pago se hace sin la ventana de Google Play (ver «El cobro»).

---

## Cómo borrar los datos

Desde la pantalla de perfiles se puede borrar un perfil con todo su avance. Para borrar todo lo que hay en el teléfono, desinstala la app: el avance, los perfiles y los ajustes no tienen copia en otra parte, así que se borran del todo. Desinstalar también reinicia los identificadores de Firebase: si vuelves a instalar, empiezan unos nuevos.

Lo que ya se mandó a Firebase no se borra al desinstalar, pero caduca solo: los datos de Analytics a los 2 meses y los informes de fallos a los 90 días. Si quieres pedir que se borre antes, o tienes cualquier duda, escríbenos a contacto@gusmarstudios.com. Como esos datos no llevan nombre, correo ni nada que diga de quién son, puede que no tengamos forma de encontrar los de un teléfono en particular; por eso caducan solos.

---

## Cambios en esta política

Si una versión futura cambia algo de esto, este texto y la fecha de arriba se actualizan antes de que esa versión llegue a Google Play. La revisión del 1 de octubre de 2026 agregó Google Analytics para Firebase y Firebase Crashlytics, que la app no usaba antes. La del 15 de octubre de 2026 agregó que pagar ya no pasa por la puerta de adultos, el motivo de una compra que no se completa, la carga de los precios de Google Play junto con la fuente de la instalación y el equipo de pruebas, los errores de la tienda que van a Crashlytics y que Google Analytics lee por su cuenta el enlace de la instalación. Lo que se recoge es lo mismo: solo está mejor contado.

---

## Contacto

Para cualquier duda sobre privacidad, escribe a contacto@gusmarstudios.com.
