# Querétaro: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Querétaro, Mexico, which global-law reads at `mexico/queretaro/acts/`.

The law of the State of Querétaro (Estado Libre y Soberano de Querétaro, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-que/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

152 ordenamientos with 1159 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE QUERETARO -- ANTES CONSTITUCION POLITICA DEL ESTADO DE QUERETARO -- ANTES CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE QUERETARO -- | 112 | as first published, then each reform: 25 September 1917 to 16 July 2026 |
| `codigo-ambiental/` | CODIGO AMBIENTAL DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 4 December 2021 to 1 January 2024 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE QUERETARO | 41 | as first published, then each reform: 22 October 2009 to 8 March 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE QUERETARO | 18 | as first published, then each reform: 22 October 2009 to 21 September 2024 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE QUERETARO | 19 | as first published, then each reform: 22 July 2014 to 1 January 2026 |
| `codigo-municipal-de-queretaro/` | CODIGO MUNICIPAL DE QUERETARO | 31 | oldest version available, then each reform: 7 June 1999 to 7 June 2025 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE QUERETARO | 96 | as first published, then each reform: 22 August 1987 to 28 February 2026 |
| `codigo-urbano/` | CODIGO URBANO DEL ESTADO DE QUERETARO | 23 | as first published, then each reform: 1 June 2012 to 18 November 2023 |
| `ley-de-adquisiciones-enajenaciones-arrendamientos-y-contrata/` | LEY DE ADQUISICIONES, ENAJENACIONES, ARRENDAMIENTOS Y CONTRATACION DE SERVICIOS DEL ESTADO DE QUERETARO | 24 | as first published, then each reform: 27 June 2009 to 1 January 2025 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE QUERETARO | 5 | as first published, then each reform: 25 July 2009 to 1 January 2020 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE QUERETARO | 6 | as first published, then each reform: 19 September 2015 to 21 May 2022 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE QUERETARO | 8 | as first published, then each reform: 1 February 2018 to 31 December 2025 |
| `ley-de-catastro/` | LEY DE CATASTRO PARA EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 1 January 2022 to 21 September 2024 |
| `ley-de-coordinacion-fiscal-estatal-intermunicipal/` | LEY DE COORDINACION FISCAL ESTATAL INTERMUNICIPAL DEL ESTADO DE QUERETARO | 13 | as first published, then each reform: 14 December 2008 to 1 January 2026 |
| `ley-de-derechos-humanos/` | LEY DE DERECHOS HUMANOS DEL ESTADO DE QUERETARO | 7 | as first published, then each reform: 4 September 2015 to 19 October 2024 |
| `ley-de-derechos-y-cultura-de-los-pueblos-y-comunidades-indig/` | LEY DE DERECHOS Y CULTURA DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE QUERETARO | 8 | as first published, then each reform: 25 July 2009 to 19 October 2019 |
| `ley-de-desarrollo-pecuario/` | LEY DE DESARROLLO PECUARIO DEL ESTADO DE QUERETARO | 5 | as first published, then each reform: 25 July 2009 to 8 October 2021 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE QUERETARO | 11 | as first published, then each reform: 1 October 2015 to 1 January 2025 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE QUERETARO | 14 | as first published, then each reform: 21 March 2009 to 1 July 2023 |
| `ley-de-donacion-y-trasplantes-de-organos-tejidos-y-celulas-h/` | LEY DE DONACION Y TRASPLANTES DE ORGANOS, TEJIDOS Y CELULAS HUMANAS DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 26 February 2012 to 8 October 2021 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE QUERETARO | 23 | as first published, then each reform: 1 August 2009 to 4 March 2023 |
| `ley-de-ejecucion-de-penas-y-medidas-de-seguridad/` | LEY DE EJECUCION DE PENAS Y MEDIDAS DE SEGURIDAD DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 24 October 2009 to 13 June 2013 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA RECEPCION DEL ESTADO DE QUERETARO | 1 | as first published: 21 March 2009 |
| `ley-de-estacionamientos-publicos-y-servicios-de-recepcion-y/` | LEY DE ESTACIONAMIENTOS PUBLICOS Y SERVICIOS DE RECEPCION Y DEPOSITO DE VEHICULOS PARA EL ESTADO DE QUERETARO | 1 | as first published: 9 February 2012 |
| `ley-de-estimulos-civiles/` | LEY DE ESTIMULOS CIVILES DEL ESTADO DE QUERETARO | 2 | as first published, then each reform: 29 November 1985 to 15 May 2010 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 25 July 2009 to 21 September 2024 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE QUERETARO | 6 | as first published, then each reform: 8 January 2022 to 1 January 2026 |
| `ley-de-fiscalizacion-superior-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE QUERETARO | 1 | as first published: 17 September 2022 |
| `ley-de-fomento-a-la-actividad-artesanal-en-el-estado-de-quer/` | LEY DE FOMENTO A LA ACTIVIDAD ARTESANAL EN EL ESTADO DE QUERETARO | 4 | as first published, then each reform: 17 December 2004 to 8 October 2021 |
| `ley-de-fomento-a-las-organizaciones-de-la-sociedad-civil/` | LEY DE FOMENTO A LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE QUERETARO | 1 | as first published: 3 May 2022 |
| `ley-de-fomento-apicola-y-proteccion-del-proceso-de-polinizac/` | LEY DE FOMENTO APICOLA Y PROTECCION DEL PROCESO DE POLINIZACION EN EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 12 May 2018 to 8 October 2021 |
| `ley-de-fundos-legales/` | LEY DE FUNDOS LEGALES DEL ESTADO DE QUERETARO | 1 | as first published: 18 June 2009 |
| `ley-de-gobierno-digital/` | LEY DE GOBIERNO DIGITAL DEL ESTADO DE QUERETARO | 2 | as first published, then each reform: 21 May 2022 to 28 January 2023 |
| `ley-de-hacienda-de-los-municipios/` | LEY DE HACIENDA DE LOS MUNICIPIOS DEL ESTADO DE QUERETARO | 11 | as first published, then each reform: 18 October 2013 to 21 September 2024 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE QUERETARO | 26 | as first published, then each reform: 22 July 2014 to 1 January 2026 |
| `ley-de-igualdad-sustantiva-entre-mujeres-y-hombres/` | LEY DE IGUALDAD SUSTANTIVA ENTRE MUJERES Y HOMBRES DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 31 August 2012 to 1 January 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE QUERETARO PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-colon-qro-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE COLON, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-corregidora-qro-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE CORREGIDORA, QRO. PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-jalpan-de-serra-qro-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE JALPAN DE SERRA, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-landa-de-matamoros-qro-para/` | LEY DE INGRESOS DEL MUNICIPIO DE LANDA DE MATAMOROS, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-pedro-escobedo-qro-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE PEDRO ESCOBEDO, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-penamiller-qro-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE PEÑAMILLER, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-pinal-de-amoles-qro-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE PINAL DE AMOLES, QRO., PARA EL EJERCICIO FISCAL 2026. | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-queretaro-qro-para-el-ejerc/` | LEY DE INGRESOS DEL MUNICIPIO DE QUERÉTARO, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-joaquin-qro-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JOAQUIN, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-juan-del-rio-qro-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JUAN DEL RÍO, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-tequisquiapan-qro-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE TEQUISQUIAPAN, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-toliman-qro-para-el-ejercic/` | LEY DE INGRESOS DEL MUNICIPIO DE TOLIMAN, QRO., PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-de-asistencia-privada/` | LEY DE INSTITUCIONES DE ASISTENCIA PRIVADA DEL ESTADO DE QUERETARO | 9 | as first published, then each reform: 25 July 2009 to 28 September 2024 |
| `ley-de-juicio-politico/` | LEY DE JUICIO POLITICO DEL ESTADO DE QUERETARO | 1 | as first published: 4 October 2018 |
| `ley-de-justicia-constitucional/` | LEY DE JUSTICIA CONSTITUCIONAL DEL ESTADO DE QUERETARO | 2 | as first published, then each reform: 26 April 2009 to 26 November 2011 |
| `ley-de-la-administracion-publica-paraestatal/` | LEY DE LA ADMINISTRACION PUBLICA PARAESTATAL DEL ESTADO DE QUERETARO | 19 | as first published, then each reform: 18 June 2009 to 1 January 2024 |
| `ley-de-la-agencia-de-movilidad-y-modalidades-de-transporte-p/` | LEY DE LA AGENCIA DE MOVILIDAD Y MODALIDADES DE TRANSPORTE PUBLICO PARA EL ESTADO DE QUERETARO -- ANTES LEY DE MOVILIDAD PARA EL TRANSPORTE DEL ESTADO DE QUERETARO -- | 17 | as first published, then each reform: 2 May 2012 to 31 December 2025 |
| `ley-de-la-secretaria-de-las-mujeres-antes-ley-del-instituto/` | LEY DE LA SECRETARIA DE LAS MUJERES -- ANTES LEY DEL INSTITUTO QUERETANO DE LAS MUJERES -- | 2 | as first published, then each reform: 25 November 2023 to 1 January 2025 |
| `ley-de-la-secretaria-de-seguridad-ciudadana/` | LEY DE LA SECRETARIA DE SEGURIDAD CIUDADANA DEL ESTADO DE QUERETARO | 9 | as first published, then each reform: 11 June 2016 to 28 February 2026 |
| `ley-de-la-unidad-de-medida-y-actualizacion/` | LEY DE LA UNIDAD DE MEDIDA Y ACTUALIZACION DEL ESTADO DE QUERETARO -- ANTES LEY DEL FACTOR DE CALCULO -- | 3 | as first published, then each reform: 1 January 2016 to 1 September 2017 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores-antes-le/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES -- ANTES LEY DE LAS PERSONAS ADULTAS MAYORES -- DEL ESTADO DE QUERETARO | 6 | as first published, then each reform: 18 December 2008 to 3 June 2021 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE QUERETARO | 12 | as first published, then each reform: 2 November 2015 to 21 February 2026 |
| `ley-de-los-trabajadores/` | LEY DE LOS TRABAJADORES DEL ESTADO DE QUERETARO | 20 | as first published, then each reform: 21 March 2009 to 6 May 2026 |
| `ley-de-medios-de-impugnacion-en-materia-electoral/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL DEL ESTADO DE QUERETARO | 1 | as first published: 1 June 2020 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA DEL ESTADO DE QUERETARO | 1 | as first published: 30 November 2022 |
| `ley-de-obra-publica/` | LEY DE OBRA PUBLICA DEL ESTADO DE QUERETARO | 20 | as first published, then each reform: 13 November 2003 to 30 November 2022 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE QUERETARO | 2 | as first published, then each reform: 15 February 2025 to 21 February 2025 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE QUERETARO | 11 | as first published, then each reform: 18 December 2008 to 14 December 2021 |
| `ley-de-procedimiento-contencioso-administrativo/` | LEY DE PROCEDIMIENTO CONTENCIOSO ADMINISTRATIVO DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 18 July 2017 to 8 October 2021 |
| `ley-de-procedimientos-administrativos/` | LEY DE PROCEDIMIENTOS ADMINISTRATIVOS DEL ESTADO DE QUERETARO | 8 | as first published, then each reform: 28 February 2009 to 1 January 2024 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 4 August 2009 to 8 October 2021 |
| `ley-de-proteccion-a-victimas-y-personas-que-intervienen-en-e/` | LEY DE PROTECCION A VICTIMAS Y PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL DEL ESTADO DE QUERETARO -- ANTES LEY DE PROTECCION A VICTIMAS, OFENDIDOS Y PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL -- | 5 | as first published, then each reform: 21 March 2014 to 1 January 2025 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 27 January 2018 to 8 October 2021 |
| `ley-de-publicaciones-oficiales/` | LEY DE PUBLICACIONES OFICIALES DEL ESTADO DE QUERETARO | 1 | as first published: 15 November 2009 |
| `ley-de-respeto-vecinal/` | LEY DE RESPETO VECINAL PARA EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 9 November 2012 to 11 June 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE QUERETARO | 1 | as first published: 4 August 2009 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 21 April 2017 to 8 October 2021 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE QUERETARO | 25 | as first published, then each reform: 31 January 2010 to 9 May 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE QUERETARO | 1 | as first published: 21 December 2017 |
| `ley-de-seguridad/` | LEY DE SEGURIDAD PARA EL ESTADO DE QUERETARO | 11 | as first published, then each reform: 31 May 2016 to 24 February 2026 |
| `ley-de-servicios-auxiliares-del-transporte-publico/` | LEY DE SERVICIOS AUXILIARES DEL TRANSPORTE PUBLICO DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 23 January 2012 to 6 January 2023 |
| `ley-de-transito/` | LEY DE TRANSITO PARA EL ESTADO DE QUERETARO | 5 | as first published, then each reform: 14 October 2017 to 31 December 2025 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE QUERETARO | 7 | as first published, then each reform: 1 February 2016 to 8 October 2021 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE QUERETARO | 12 | as first published, then each reform: 1 August 2009 to 25 November 2023 |
| `ley-de-valuacion-inmobiliaria/` | LEY DE VALUACION INMOBILIARIA PARA EL ESTADO DE QUERETARO | 4 | as first published, then each reform: 18 March 2017 to 21 September 2024 |
| `ley-del-centro-de-capacitacion-formacion-e-investigacion-par/` | LEY DEL CENTRO DE CAPACITACION, FORMACION E INVESTIGACION PARA LA SEGURIDAD DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 29 November 2017 to 8 October 2021 |
| `ley-del-centro-de-prevencion-social-del-delito-y-la-violenci/` | LEY DEL CENTRO DE PREVENCION SOCIAL DEL DELITO Y LA VIOLENCIA EN EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 11 June 2022 to 28 September 2024 |
| `ley-del-deporte/` | LEY DEL DEPORTE DEL ESTADO DE QUERETARO | 11 | as first published, then each reform: 27 June 2009 to 9 May 2026 |
| `ley-del-escudo-la-bandera-y-el-himno/` | LEY DEL ESCUDO, LA BANDERA Y EL HIMNO DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 22 September 2015 to 8 October 2021 |
| `ley-del-instituto-de-la-defensoria-penal-publica/` | LEY DEL INSTITUTO DE LA DEFENSORIA PENAL PUBLICA DEL ESTADO DE QUERETARO | 1 | as first published: 31 May 2016 |
| `ley-del-instituto-registral-y-catastral/` | LEY DEL INSTITUTO REGISTRAL Y CATASTRAL DEL ESTADO DE QUERETARO | 2 | as first published, then each reform: 23 March 2024 to 21 September 2024 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE QUERETARO | 10 | as first published, then each reform: 27 June 2009 to 21 September 2024 |
| `ley-del-sistema-de-asistencia-social/` | LEY DEL SISTEMA DE ASISTENCIA SOCIAL DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 18 December 2008 to 3 June 2021 |
| `ley-del-sistema-de-servicio-profesional-de-carrera-del-poder/` | LEY DEL SISTEMA DE SERVICIO PROFESIONAL DE CARRERA DEL PODER LEGISLATIVO DEL ESTADO DE QUERETARO | 1 | as first published: 25 May 2015 |
| `ley-del-sistema-estatal-anticorrupcion/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DEL ESTADO DE QUERETARO | 1 | as first published: 19 April 2017 |
| `ley-del-sistema-estatal-de-proteccion-civil-prevencion-y-mit/` | LEY DEL SISTEMA ESTATAL DE PROTECCION CIVIL, PREVENCION Y MITIGACION DE DESASTRES PARA EL ESTADO DE QUERETARO | 5 | as first published, then each reform: 19 September 2015 to 23 October 2021 |
| `ley-del-sistema-para-el-desarrollo-integral-de-la-familia/` | LEY DEL SISTEMA PARA EL DESARROLLO INTEGRAL DE LA FAMILIA DEL ESTADO DE QUERETARO | 6 | as first published, then each reform: 19 February 2014 to 8 October 2021 |
| `ley-del-voluntariado/` | LEY DEL VOLUNTARIADO DEL ESTADO DE QUERETARO | 1 | as first published: 6 September 2017 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE QUERETARO | 5 | as first published, then each reform: 1 June 2020 to 15 July 2023 |
| `ley-estatal-de-acceso-de-las-mujeres-a-una-vida-libre-de-vio/` | LEY ESTATAL DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA, QUERETARO | 8 | as first published, then each reform: 28 March 2009 to 16 June 2026 |
| `ley-industrial/` | LEY INDUSTRIAL DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 4 April 2009 to 8 March 2023 |
| `ley-numero-1-de-la-xxxii-legislatura/` | LEY NUMERO 1 DE LA XXXII LEGISLATURA DEL ESTADO, PARA FACULTAR AL EJECUTIVO DEL ESTADO EL CONCEDER GRACIA DE INDULTO A REOS DEL ORDEN COMUN, QUERETARO | 1 | as first published: 24 September 1939 |
| `ley-organica-de-la-agencia-de-energia/` | LEY ORGANICA DE LA AGENCIA DE ENERGIA DEL ESTADO DE QUERETARO | 1 | as first published: 1 October 2021 |
| `ley-organica-de-la-escuela-normal/` | LEY ORGANICA DE LA ESCUELA NORMAL DEL ESTADO, QUERETARO | 2 | as first published, then each reform: 27 December 1987 to 28 February 2026 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE QUERETARO | 21 | as first published, then each reform: 30 May 2016 to 24 February 2026 |
| `ley-organica-de-la-universidad-autonoma-de-queretaro/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE QUERETARO | 1 | as first published: 3 January 1986 |
| `ley-organica-de-la-universidad-tecnologica-de-queretaro/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE QUERETARO | 3 | as first published, then each reform: 14 November 2011 to 8 October 2021 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 1 October 2021 to 8 October 2021 |
| `ley-organica-del-colegio-de-bachilleres/` | LEY ORGANICA DEL COLEGIO DE BACHILLERES DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 18 June 2009 to 28 February 2026 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO DEL ESTADO DE QUERETARO | 42 | as first published, then each reform: 18 December 2008 to 1 January 2025 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 30 September 2022 to 20 August 2024 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE QUERETARO | 48 | as first published, then each reform: 4 December 2008 to 21 April 2025 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 19 April 2017 to 8 October 2021 |
| `ley-organica-del-tribunal-electoral/` | LEY ORGANICA DEL TRIBUNAL ELECTORAL DEL ESTADO DE QUERETARO | 5 | as first published, then each reform: 2 July 2014 to 3 July 2020 |
| `ley-organica-municipal/` | LEY ORGANICA MUNICIPAL DEL ESTADO DE QUERETARO -ANTES LEY PARA LA ORGANIZACION POLITICA Y ADMINISTRATIVA DEL MUNICIPIO LIBRE DEL ESTADO DE QUERETARO- | 27 | as first published, then each reform: 1 June 2001 to 28 December 2022 |
| `ley-para-agilizar-los-procedimientos-de-entrega-recepcion-de/` | LEY PARA AGILIZAR LOS PROCEDIMIENTOS DE ENTREGA-RECEPCION DE FRACCIONAMIENTOS EN EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 18 February 2021 to 18 November 2023 |
| `ley-para-el-desarrollo-de-los-jovenes-en-el-estado-de-queret/` | LEY PARA EL DESARROLLO DE LOS JOVENES EN EL ESTADO DE QUERETARO | 16 | as first published, then each reform: 3 March 2012 to 8 March 2023 |
| `ley-para-el-fomento-de-la-investigacion-cientifica-tecnologi/` | LEY PARA EL FOMENTO DE LA INVESTIGACION CIENTIFICA, TECNOLOGICA E INNOVACION DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 31 January 2010 to 17 August 2024 |
| `ley-para-el-manejo-de-los-recursos-publicos/` | LEY PARA EL MANEJO DE LOS RECURSOS PUBLICOS DEL ESTADO DE QUERETARO | 24 | as first published, then each reform: 21 December 2014 to 1 January 2026 |
| `ley-para-la-atencion-de-las-migraciones-en-el-estado-de-quer/` | LEY PARA LA ATENCION DE LAS MIGRACIONES EN EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 31 December 2021 to 1 January 2025 |
| `ley-para-la-cultura-y-las-artes/` | LEY PARA LA CULTURA Y LAS ARTES DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 31 December 2005 to 12 October 2024 |
| `ley-para-la-inclusion-al-desarrollo-social-de-las-personas-c/` | LEY PARA LA INCLUSION AL DESARROLLO SOCIAL DE LAS PERSONAS CON DISCAPACIDAD -- ANTES LEY PARA LA INTEGRACION AL DESARROLLO SOCIAL DE LAS PERSONAS CON DISCAPACIDAD -- DEL ESTADO DE QUERETARO | 10 | as first published, then each reform: 5 November 2011 to 23 February 2026 |
| `ley-para-la-prevencion-gestion-integral-y-economia-circular/` | LEY PARA LA PREVENCION, GESTION INTEGRAL Y ECONOMIA CIRCULAR DE LOS RESIDUOS DEL ESTADO DE QUERETARO | 1 | as first published: 4 December 2021 |
| `ley-para-la-promocion-fomento-y-desarrollo-de-la-industria-c/` | LEY PARA LA PROMOCION, FOMENTO Y DESARROLLO DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 20 July 2013 to 8 October 2021 |
| `ley-para-la-regularizacion-de-asentamientos-humanos-irregula/` | LEY PARA LA REGULARIZACION DE ASENTAMIENTOS HUMANOS IRREGULARES, PREDIOS URBANOS, PREDIOS RUSTICOS, PREDIOS FAMILIARES Y PREDIOS SOCIALES DEL ESTADO DE QUERETARO | 5 | as first published, then each reform: 14 January 2017 to 14 January 2022 |
| `ley-para-la-regularizacion-de-asentamientos-humanos-irregula-2/` | LEY PARA LA REGULARIZACION DE ASENTAMIENTOS HUMANOS IRREGULARES, PREDIOS URBANOS, RUSTICOS Y SOCIALES DEL ESTADO DE QUERETARO | 1 | as first published: 5 August 2023 |
| `ley-para-prevenir-y-eliminar-toda-forma-de-discriminacion-en/` | LEY PARA PREVENIR Y ELIMINAR TODA FORMA DE DISCRIMINACION EN EL ESTADO DE QUERETARO | 3 | as first published, then each reform: 31 August 2012 to 1 January 2025 |
| `ley-para-prevenir-combatir-y-sancionar-la-trata-de-personas/` | LEY PARA PREVENIR, COMBATIR Y SANCIONAR LA TRATA DE PERSONAS EN EL ESTADO DE QUERETARO | 2 | as first published, then each reform: 9 March 2013 to 1 January 2025 |
| `ley-para-prevenir-investigar-sancionar-y-reparar-la-desapari/` | LEY PARA PREVENIR, INVESTIGAR, SANCIONAR Y REPARAR LA DESAPARICION DE PERSONAS EN EL ESTADO DE QUERETARO | 2 | as first published, then each reform: 7 June 2014 to 6 February 2016 |
| `ley-para-regularizar-la-pequena-propiedad-de-predios-rustico/` | LEY PARA REGULARIZAR LA PEQUEÑA PROPIEDAD DE PREDIOS RUSTICOS EN EL ESTADO DE QUERETARO | 2 | as first published, then each reform: 25 June 2012 to 8 November 2012 |
| `ley-por-la-que-se-faculta-al-c-gobernador-constitucional/` | LEY POR LA QUE SE FACULTA AL C. GOBERNADOR CONSTITUCIONAL DEL ESTADO, PARA DECLARAR ZONAS URBANAS EN LA CIUDAD DE QUERETARO | 1 | as first published: 31 December 1967 |
| `ley-por-la-que-se-faculta-al-ejecutivo-local-para-enajenar-l/` | LEY POR LA QUE SE FACULTA AL EJECUTIVO LOCAL PARA ENAJENAR LOS INMUEBLES PROPIEDAD DEL ESTADO, QUERETARO | 1 | as first published: 21 July 1963 |
| `ley-que-aprueba-la-incorporacion/` | LEY QUE APRUEBA LA INCORPORACION DEL ESTADO DE QUERETARO Y SUS MUNICIPIOS A LA COORDINACION EN MATERIA FEDERAL DE DERECHOS | 1 | as first published: 27 December 1984 |
| `ley-que-crea-el-centro-de-evaluacion-y-control-de-confianza/` | LEY QUE CREA EL CENTRO DE EVALUACION Y CONTROL DE CONFIANZA DEL ESTADO DE QUERETARO | 4 | as first published, then each reform: 29 November 2017 to 8 October 2021 |
| `ley-que-crea-el-centro-de-informacion-y-analisis-para-la-seg/` | LEY QUE CREA EL CENTRO DE INFORMACION Y ANALISIS PARA LA SEGURIDAD DE QUERETARO | 6 | as first published, then each reform: 17 August 2018 to 28 September 2024 |
| `ley-que-crea-el-consejo-consultivo/` | LEY QUE CREA EL CONSEJO CONSULTIVO DEL ESTADO DE QUERETARO | 1 | as first published: 28 November 1974 |
| `ley-que-crea-el-instituto-queretano-del-emprendimiento-y-la/` | LEY QUE CREA EL INSTITUTO QUERETANO DEL EMPRENDIMIENTO Y LA INNOVACION | 3 | as first published, then each reform: 10 September 2022 to 1 January 2025 |
| `ley-que-crea-la-comision-estatal-de-infraestructura-de-quere/` | LEY QUE CREA LA COMISION ESTATAL DE INFRAESTRUCTURA DE QUERETARO -- ANTES LEY QUE CREA LA COMISION ESTATAL DE CAMINOS DEL ESTADO DE QUERETARO -- | 6 | as first published, then each reform: 27 December 1985 to 8 October 2021 |
| `ley-que-crea-la-comision-estatal-del-sistema-penitenciario-d/` | LEY QUE CREA LA COMISION ESTATAL DEL SISTEMA PENITENCIARIO DE QUERETARO | 3 | as first published, then each reform: 29 November 2017 to 8 October 2021 |
| `ley-que-crea-la-comision-para-la-evaluacion-de-la-operacion/` | LEY QUE CREA LA COMISION PARA LA EVALUACION DE LA OPERACION DEL SISTEMA DE JUSTICIA PENAL ACUSATORIO DEL ESTADO DE QUERETARO, DENOMINADA "COSMOS" | 5 | as first published, then each reform: 3 October 2018 to 28 September 2024 |
| `ley-que-crea-la-comision-tripartita/` | LEY QUE CREA LA COMISION TRIPARTITA DEL ESTADO DE QUERETARO | 1 | as first published: 18 August 1974 |
| `ley-que-crea-la-direccion-estatal-coordinadora-del-registro/` | LEY QUE CREA LA DIRECCION ESTATAL COORDINADORA DEL REGISTRO CIVIL, PARA EL ESTADO DE QUERETARO, DEPENDIENTE DEL EJECUTIVO A TRAVES DE LA SECRETARIA DE GOBIERNO | 1 | as first published: 2 January 1981 |
| `ley-que-crea-la-escuela-normal-superior-de-queretaro/` | LEY QUE CREA LA ESCUELA NORMAL SUPERIOR DE QUERETARO | 1 | as first published: 9 September 1976 |
| `ley-que-crea-la-orquesta-de-camara-de-queretaro/` | LEY QUE CREA LA ORQUESTA DE CAMARA DE QUERETARO | 1 | as first published: 3 May 1973 |
| `ley-que-establece-el-secreto-profesional-periodistico-en-el/` | LEY QUE ESTABLECE EL SECRETO PROFESIONAL PERIODISTICO EN EL ESTADO DE QUERETARO | 1 | as first published: 7 July 2012 |
| `ley-que-establece-la-obligacion-de-bardear-los-predios-urban/` | LEY QUE ESTABLECE LA OBLIGACION DE BARDEAR LOS PREDIOS URBANOS EN LA CIUDAD DE QUERETARO | 1 | as first published: 7 December 1969 |
| `ley-que-establece-las-bases-para-la-prevencion-y-la-atencion/` | LEY QUE ESTABLECE LAS BASES PARA LA PREVENCION Y LA ATENCION DE LA VIOLENCIA FAMILIAR EN EL ESTADO DE QUERETARO | 2 | as first published, then each reform: 18 December 2008 to 1 January 2025 |
| `ley-que-establece-los-limites-urbanos/` | LEY QUE ESTABLECE LOS LIMITES URBANOS DE LA CIUDAD DE SAN JUAN DEL RIO, QUERETARO | 1 | as first published: 18 October 1979 |
| `ley-que-fija-el-arancel-para-el-cobro-de-honorarios-de-aboga/` | LEY QUE FIJA EL ARANCEL PARA EL COBRO DE HONORARIOS DE ABOGADOS EN EL ESTADO DE QUERETARO | 1 | as first published: 6 October 2011 |
| `ley-que-fija-el-arancel-para-el-cobro-de-honorarios-profesio/` | LEY QUE FIJA EL ARANCEL PARA EL COBRO DE HONORARIOS PROFESIONALES DE LOS ARQUITECTOS EN EL ESTADO DE QUERETARO ARTEAGA | 1 | as first published: 6 May 2006 |
| `ley-que-fija-las-bases-montos-y-plazos-conforme-a-los-cuales/` | LEY QUE FIJA LAS BASES, MONTOS Y PLAZOS CONFORME A LOS CUALES SE DISTRIBUIRAN LAS PARTICIPACIONES FEDERALES CORRESPONDIENTES A LOS MUNICIPIOS DEL ESTADO DE QUERETARO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-que-prorroga-los-contratos-de-arrendamiento-de-bienes-in/` | LEY QUE PRORROGA LOS CONTRATOS DE ARRENDAMIENTO DE BIENES INMUBLES EN EL ESTADO, QUERETARO | 1 | as first published: 10 October 1982 |
| `ley-que-regula-a-los-agentes-y-empresas-inmobiliarias-en-el/` | LEY QUE REGULA A LOS AGENTES Y EMPRESAS INMOBILIARIAS EN EL ESTADO DE QUERETARO | 1 | as first published: 1 January 2017 |
| `ley-que-regula-el-sistema-estatal-de-promocion-del-uso-de-la/` | LEY QUE REGULA EL SISTEMA ESTATAL DE PROMOCION DEL USO DE LA BICICLETA, EN EL ESTADO DE QUERETARO | 1 | as first published: 23 July 2011 |
| `ley-que-regula-la-prestacion-de-los-servicios-de-agua-potabl/` | LEY QUE REGULA LA PRESTACION DE LOS SERVICIOS DE AGUA POTABLE, ALCANTARILLADO Y SANEAMIENTO DEL ESTADO DE QUERETARO | 3 | as first published, then each reform: 24 May 2022 to 2 May 2025 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
