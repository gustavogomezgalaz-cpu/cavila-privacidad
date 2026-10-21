# Política de privacidad — Cavila

**Última actualización: 2026-10-21**

Cavila es una aplicación de acertijos para niños desde los 6 años. Esta política explica qué guarda la app en el teléfono, qué datos de uso y de fallos manda, para qué y cuánto tiempo se guardan. Revisión del 21 de octubre de 2026: se agregan los planes por un tiempo sin renovación automática, pagar en un teléfono y abrir en otro con un código, el regalo de familia y lo nuevo que se mide (ver «Cambios en esta política»).

---

## Lo corto

No hay cuentas ni registro, no pedimos el nombre del niño ni ningún dato de contacto, no hay publicidad y no hay chat. El avance del niño y sus perfiles se guardan en el teléfono.

Para saber cuántas familias instalan Cavila, de qué app hermana o anuncio nuestro llegan, qué partes usan y qué compran, la app manda datos de uso a Google Analytics para Firebase, sin nombres y sin el identificador de publicidad del teléfono. Y si la app se cierra por un error, o si una compra con Google Play no se completa (por un error, porque se agotó el tiempo o porque se canceló), Firebase Crashlytics manda un informe técnico para poder arreglarlo. Las dos cosas están explicadas una por una en «Estadísticas y fallos».

El juego funciona entero con el teléfono en modo avión: los desafíos, el avance y la voz salen del propio teléfono. Sin conexión, los datos de uso pueden esperar y mandarse después. Para jugar no hace falta red; para pagar Premium, que cobra Google Play, sí. Y si un adulto paga en su teléfono para abrir la app en otro aparato, la app usa un código y un servidor nuestro, solo para eso (ver «Pagar en un teléfono y abrir en otro»).

---

## Qué se guarda en el teléfono

Lo que la app guarda vive en el almacenamiento del propio teléfono:

- El avance del juego (niveles, estrellas, monedas, racha, medallas), para que el niño siga donde quedó.
- El apodo y el emoji de cada perfil, para distinguir a los hermanos que comparten el teléfono.
- La banda de edad, que es opcional, para ajustar la dificultad.
- Los ajustes: sonido, narración, idioma y recordatorio.
- Unas pocas fechas y marcas que solo sirven para decidir qué mostrarle al adulto: cuándo se instaló la app, cuándo empezó la prueba de 3 días del Faro Criterio, qué ofertas de Premium ya vio, si hay acceso Premium y, con un plan por un tiempo, hasta cuándo dura y qué día se avisó que vence.
- La ficha de los planes que entrega Google Play (el nombre, los precios y las opciones de compra), para poder pagar aunque Google Play tarde en contestar (ver «El cobro»).
- Si un adulto usó el código para pagar en un teléfono y abrir en otro: ese código, hasta cuándo vale y un número de aparato al azar (ver «Pagar en un teléfono y abrir en otro»). Y si un intento de pago no terminó y si ya se mostró el aviso «Mejoramos el pago», para no repetirlo.

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
- Una lista cerrada de hechos de uso: que se terminó o se saltó la bienvenida; que se terminó un nivel, de qué isla y con cuántas estrellas; que se terminó una isla o el reto del día; que se abrió o se cerró la prueba de 3 días del Faro Criterio; que se llegó a un límite del plan gratis (los perfiles o el informe); la entrada a la Zona de Papás y el paso por la puerta de adultos, que piden borrar un perfil, restaurar una compra y lo que sale de la app (si se pasó, si la huella respondió o si se tocó un número equivocado; nunca la huella ni el número); los candados tocados y desde qué pantalla; la pantalla de planes, el plan elegido, cómo se cerró y a los cuántos segundos, y si la compra empezó, falló o se restauró; que se pidió una reseña en Google Play; y qué otra app de la familia se vio o se tocó en la Zona de Papás.
- Si un adulto compra Premium: el plan, el precio y la moneda, si el pago se confirmó más tarde (por ejemplo, uno en efectivo) y si se pagó con el precio del regalo de familia. Ningún dato de pago.
- Si una compra no se completó: el motivo y el código que dio Google Play (por ejemplo, que se canceló, que se acabó el tiempo o que el pago fue rechazado por falta de fondos), en qué paso de la compra pasó, si el teléfono tenía internet y, de la conexión, si era por wifi o por datos, si Android le restringía los datos a la app (por ejemplo, con el ahorro de datos) y si el teléfono tiene los servicios de Google.
- Al cargar los planes: si se pudieron traer los precios de Google Play (y si fue al volver a pedirlos o con unos guardados de hace un rato), si la app se instaló desde Google Play o desde otra fuente, si corre en un equipo de pruebas de Google (Firebase Test Lab), si había internet, cuántos intentos hizo la app y cuántos segundos tardó, y lo mismo de la conexión: si era por wifi o por datos, si Android le restringía los datos a la app y si el teléfono tiene los servicios de Google. Nunca el nombre de la red, la compañía de teléfono ni ninguna dirección. Sirve para separar las pruebas automáticas de las familias de verdad y para saber qué pasa cuando los precios no cargan.
- Si la app pudo guardar en el teléfono la ficha de Google Play de los planes (para abrir el pago aunque Google Play tarde en contestar) y, si un pago se abrió con ella, cómo terminó y si se pagó de entrada con la que ya estaba guardada. La ficha la manda Google Play y no lleva nada del niño ni de la tarjeta.
- Del código para pagar en un teléfono y abrir en otro: que se mostró el código QR y desde dónde, que se abrió en el otro teléfono, que se pagó, que un aparato se abrió con él, que se creó uno para abrir otro aparato, que se tocó su enlace para mandarlo y, si algo falló, el motivo y en qué paso. Nunca el código.
- Del regalo de familia: que se vio el descuento en el pase de nuestras otras apps, que se abrió o se mandó el enlace del regalo y para cuál de ellas, que un código de familia dio el precio con descuento, de qué app venía y cómo llegó, o por qué no. Nunca el código.
- Que se vio el aviso «Mejoramos el pago» y si se tocó «Ver los planes» o se cerró.

Si la app se cierra por un error, Firebase Crashlytics manda un informe técnico: la traza del error, el modelo del teléfono, las versiones de Android y de la app y la hora. Sin ningún dato del niño. Además, cuando una compra o una consulta a Google Play falla por un error de la tienda, Crashlytics recibe un informe aunque la app no se cierre, con el código y el mensaje que dio Google Play, el paso de la compra, el producto y el plan; tampoco lleva nada del niño.

Lo que nunca va en estos datos: el apodo o el emoji de un perfil, la edad o la banda de edad, las respuestas a los desafíos, nada que se escriba en la app ni el identificador de publicidad. Cada evento tiene una lista cerrada de valores permitidos y lo que no está en esa lista se descarta antes de salir; una prueba automática del código lo vigila en cada versión.

Para qué: para saber cuántas familias instalan la app y se quedan, qué partes se usan, qué app hermana o anuncio nuestro trae familias que compran, y para encontrar y arreglar fallos. Medir de dónde llegan las instalaciones es lo que Google Play llama «publicidad o marketing»; la app no muestra anuncios. No vendemos estos datos y no se comparten con terceros para publicidad. Los de Analytics se borran solos a los 2 meses y los informes de fallos a los 90 días. Google los trata como proveedor de Firebase: firebase.google.com/support/privacy

---

## Qué NO hace la app

- No tiene publicidad, de ningún tipo ni de ninguna red, y no hay perfiles publicitarios ni seguimiento entre aplicaciones.
- No hay cuentas, registro ni inicio de sesión. Los datos de uso van a Firebase, que es de Google; el único servidor nuestro es el del código para pagar en un teléfono y abrir en otro, y la app solo le habla si un adulto usa ese código.
- No hay chat, ni contenido de otros usuarios, ni forma de que el niño le escriba a alguien o reciba mensajes.
- No hay artículos a la venta dentro del juego: las monedas se ganan resolviendo desafíos y no se pueden comprar con dinero real. Lo único que se paga es Premium, y ningún pago se hace sin la ventana de Google Play, que muestra el precio y pide confirmar.
- No usa inteligencia artificial. Hubo un chat con IA durante el desarrollo y se retiró antes de publicar; el diálogo de Gus está escrito a mano.
- No vende información a nadie.

---

## El cobro

La app se puede usar sin pagar nada. Premium, que es opcional, abre el resto del contenido y se paga por un tiempo —un mes, tres meses o un año, con un solo pago y sin renovación automática— o con un pase de pago único; en todos los casos quien cobra es Google Play, con tu cuenta: nosotros no vemos ni recibimos tu tarjeta, tu nombre ni tu dirección.

Para saber si hay acceso Premium, la app le pregunta a Google Play si hay una suscripción activa o un pase comprado. Esa consulta no lleva ningún dato del niño ni de su avance, y si el teléfono está sin conexión el juego sigue funcionando igual. Cuando un adulto compra, la analítica anota el plan, el precio y la moneda (ver «Estadísticas y fallos»), nunca datos de la tarjeta.

Para que pagar no falle cuando Google Play tropieza, la app guarda en el teléfono la ficha de los planes que entrega Google Play (el nombre, los precios y las opciones de compra; nada del niño ni tuyo) y paga con ella. Mientras no la tenga, se la vuelve a pedir a Google Play de vez en cuando —a los 15 minutos, a la hora, a las 6 horas y después una vez al día—, solo con internet y aunque la app esté cerrada, con el programador de tareas de Android; al tenerla, deja de pedirla, y si ya hay acceso Premium no se pide. Esa consulta no lleva nada del niño ni de su avance.

No hay compras sorpresa: la pantalla de planes se abre sin la puerta de adultos, pero nada se cobra sin la ventana de pago de Google Play, que muestra el precio y pide confirmar. Si tu hijo usa el teléfono solo, en los ajustes de Google Play puedes pedir tu contraseña o tu huella para cada compra, o usar Google Family Link.

Un plan por un tiempo no se renueva solo: no hay nada que cancelar. La app guarda en el teléfono hasta cuándo dura y, unos días antes de que venza (quince en el plan de un año, tres en los de un mes y tres meses), abre la pantalla de planes para avisarlo y ofrecer extenderlo; si no se extiende, el acceso se cierra solo al vencer. Quien todavía tenga una suscripción de antes, de las que se renuevan, la gestiona o la cancela desde Google Play, no desde acá; y si compra un plan por un tiempo, Google Play la reemplaza por ese plan, así que no quedan dos cobrando. Restaurar una compra sigue en la Zona de Papás, detrás de la puerta de adultos.

---

## Pagar en un teléfono y abrir en otro

Puedes pagar la versión completa desde tu propio teléfono: el aparato del niño muestra un código QR, lo abres en tu teléfono, pagas ahí con tu cuenta de Google Play y el aparato del niño se abre solo. El código de 8 letras también se puede escribir a mano, y desde la Zona de Papás, con «Abrir en otro aparato», una misma compra abre la versión completa en hasta 3 aparatos.

Para eso, y solo cuando un adulto usa el código, la app habla con un servidor nuestro de códigos de activación (gusmar-activacion), que funciona en Cloud Functions y Firestore de Google, como proveedor. Lo que guarda ese servidor: el código; el producto y el comprobante de la compra que entrega Google Play, que no contiene tu nombre, tu correo ni datos de pago; un número de aparato aleatorio que crea la app, que no es el identificador de publicidad, ni el ANDROID_ID, ni ningún otro dato del teléfono; las fechas de cada paso (cuándo se mostró el código, se abrió, se pagó y se activó); y, para poner un tope de pedidos y frenar abusos, un resumen de la dirección IP de cada pedido, que se borra en un día como mucho (los registros técnicos de Google Cloud guardan la dirección IP hasta 30 días). Un aparato que solo muestra el código manda el código y ese número; el que pagó manda además el comprobante de Google Play. En cada aparato, la app recuerda su código y su número para seguir donde quedó, y un aparato abierto con un código le pregunta a ese servidor, como mucho una vez al día, si sigue valiendo.

Para qué: para comprobar con Google Play que la compra es válida y sigue vigente (si se reembolsa, deja de abrir la versión completa), para abrirla en hasta 3 aparatos y para evitar abusos. Ese número es un identificador que se usa solo para que el servicio funcione: no se usa para publicidad, ni para armar perfiles, ni para contactar a nadie, y no se comparte ni se vende.

Cuánto se guarda: un código que nadie paga se borra a los 2 días; el de una compra, mientras la compra siga vigente y hasta 90 días después; y un aparato que no se ve en 60 días libera su cupo. Si quieres que lo borremos antes, escríbenos a contacto@gusmarstudios.com con el código.

El regalo de familia: quien tiene el pase de por vida de una de nuestras apps compra el de las otras con −70%. Para eso ese mismo servidor le da a esa compra un código de familia, ligado al comprobante de Google Play y sin tu nombre, tu correo ni datos de pago, que la app muestra en la Zona de Papás para mandarlo a las otras; la app que lo recibe (por el enlace, por Google Play al instalarla o escrito a mano) se lo pregunta al servidor con su número de aparato, lo guarda en el teléfono y lo revisa una vez al día. Además, una vez al día la app le pregunta al servidor si el regalo está encendido y en qué apps, sin mandar nada más que ese número. El código de familia se guarda mientras el pase siga vigente y hasta 90 días después de un reembolso.

---

## Permisos que pide la app

- Huella o reconocimiento facial (opcional, se puede apagar): sirve para que un adulto confirme lo que pide la puerta de adultos —borrar un perfil, restaurar una compra, abrir algo fuera de la app— sin tocar los números. Lo verifica el sistema operativo del teléfono; la app nunca ve ni guarda tu huella, solo recibe un "sí" o un "no".
- Notificaciones (opcional, viene apagado): un único recordatorio diario que programa el propio teléfono, sin pasar por ningún servidor.

La app no pide micrófono, ni cámara, ni ubicación, ni contactos, ni acceso a tus archivos. La ubicación aproximada de «Estadísticas y fallos» no sale de ningún permiso: Google la deduce de la dirección IP.

Para saber si hay internet —y decirle al adulto que se conecte, en vez de un error de Google Play, y volver a pedir los precios cuando vuelve—, la app consulta el estado de la red del teléfono, con el permiso normal de Android que no pide nada al instalar: si hay conexión, si es por wifi o por datos y si Android le restringe los datos a la app. No lee a qué red estás conectado ni dónde estás. Y para saber si el teléfono tiene los servicios de Google y la Play Store (algunos, como los Amazon Fire, no los traen y ahí Google Play no puede cobrar), la app le pregunta al sistema solo por esas dos aplicaciones, sin ver qué otras tienes.

---

## La biblioteca de avisos y los identificadores

El recordatorio diario opcional usa el componente de notificaciones de Android, que trae dentro una biblioteca de Google —Firebase Cloud Messaging— que otras aplicaciones usan para recibir mensajes enviados desde un servidor y que, para eso, registra un identificador del aparato.

Cavila no usa esa función: no hay mensajes desde ningún servidor, la app nunca pide ese identificador de envío, el arranque automático de la biblioteca está apagado y el permiso para recibir esa clase de mensajes está bloqueado. El aviso se arma entero dentro del teléfono y funciona en modo avión.

Lo que sí usa la app son dos identificadores técnicos de Firebase: el de instancia de Analytics y el de instalación que usa Crashlytics para agrupar los informes de fallos. Los dos son números aleatorios que crea la app, no van unidos a ningún nombre, no son el identificador de publicidad y se reinician si la desinstalas. Por eso declaramos «IDs de dispositivo o de otro tipo» en el formulario de seguridad de los datos de Google Play.

La app usa además la biblioteca de Google Play para actualizar dentro de la app: al abrirla le pregunta a Google Play, en el propio teléfono, si hay una versión nueva, y si es importante abre la pantalla de Google Play para instalarla, como mucho una vez al día. Esa consulta la responde Google Play con la versión disponible; no lleva nada del niño ni de su avance, y la app solo guarda en el teléfono el día en que lo pidió.

---

## Lectura en voz alta

La app puede leer los textos en voz alta usando el motor de texto a voz que ya viene instalado en el teléfono. Lo único que se le entrega a ese motor son los textos de la propia app —los desafíos y los datos del Nido de Gus—: nunca nada que el niño haya escrito.

Ese motor es parte del sistema operativo y se rige por la política de privacidad del fabricante del teléfono.

---

## Niños

Cavila está pensada para niños y cumple las normas de Google Play para familias. No recogemos el nombre del niño, ni su correo, ni su ubicación precisa, ni su edad: la analítica mide cómo se usa la app con un número de instalación aleatorio, sin saber quién la usa, y su avance se queda en el teléfono. No hay publicidad, ni perfiles publicitarios, ni seguimiento entre aplicaciones, ni contenido generado por otros usuarios, ni forma de que un niño contacte con un desconocido dentro de la app.

La Zona de Papás se abre sin puerta: ver el informe y cambiar los ajustes no tiene nada de delicado. Lo que no tiene vuelta atrás o sale de la app —borrar un perfil, restaurar una compra, escribirnos un correo, abrir otra de nuestras apps en Google Play, mandar el enlace que abre la app en otro aparato o abrir y mandar el enlace del regalo de familia— pide una puerta que exige tocar el número más grande o confirmar con la huella. La pantalla de planes no tiene esa puerta, pero ningún pago se hace sin la ventana de Google Play (ver «El cobro»).

---

## Cómo borrar los datos

Desde la pantalla de perfiles se puede borrar un perfil con todo su avance. Para borrar todo lo que hay en el teléfono, desinstala la app: el avance, los perfiles y los ajustes no tienen copia en otra parte, así que se borran del todo. Desinstalar también reinicia los identificadores de Firebase: si vuelves a instalar, empiezan unos nuevos. Si se usó el código para pagar en un teléfono y abrir en otro, lo que guarda nuestro servidor se borra solo en los plazos de esa sección, o antes si nos escribes con el código.

Lo que ya se mandó a Firebase no se borra al desinstalar, pero caduca solo: los datos de Analytics a los 2 meses y los informes de fallos a los 90 días. Si quieres pedir que se borre antes, o tienes cualquier duda, escríbenos a contacto@gusmarstudios.com. Como esos datos no llevan nombre, correo ni nada que diga de quién son, puede que no tengamos forma de encontrar los de un teléfono en particular; por eso caducan solos.

---

## Cambios en esta política

Si una versión futura cambia algo de esto, este texto y la fecha de arriba se actualizan antes de que esa versión llegue a Google Play. La revisión del 1 de octubre de 2026 agregó Google Analytics para Firebase y Firebase Crashlytics, que la app no usaba antes. La del 15 de octubre de 2026 agregó que pagar ya no pasa por la puerta de adultos, el motivo de una compra que no se completa, la carga de los precios de Google Play junto con la fuente de la instalación y el equipo de pruebas, los errores de la tienda que van a Crashlytics y que Google Analytics lee por su cuenta el enlace de la instalación. Lo que se recoge es lo mismo: solo está mejor contado. La revisión del 21 de octubre de 2026 agregó los planes por un tiempo sin renovación automática (con el aviso antes de que venzan y lo que la app guarda para darlo); la actualización dentro de la app con la biblioteca de Google Play; pagar en un teléfono y abrir en otro con un código, y el servidor de la familia que lo hace posible; el regalo de familia; que la Zona de Papás se entra sin puerta (la piden lo delicado y lo que sale de la app); que la ficha de los planes de Google Play quede guardada en el teléfono y, mientras falte, se pida en segundo plano con la app cerrada; y, en las mediciones, el tipo de red (wifi o datos, y si Android restringía los datos a la app), si el teléfono tiene los servicios de Google, cuánto tardó la carga de los precios y los hechos nuevos del código QR y del aviso «Mejoramos el pago».

---

## Contacto

Para cualquier duda sobre privacidad, escribe a contacto@gusmarstudios.com.
