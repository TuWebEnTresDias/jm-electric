# Blog de JM Eléctric

## Alcance editorial

Reserva de 12 temas distintos para unas 12 semanas; no equivale a tres meses de facturación ni fija fechas. El ensayo comercial informado es de un mes, con una nota semanal. No hay programación automática.

Solo la primera nota está habilitada en la versión local. Las otras tres quedan como “Próximamente”, sin enlaces en home o índice y fuera del sitemap. Sus rutas contienen únicamente un aviso con noindex; los textos completos se conservan abajo. No se publicó ningún cambio. La salida semanal será manual y requiere autorización; no hay fechas programadas.

Estados: `proposed`, `approved`, `drafted`, `review`, `ready`, `published`. Solo marcar `published` después de verificar el sitio servido.

## Calendario propuesto

| Semana | Estado | Tema | Slug | Intención del lector | Datos por confirmar |
|---:|---|---|---|---|---|
| 1 | review | Qué conviene revisar antes de instalar un aire acondicionado | `antes-instalar-aire-acondicionado` | Qué información reunir sobre el ambiente, la ubicación del equipo y la instalación eléctrica antes de consultar. | Alcance del servicio y cobertura para cada consulta; revisión técnica del contenido general |
| 2 | drafted | Paneles solares On-Grid y Off-Grid: diferencias para una primera consulta | `paneles-solares-on-grid-off-grid` | Cómo cambia la elección según la conexión a la red, el consumo y la necesidad de respaldo. | Alcance del servicio y cobertura para cada consulta; revisión técnica del contenido general |
| 3 | drafted | Cuándo conviene revisar la instalación eléctrica de una vivienda | `cuando-revisar-instalacion-electrica-vivienda` | Señales y cambios de uso que justifican pedir una evaluación profesional de la instalación. | Alcance del servicio y cobertura para cada consulta; revisión técnica del contenido general |
| 4 | drafted | Qué tener en cuenta antes de instalar cámaras de seguridad | `antes-instalar-camaras-seguridad` | Objetivos de cobertura, conectividad, grabación y privacidad para preparar una primera consulta. | Alcance del servicio y cobertura para cada consulta; revisión técnica del contenido general |
| 5 | proposed | Mantenimiento de aire acondicionado: qué consultar si cambió su funcionamiento | `mantenimiento-aire-acondicionado` | Reconocer cambios y preparar una consulta | Alcance real del mantenimiento y recomendaciones del fabricante |
| 6 | proposed | Qué datos reunir para consultar por un grupo electrógeno | `consulta-mantenimiento-grupo-electrogeno` | Preparar una consulta de mantenimiento | Equipos atendidos y alcance del servicio |
| 7 | proposed | Iluminación para el hogar: cómo describir el resultado que buscás | `planificar-iluminacion-hogar` | Comunicar necesidades de iluminación | Opciones y alcance del proyecto |
| 8 | proposed | Cableado estructurado: cuándo consultar por una red de datos | `cuando-consultar-cableado-estructurado` | Identificar necesidades de conectividad | Tipos de instalaciones atendidas |
| 9 | proposed | Energía solar y cortes de luz: qué preguntar sobre el respaldo | `energia-solar-respaldo-cortes` | Distinguir generación de respaldo | Soluciones ofrecidas y límites de autonomía |
| 10 | proposed | Qué información ayuda a pedir un presupuesto eléctrico | `pedir-presupuesto-electrico` | Describir un trabajo sin intervenir la instalación | Datos necesarios para evaluar y presupuestar |
| 11 | proposed | Cámaras de seguridad: preguntas sobre grabación y acceso | `camaras-grabacion-acceso` | Comparar almacenamiento y permisos | Opciones disponibles, conservación y condiciones |
| 12 | proposed | Reformas en casa: cuándo consultar por la instalación eléctrica | `instalacion-electrica-antes-reforma` | Anticipar cambios de consumo y distribución | Alcance de evaluación y coordinación |

## Hechos y controles

Servicios y cobertura tomados del sitio y del contexto confirmado por el usuario el 23/10/2026. WhatsApp reutiliza el destino del HTML existente, sin envío de mensajes. Las guías son generales, no diagnósticos ni instrucciones de intervención. No se incorporan precios, certificaciones, garantías, casos de éxito, plazos ni disponibilidad. La oferta comercial no se publica en los artículos.

Los borradores HTML están en `blogs/{slug}/index.html`; su resumen figura en el índice. Antes de pasar a `ready`, revisar exactitud técnica, alcance comercial, enlaces y diseño. No hay fechas ni autorías inventadas.

## Verificación local — 23/10/2026

- Seis páginas verificadas: home, índice y cuatro artículos. Rutas internas, recursos, anclas, IDs únicos, un H1 por página y destinos de WhatsApp válidos por inspección estática. No se enviaron mensajes ni se verificó una conversación real.
- Sitemap XML parseado con seis rutas existentes; robots apunta al sitemap del dominio sin el prefijo del repositorio.
- Head y bloques de scripts originales de la home comparados con HEAD, idénticos. `script.js`, `style.css` y `CNAME` sin cambios. `node --check script.js` y `git diff --check` sin errores.
- Chromium local por HTTP: 1440, 768, 680, 390 y 320 px; sin desbordes horizontales, imágenes cargadas y menú móvil comprobado (abrir, cerrar con Escape y al seguir enlace). Capturas locales del índice en escritorio/móvil y de un artículo móvil revisadas visualmente.
- Sin verificación del sitio publicado: respondió HTTP 403 desde el entorno durante la revisión. No se hizo commit, push ni despliegue.


## Borrador reservado — paneles-solares-on-grid-off-grid

**Estado:** `drafted` · Próximamente. Pendiente de revisión y habilitación semanal.

Energía solar

Paneles solares On-Grid y Off-Grid: diferencias para una primera consulta

Cómo cambia la elección según la conexión a la red, el consumo y la necesidad de respaldo.

La primera pregunta es qué necesitás resolver

Reducir energía tomada de la red, abastecer un lugar sin conexión y mantener ciertos consumos durante un corte son objetivos distintos. Antes de comparar equipos, definí cuál es tu prioridad y qué artefactos necesitás alimentar.

On-Grid: conectado a la red

Un sistema On-Grid trabaja conectado a la red eléctrica. La generación solar puede abastecer consumos mientras hay producción. La posibilidad de inyectar excedentes depende de los requisitos y autorizaciones aplicables de la distribuidora. No hay que dar por hecho que un sistema On-Grid convencional dará energía durante un corte: normalmente se desconecta por seguridad. El respaldo requiere una solución diseñada para ese objetivo.

Off-Grid: una instalación independiente

Un sistema Off-Grid está diseñado para operar sin depender de la red. Habitualmente combina generación solar, baterías y equipos de control y conversión. Su autonomía depende del consumo, el almacenamiento, el recurso solar y el diseño. No significa energía ilimitada ni elimina la necesidad de mantenimiento.

Qué datos ayudan a comparar

Reuní consumos de facturas recientes, ubicación del inmueble y una lista de los equipos que querés alimentar. Diferenciá los consumos habituales de los que necesitás sostener durante un corte. El espacio disponible, las sombras y las condiciones del inmueble requieren evaluación; no subas al techo para inspeccionarlos. JM Eléctric ofrece sistemas On-Grid y Off-Grid. La propuesta, los trámites aplicables y la cobertura deben confirmarse para cada caso; no se puede asegurar ahorro o autonomía sin un estudio.

Consultar con JM Eléctric

Atención en CABA y alrededores. Consultá la cobertura y el alcance para tu caso.

Consultar por WhatsApp

↗


## Borrador reservado — antes-instalar-camaras-seguridad

**Estado:** `drafted` · Próximamente. Pendiente de revisión y habilitación semanal.

Cámaras y redes

Qué tener en cuenta antes de instalar cámaras de seguridad

Objetivos de cobertura, conectividad, grabación y privacidad para preparar una primera consulta.

Definí qué querés observar

Controlar un acceso, ver un patio o revisar movimientos en un comercio plantea necesidades distintas. Identificá los sectores de interés y si necesitás ver imágenes en vivo, consultar grabaciones o ambas cosas. Una cámara no garantiza evitar incidentes y su ubicación condiciona lo que podrá registrar.

La imagen depende del entorno

La iluminación, los reflejos, las distancias y los obstáculos influyen en la imagen. También importa el uso nocturno. No alcanza con comparar únicamente la resolución: la evaluación debe considerar el escenario real y los límites de cobertura.

Conexión y grabación son decisiones diferentes

El acceso remoto suele requerir conectividad, mientras que el almacenamiento depende de la solución elegida. Preguntá dónde se guardarán las imágenes, cuánto tiempo se conservarán y qué ocurre ante un corte de luz o de internet. Evitá asumir que todas las cámaras incluyen grabación o que cualquier conexión Wi-Fi sirve para todo el sistema.

Privacidad y acceso a las imágenes

Definí quién podrá acceder y evitá compartir contraseñas o publicar imágenes de personas sin considerar sus derechos. La ubicación debe contemplar la privacidad de vecinos y los requisitos aplicables; en espacios compartidos, consultá las autorizaciones correspondientes. No envíes claves de redes o cuentas en la primera consulta.

Qué información compartir

Indicá barrio o localidad, tipo de inmueble, sectores que querés cubrir y si existe una red de datos. Las fotos del espacio deben tomarse desde un lugar seguro y sin exponer datos personales. JM Eléctric ofrece cámaras de seguridad y cableado estructurado; el equipamiento, la grabación, el acceso remoto y la cobertura se confirman para cada proyecto.

Consultar con JM Eléctric

Atención en CABA y alrededores. Consultá la cobertura y el alcance para tu caso.

Consultar por WhatsApp

↗


## Borrador reservado — cuando-revisar-instalacion-electrica-vivienda

**Estado:** `drafted` · Próximamente. Pendiente de revisión y habilitación semanal.

Electricidad

Cuándo conviene revisar la instalación eléctrica de una vivienda

Señales y cambios de uso que justifican pedir una evaluación profesional de la instalación.

Los cambios de uso pueden requerir una revisión

Una vivienda puede incorporar aires acondicionados, horno eléctrico u otros equipos que cambian su demanda. Antes de sumar consumos importantes, conviene pedir una evaluación de la instalación existente. La antigüedad por sí sola no permite diagnosticar su estado, y que todo encienda tampoco confirma que sea segura.

Señales que no conviene normalizar

Disparos reiterados de protecciones, luces que varían de intensidad o marcas de recalentamiento justifican una consulta. Estas señales pueden tener distintas causas y no permiten identificar una falla a distancia. No reemplaces una protección por otra de mayor capacidad ni la anules para evitar que se desconecte.

Si hay una señal de peligro inmediato

Ante humo, chispas, olor a quemado o una descarga, alejate del sector y evitá tocar equipos, enchufes o tableros. No uses agua ni intentes reparar la instalación. Si hay incendio o una persona en peligro, contactá a los servicios de emergencia de tu zona. Una consulta comercial por WhatsApp no sustituye la atención de una emergencia.

Cómo preparar una consulta sin intervenir

Contá qué observaste, desde cuándo ocurre y si hubo cambios recientes de equipos o reformas. Podés indicar barrio o localidad y tipo de vivienda. No reproduzcas la falla, no retires tapas ni abras el tablero para sacar fotos. JM Eléctric ofrece instalaciones y mantenimiento eléctrico; el alcance de la evaluación y la cobertura se confirman directamente.

Consultar con JM Eléctric

Atención en CABA y alrededores. Consultá la cobertura y el alcance para tu caso.

Consultar por WhatsApp

↗


## Revisión de diseño y disponibilidad

Referencia consultada: `TuWebEnTresDias/techos-sanabria`, guía de filtraciones y `blogs/guides.css`. Se adapta la estructura editorial a la identidad de JM; no se copian analítica, contactos ni fotografías de otro negocio. La portada reutiliza la imagen de climatización ya publicada por JM. Primer artículo con portada, índice, resumen, desarrollo, comparación, checklist, seguridad y FAQ. Tres temas reservados con aviso noindex y sin enlaces ni sitemap. Ningún artículo está publicado por esta sesión.

### Verificación posterior al rediseño — 23/10/2026

Sustituye el estado de disponibilidad y sitemap de la primera verificación: ahora hay tres URLs en sitemap (home, índice y primera guía). Chromium local comprobó las seis rutas a 1440, 768, 680, 390 y 320 px: imágenes, ausencia de desbordes y menú móvil. Se comprobaron cinco destinos del índice de la guía y apertura/cierre de sus cuatro preguntas frecuentes. Capturas locales del nuevo diseño revisadas. Las tres tarjetas reservadas no contienen enlaces; las rutas antiguas muestran solo el aviso noindex. Los tres borradores completos están conservados en este documento. Head/scripts originales de la home, script.js, style.css y CNAME permanecen intactos. No se hizo publicación ni verificación del sitio remoto.

## Tarjetas de la landing — referencia visual del usuario

La home y el índice usan tarjetas con imagen superior, categoría y resumen. Fotos existentes de climatización, panel solar y tablero eléctrico. No hay foto verificada de cámaras en los recursos del sitio: la tarjeta usa una portada tipográfica que indica “Imagen pendiente”, sin atribuir una foto ajena al negocio. Las tres próximas notas siguen sin enlaces. El manifiesto de publicación anterior queda obsoleto por estos cambios de diseño; se debe generar uno nuevo antes de publicar.
