# Acciones afirmativas en la normativa electoral del Legislativo

Bienvenidos/as al repositorio GitHub de la base de datos "Acciones afirmativas en la normativa electoral del Legislativo" mantenida por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)

## Resumen

La base de datos contiene información descriptiva para conocer la manera en que los países en América Latina implementan acciones afirmativas que permitan la integración de grupos históricamente excluidos en escenarios electorales, por medio de la regulación de estas acciones en la normativa electoral del legislativo.

La recolección de información se realizó consultando la legislación de cada país en América Latina sobre acciones afirmativas en la postulación de candidaturas. Estas acciones afirmativas en la normativa electoral del legislativo se refieren a características normativas nacionales que establecen medidas para que la población históricamente excluida de la representación política pueda acceder a cargos de elección popular.

La revisión toma como base el inicio de la tercera ola de democracia en América Latina (Huntington, 1991).

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. Las personas responsables de la recopilación de los datos son Mauricio Lozano Massés (Facultad de Ciencias Políticas y Sociales, UNAM), Yazmin Patricia Noris Contreras (Facultad de Estudios Superiores Acatlán, UNAM) y Arturo Peralta Oliver (Facultad de Estudios Superiores Aragón, UNAM). Mientras que la persona responsable de la codificación es Josué Godoy Jiménez (Facultad de Ciencias Políticas y Sociales, UNAM).

Producto elaborado en el marco del Proyecto IN302122. Proyecto: “La capacidad de resiliencia de las democracias: elecciones y política en contexto de pandemia”, del Programa de Apoyo a Proyectos de Investigación en Innovación Tecnológica de la UNAM- DGAPA, bajo la dirección de. Flavia Freidenberg (IIJ-UNAM).


## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_Acciones_Afirmativas` en el cual se encuentra toda la información relevante respecto a la base de datos de implementación de acciones afirmativas en la normativa electoral del legislativo. En específico, la base de datos se compone de las siguientes variables:

-   `país`: nombre del país en el cual se llevó a cabo la reforma sobre las acciones afirmativas en la normativa electoral del legislativo.

-   `cowcode`: código del país de acuerdo con la codificación de “Correlates of War”.
https://correlatesofwar.org/data-sets/cow-country-codes.

-   `siglas_pais`: siglas del país de acuerdo con el código de tres letras ISO (por ejemplo: ARG, MEX, SAL) http://utils.mucattu.com/iso_3166-1.html

-   `año_reforma`: año calendario al que corresponde la reforma en la que se estableció la acción afirmativa en la normativa electoral del legislativo (1991-2020).

-   `consec_reforma_pais`: registra el número consecutivo de reformas a las acciones afirmativas en la normativa electoral en cada país de América Latina para cargos de elección en el legislativo nacional. Ejemplo: Perú_1, Perú_2, Perú_3, Perú_4.

-   `norma`: indica el rango legal de la normatividad donde se establecen las acciones afirmativas. Sus valores: No existe [0], no hay un marco legal o acuerdos emitidos por las autoridades administrativas o jurisdiccionales en materia electoral que regulen las acciones afirmativas; Sentencia [1], las acciones afirmativas están reguladas en sentencias emitidas por las autoridades jurisdiccionales en materia electoral; Acuerdo [2], las acciones afirmativas están reguladas en acuerdos emitidos por las autoridades administrativas en materia electoral; Ley [3], las acciones afirmativas están reguladas en leyes electorales o en la materia; Constitución [4], las acciones afirmativas están reguladas a nivel constitucional.

-   `cb_mujer`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de mujeres para ocupar un escaño en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_mujer_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de las mujeres a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_mujer_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de las mujeres a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_mujer_escaño`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de las mujeres a la cámara baja.

-   `cb_juventud`: registra la existencia o inexistencia en la legislación correspondiente de acciones afirmativas que sean aplicadas a las candidaturas de personas jóvenes para ocupar un escaño en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_juventud_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas jóvenes a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_juventud_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas jóvenes a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_juventud_escaño`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de personas jóvenes a la cámara baja.

-   `cb_indigena`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas indígenas para ocupar un escaño en la cámara baja de un país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_indigena_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas indígenas a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_indigena_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas indígenas a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_indigena_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas indígenas a la cámara baja.

-   `cb_afrodescendiente`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas afrodescendientes para ocupar un escaño en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_afrodescendiente_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas afrodescendientes a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_afrodescendiente_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas afrodescendientes a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_afrodescendiente_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas afrodescendientes a la cámara baja.

-   `cb_LGBTIQ`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que garanticen la presencia de personas pertenecientes a la comunidad LGBTQI+ en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_LGBTIQ_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ en la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_LGBTIQ_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_LGBTIQ_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de la comunidad LGBTIQ+ a la cámara baja.

-   `cb_exterior`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas residentes en el exterior para ocupar un escaño en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_exterior_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas residentes en el exterior a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_exterior_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas residentes en el exterior a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_exterior_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas residentes en el exterior a la cámara baja.

-   `cb_discapacidad`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas con discapacidad para ocupar un escaño en la cámara baja de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_discapacidad_obligatorio`:indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas con discapacidad a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_discapacidad_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas con discapacidad a la cámara baja. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cb_discapacidad_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas con discapacidad a la cámara baja.

-   `ca_mujer`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de mujeres para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_mujer_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de las mujeres en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_mujer_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de las mujeres en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_mujer_escaño`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de las mujeres en el Senado (cámara alta) de algún país.

-   `ca_juventud`: registra la existencia o inexistencia en la legislación correspondiente de acciones afirmativas que sean aplicadas a las candidaturas de personas jóvenes para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_juventud_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas jóvenes en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_juventud_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas jóvenes en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_juventud_escaño`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de personas jóvenes en el Senado (cámara alta) de algún país.

-   `ca_indigena`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas indígenas para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_indigena_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas indígenas en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_indigena_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas indígenas en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_indigena_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas indígenas en el Senado (cámara alta) de algún país.

-   `ca_afrodescendiente`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas afrodescendientes para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_afrodescendiente_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas afrodescendientes en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_afrodescendiente_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas afrodescendientes en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_afrodescendiente_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas afrodescendiente en el Senado (cámara alta) de algún país.

-   `ca_LGBTIQ`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que garanticen la presencia de personas pertenecientes a la comunidad LGBTQI+ en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_LGBTIQ_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_LGBTIQ_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_LGBTIQ_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de la comunidad LGBTIQ+ en el Senado (cámara alta) de algún país.

-   `ca_exterior`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas residentes en el exterior para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_exterior_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas residentes en el exterior en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_exterior_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas residentes en el exterior en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_exterior_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas residentes en el exterior en el Senado (cámara alta) de algún país.

-   `ca_discapacidad`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas con discapacidad para ocupar un escaño en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_discapacidad_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas con discapacidad en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_discapacidad_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas con discapacidad en el Senado (cámara alta) de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `ca_discapacidad_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas con discapacidad en el Senado (cámara alta) de algún país.

-   `cu_mujer`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de mujeres para ocupar un escaño en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_mujer_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de las mujeres a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_mujer_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de las mujeres a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_mujer_escaño`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de las mujeres a la cámara única.

-   `cu_juventud`: registra la existencia o inexistencia en la legislación correspondiente de acciones afirmativas que sean aplicadas a las candidaturas de personas jóvenes para ocupar un escaño en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_juventud_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas jóvenes a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_juventud_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas jóvenes a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_juventud_porcentaje`: indica el porcentaje de escaños de las acciones afirmativas aplicadas a las candidaturas de personas jóvenes a la cámara única.

-   `cu_indigena`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas indígenas para ocupar un escaño en la cámara única de un país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_indigena_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas indígenas a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_indigena_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas indígenas a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_indigena_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas indígenas a la cámara única.

-   `cu_afrodescendiente`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas afrodescendientes para ocupar un escaño en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_afrodescendiente_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas afrodescendientes a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_afrodescendiente_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas afrodescendientes a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_afrodescendiente_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas afrodescendientes a la cámara única.

-   `cu_LGBTIQ`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que garanticen la presencia de personas pertenecientes a la comunidad LGBTQI+ en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_LGBTIQ_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ en la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_LGBTIQ_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas pertenecientes a la comunidad LGBTIQ+ a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_LGBTIQ_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de la comunidad LGBTIQ+ a la cámara única.

-   `cu_exterior`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas residentes en el exterior para ocupar un escaño en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_exterior_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas residentes en el exterior a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_exterior_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas residentes en el exterior a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_exterior_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas residentes en el exterior a la cámara única.

-   `cu_discapacidad`: registra la existencia o inexistencia en la legislación correspondiente, de acciones afirmativas que sean aplicadas a las candidaturas de personas con discapacidad para ocupar un escaño en la cámara única de algún país. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_discapacidad_obligatorio`: indica la existencia o inexistencia de obligatoriedad de las acciones afirmativas para las candidaturas de personas con discapacidad a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_discapacidad_porcentaje`: indica la existencia o inexistencia de porcentajes en las acciones afirmativas implementadas en las candidaturas de personas con discapacidad a la cámara única. Es una variable dicotómica cuyos valores son [0] no existe y [1] sí existe.

-   `cu_discapacidad_escaño`: indica el porcentaje de escaños de acciones afirmativas aplicadas a las candidaturas de personas con discapacidad a la cámara única.

## Citado

``` r
Freidenberg, Flavia. Dir., 2023, “Acciones afirmativas en la normativa electoral del legislativo”, DOI: 10.5281/zenodo.7853670. Observatorio de Reformas Políticas en América Latina (1978-2023). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría de Fortalecimiento para la Democracia de la Organización de los Estados Americanos (SFD/OEA), V1. Disponible en: https://bit.ly/3T2v3eC
```