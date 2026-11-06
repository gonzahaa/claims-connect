# Claims Connect

## Propósito

Definir un proceso centralizado y auditable para intercambiar documentación de
reclamos con aseguradoras y asesores externos. El repositorio debe evitar los
envíos repetidos de archivos grandes por correo y permitir demostrar qué
documentos estuvieron disponibles, para quién y durante qué período.

Este repositorio documenta los requisitos del proceso; todavía no aprovisiona
un sitio, cuentas de invitados ni permisos en Microsoft 365.

## Flujo requerido

1. La operación crea un reclamo e incorpora los documentos necesarios.
2. El equipo corporativo revisa los documentos antes de compartirlos.
3. Un responsable habilita al revisor externo únicamente para los documentos
   de ese reclamo y por un período aprobado.
4. Se notifica al destinatario la ubicación de los documentos. Se conserva
   evidencia de la publicación y de la notificación, sin depender del correo
   como medio de almacenamiento.
5. Se registra la actividad documental disponible, como visualizaciones,
   cambios y metadatos.
6. Al cerrarse el reclamo y completarse el pago, se retira el acceso y se
   solicita la baja de la cuenta de invitado conforme al proceso corporativo.

Los reclamos pueden permanecer abiertos hasta aproximadamente 18 meses. La
vigencia debe definirse para cada invitado y revisarse si el reclamo sigue
abierto; las fechas de ejemplo no constituyen una vigencia predeterminada.

## Acceso y gobernanza

- Los usuarios externos necesitan una cuenta de invitado aprobada antes de
  acceder a SharePoint o Teams. La solicitud debe incluir nombre completo,
  departamento, sector y los datos de identificación requeridos para su país.
- La solicitud se tramita por el hub corporativo y la aprueba el equipo
  responsable. Se debe confirmar si la gestión corresponde a soporte local o
  a Collaboration and Communication.
- Los revisores de aseguradoras solo pueden acceder al reclamo que tienen
  asignado; no deben poder explorar la biblioteca corporativa ni otros casos.
- Los asesores externos permanentes pueden tener un alcance mayor solo cuando
  haya sido aprobado expresamente y limitado a la información que necesitan.
- Los permisos deben permitir retirar el acceso de un reclamo sin afectar
  otros reclamos. La edición y descarga se restringen según las necesidades
  del caso y las capacidades disponibles en Microsoft 365.
- Las identidades, aprobaciones, períodos de acceso, cambios de permisos,
  notificaciones y acciones de baja deben quedar sujetos a los controles de
  auditoría corporativos.
- El proceso debe servir para reclamos de toda Latinoamérica. Los requisitos
  de identidad y aprobación pueden variar según el país.

## Estructura por validar

La opción base es un sitio SharePoint dedicado a reclamos, con separación de
acceso por caso. Antes de invitar a externos se debe validar que la estructura
elegida (por ejemplo, bibliotecas o espacios separados por reclamo) mantenga
el aislamiento y facilite retirar permisos sin exponer otros casos.

Como alternativa, se puede usar un equipo de Teams con un canal privado o
compartido por reclamo. Debe confirmarse que los usuarios externos solo puedan
ver el canal y los archivos de su caso, y verificar las condiciones vigentes
de Microsoft para colaboración externa. La decisión entre SharePoint y Teams
queda pendiente de esa validación técnica.

No se debe conceder acceso externo hasta que la estructura y los permisos
hayan sido probados con cuentas de prueba representativas, verificando tanto
el acceso autorizado como la denegación de acceso a otros reclamos.
