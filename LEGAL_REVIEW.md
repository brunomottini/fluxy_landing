# Fluxy V2 — registro de revisión

Actualizado: 28 de octubre de 2026.

El titular informó en esta conversación que su abogado revisó y aprobó los documentos para su publicación. Siguiendo esa instrucción, se retiraron de las dos páginas las marcas de borrador, los avisos de revisión pendiente y las notas editoriales de publicación. Los cambios se preparan para revisión del equipo en la rama `terminos-y-condiciones-V2`, antes de su posterior merge a `main`. No se ha realizado el despliegue.

## Fuentes y contenido

- [Términos V2](https://www.notion.so/4069fcfff05d81b09c97e2033b6ad8f1): se conservan las 20 secciones y su contenido jurídico.
- [Privacidad V2](https://www.notion.so/4069fcfff05d811fae73f1c371b33d90): se conservan las 16 secciones y su contenido jurídico.

No se modificaron las fuentes de Notion ni documentos V1. Se retiraron el RUT y la dirección física precisa de las páginas públicas, conservando BOUREY S.A.S., Fluxy, su constitución en Uruguay, Montevideo, Uruguay, y las cláusulas de legislación y jurisdicción.

Ambas páginas muestran versión 2.0 y la fecha real de actualización, 28 de octubre de 2026. El contacto es `info@fluxy-ai.com`, confirmado por el titular; no se enviaron correos de prueba.

Se mantuvo el contexto de proveedores comunicado por el titular: Microsoft Azure, MongoDB Atlas, OpenAI API, Meta, Google Analytics 4 y Google Ads. TikTok se identifica como una integración prevista, todavía no habilitada en producción. La lista se presenta como proveedores identificados en la arquitectura, sin afirmar que constituye un inventario exhaustivo de subencargados.

Los criterios de conservación siguen basados en las finalidades originales; no se añadieron plazos concretos ni garantías nuevas sobre eliminación. La sección de seguridad mantiene obligaciones de adoptar medidas proporcionales, sin afirmar certificaciones ni configuraciones no verificadas. La sección de cookies refleja la presencia real de GA4 y Google Ads y la ausencia de controles de consentimiento en el código actual de la landing. Las páginas legales no incorporan estas etiquetas.

## Seguimiento operativo separado de la publicación aprobada

Estos asuntos continúan registrados para seguimiento porque la aprobación comunicada no proporciona evidencia técnica adicional sobre la configuración de producción. No se han rellenado con datos inventados.

- Inventario exhaustivo de proveedores/subencargados: entidades, funciones, datos tratados, contratos, políticas y configuraciones efectivas.
- Regiones de alojamiento y procesamiento, destinos y destinatarios de transferencias, bases jurídicas, salvaguardas contractuales y registros aplicables ante la URCDP.
- Criterios o períodos efectivos de conservación para mensajes, documentos, cuentas, leads, logs, trazas de IA, respaldos y registros contables; comportamiento real de devolución y eliminación.
- Contratos y ajustes de los proveedores de IA sobre retención, tratamiento y uso de datos.
- Controles de seguridad y procedimientos de incidentes implementados en producción.
- Auditoría de cookies, píxeles, almacenamiento y recursos externos en landing y plataforma, incluyendo Google Fonts; duraciones y ajustes de las cuentas de analítica. La landing carga GA4 (`G-23Y5TBLYTM`) y Google Ads (`AW-17725808040`) sin un mecanismo de consentimiento/configuración en su código actual. Cualquier cambio en estos controles queda fuera de este trabajo.
- Correspondencia de los flujos efectivos de aceptación, prueba gratuita, cobro, renovación, cancelación, revocación de permisos y atención de derechos con los documentos.
- Omisión del domicilio preciso: la preocupación de revisión jurídica relativa al [artículo 13(B) de la Ley 18.331](https://www.impo.com.uy/bases/leyes/18331-2008/13), que requiere informar identidad y domicilio del responsable, queda documentada. Se registra la aprobación del abogado comunicada por el titular; este trabajo no evalúa de forma independiente su conclusión ni garantiza cumplimiento legal o aprobación de TikTok.

## Validación técnica

- Se conservan las 20 y 16 secciones, respectivamente; no quedan marcas de borrador, notas editoriales ni placeholders en el HTML público.
- No aparecen RUT ni dirección precisa en las páginas legales.
- Las dos páginas tienen HTML semántico, versión, fecha de actualización, canonical, enlaces recíprocos y vuelta a la landing. No requieren JavaScript ni autenticación.
- El footer de la landing contiene exactamente dos enlaces legales discretos. Se conservan la landing, sus scripts, GA4/Google Ads y las cadenas de validación del workflow, salvo la incorporación de esa fila y su CSS.
- La validación inicial incluyó Chrome a 320, 375, 768 y 1440 píxeles con JavaScript deshabilitado, enlaces y recursos locales sin redirecciones, foco visible, contraste del footer de 5,67:1 y apertura/cierre del menú móvil sin excepciones de JavaScript. La revisión final comprueba los diseños después de retirar los avisos, junto con la ausencia de placeholders y la integridad de las secciones y enlaces.
- No se agregaron dependencias ni tests automatizados al repositorio. El workflow de GitHub Pages no cambió.

El workflow existente publica al hacer push a `main`. Una vez desplegado, corresponde verificar las URL HTTPS de producción y su contenido. Los resultados locales no constituyen una comprobación de disponibilidad en producción.
