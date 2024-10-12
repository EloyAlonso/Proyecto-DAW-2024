# Anteproyecto fin de ciclo

- [Anteproyecto fin de ciclo](#anteproyecto-fin-de-ciclo)
  - [1- Descripción del proyecto](#1--descripción-del-proyecto)
  - [2- Empresa](#2--empresa)
    - [2.1- Idea de negocio](#21--idea-de-negocio)
    - [2.2- Justificación de la idea](#22--justificación-de-la-idea)
    - [2.3- Segmento de clientes](#23--segmento-de-clientes)
    - [2.4- Competencia](#24--competencia)
    - [2.5- Propuesta de valor](#25--propuesta-de-valor)
    - [2.6- Forma jurídica](#26--forma-jurídica)
    - [2.7- Inversiones](#27--inversiones)
      - [2.7.1- Costos](#271--costos)
      - [2.7.2- Ingresos](#272--ingresos)
    - [2.8- Viabilidad](#28--viabilidad)
      - [2.8.1- Viabilidad técnica](#281--viabilidad-técnica)
      - [2.8.2 - Viabilidad económica](#282---viabilidad-económica)
      - [2.8.3- Conclusión](#283--conclusión)
  - [3- Requerimientos técnicos](#3--requerimientos-técnicos)
  - [4- Planificación](#4--planificación)

## 1- Descripción del proyecto

El proyecto consiste en crear una plataforma de comercio online para la venta directa de productos agrícolas, dirigida específicamente a los agricultores en España. El objetivo principal es ofrecer un espacio donde los agricultores puedan vender sus productos sin la intervención de grandes empresas, lo que les permitirá obtener precios justos por sus cosechas. Los usuarios podrán comprar directamente de los productores, reduciendo los costos de intermediación. La plataforma estará desarrollada en CakePHP, con un frontend que utiliza Bootstrap, JS, HTML y CSS, para asegurar su funcionalidad y una interfaz accesible.

## 2- Empresa

### 2.1- Idea de negocio

El marketplace facilitará la conexión directa entre los agricultores y los consumidores finales, eliminando a los intermediarios y permitiendo una relación más justa. También ofrecerá funciones de gestión de envíos y pagos dentro de la plataforma.

### 2.2- Justificación de la idea

Los agricultores en España enfrentan problemas relacionados con los bajos márgenes de ganancia debido a la influencia de las grandes corporaciones que controlan la distribución. Este proyecto busca cambiar esa dinámica permitiendo una venta más directa.

#### Ingresos promedio de un agricultor autónomo

Los ingresos de un agricultor autónomo en España varían según el tipo de cultivo, tamaño de la explotación, región y otros factores. A continuación, se presenta un estimado:

1. **Ingresos brutos**:
   - **Cultivos extensivos** (cereales, olivos, viñedos): ingresos anuales brutos de **25.000 a 40.000 euros** para explotaciones medianas.
   - **Cultivos hortícolas intensivos** (hortalizas, frutas): ingresos brutos de **40.000 a 70.000 euros**, especialmente en invernaderos.

2. **Costes de producción**:
   - Los costes pueden representar entre el **60%-80%** de los ingresos brutos. 
   - Por ejemplo, si un agricultor ingresa 40.000 euros, los **gastos operativos** serían de **24.000-32.000 euros**.

3. **Beneficio neto**:
   - El beneficio neto (antes de impuestos) es de aproximadamente **20%-30%** de los ingresos brutos. Esto significa que un agricultor autónomo podría obtener un beneficio de **8.000 a 12.000 euros** al año.
   - En los mejores casos, los agricultores más rentables pueden ganar entre **12.000 y 18.000 euros anuales**.

4. **Subvenciones**:
   - Las subvenciones PAC (Política Agraria Común) son un apoyo financiero **crucial** para los agricultores en España, representando hasta el **30%-40%** de sus ingresos. Estas ayudas son esenciales para cubrir los altos costos de producción y mantener la viabilidad de las explotaciones agrícolas. Sin las subvenciones, muchos agricultores verían reducidos **significativamente** sus beneficios operativos (gran parte de la actividad agrícola en España sería **inviable**), ya que los **precios** de mercado suelen ser **bajos**.

   - En el contexto de nuestra plataforma, las subvenciones PAC no afectan directamente el modelo de negocio, pero sí influyen en la capacidad de los agricultores para mantenerse activos. Al vender sus productos a través de nuestra plataforma, los agricultores pueden obtener ingresos adicionales que complementen las ayudas recibidas, mejorando su estabilidad financiera.

   - Nuestro marketplace puede ayudar a reducir la dependencia de las subvenciones a largo plazo, permitiendo a los agricultores obtener precios más justos por sus productos. Sin embargo, las subvenciones seguirán siendo un apoyo importante, especialmente en los primeros años de adopción de la plataforma. Al destacar cómo nuestra plataforma complementa los ingresos de las subvenciones, podemos atraer a más agricultores y fortalecer su posición en el mercado.

#### Problemas actuales

- **Precios bajos impuestos por intermediarios**: Los agricultores suelen vender sus productos a precios bajos fijados por los intermediarios.
- **Competencia internacional**: Los precios de productos importados son más bajos, afectando a los agricultores locales.

#### Impacto del marketplace en los ingresos del agricultor

La plataforma que propones busca **eliminar intermediarios** y permitir la venta directa al consumidor final, lo que podría aumentar los ingresos de los agricultores. A continuación, se muestra un supuesto de cómo esto impactaría sus ingresos.

#### Supuesto de ingresos con el marketplace

1. **Ventas directas**:
   - Si un agricultor vende un **10% de su producción** a través del marketplace, y su explotación genera 40.000 euros anuales, estaría vendiendo productos por valor de **4.000 euros**.

2. **Precios más altos**:
   - Al eliminar intermediarios, el agricultor podría aumentar el precio de sus productos entre un **20%-30%**, lo que generaría **800 a 1.200 euros adicionales**.

3. **Coste del marketplace**:
   - Si la plataforma cobra una comisión del **15%**, el agricultor pagaría **600 euros** de comisión por esos 4.000 euros en ventas, lo que le dejaría un ingreso neto de **3.400 euros**.

#### Diferencia con la situación actual

En este ejemplo, el agricultor podría generar entre **3.400 y 4.000 euros adicionales** al año gracias a la venta directa a través de la plataforma. Para un agricultor que actualmente obtiene un beneficio neto de **10.000 euros**, esto podría aumentar sus ingresos a **14.000 euros**, lo que representa una mejora de hasta un **40%** en su rentabilidad.

#### Conclusión

- Los agricultores autónomos en España suelen tener beneficios netos de **8.000-12.000 euros** al año, con grandes dependencias en subvenciones y precios impuestos por intermediarios.
- Con la venta directa a través del marketplace, podrían ver una mejora significativa en sus ingresos, aumentando sus beneficios en hasta un **40%** si logran vender un porcentaje de su producción a precios más justos.

Este aumento en los ingresos haría que la actividad agrícola sea más rentable y sostenible a largo plazo, permitiendo a los agricultores depender menos de los intermediarios y las subvenciones.

#### Aplicaciones o productos existentes que abordan las necesidades de los agricultores autónomos

#### 1. Ecomercado
- **Descripción**: Ecomercado es una plataforma que facilita la venta de productos agrícolas y ecológicos directamente desde los productores a los consumidores, eliminando intermediarios.
- **Solución**: Permite a los agricultores establecer contacto directo con compradores interesados en productos ecológicos, lo que les permite fijar sus propios precios y recibir un porcentaje mayor del valor del producto.
- **Medida de éxito**: Consigue reducir la dependencia de los agricultores respecto a grandes distribuidores, pero se enfoca más en productos ecológicos, limitando su adopción entre agricultores convencionales.

#### 2. Alcampo Proximidad
- **Descripción**: Alcampo lanzó el programa "Proximidad" que permite a agricultores locales vender sus productos a través de la cadena de supermercados. Apoya la venta de productos locales y de temporada, reduciendo intermediarios.
- **Solución**: Aunque sigue siendo a través de una cadena de distribución, los agricultores logran colocar sus productos en supermercados con condiciones más favorables y enfocadas en productos locales.
- **Medida de éxito**: Ofrece mayor visibilidad a los agricultores locales, pero sigue siendo un modelo con intermediarios, por lo que los agricultores no tienen control total sobre precios y márgenes.

#### 3. Huertos Compartidos
- **Descripción**: Plataforma que conecta a personas con terrenos sin uso con agricultores que necesitan espacio para cultivar. Además, facilita la venta de productos directamente al consumidor.
- **Solución**: Ofrece una solución dual, tanto en términos de espacio para cultivar como de acceso a un mercado directo de consumidores, reduciendo intermediarios.
- **Medida de éxito**: Ayuda a pequeños agricultores a obtener ingresos adicionales, pero está más enfocada a quienes no poseen terrenos propios, lo que no resuelve el problema de quienes sí tienen tierra pero no acceso al mercado.

#### 4. Crowdfarming
- **Descripción**: Plataforma que permite a los agricultores vender sus productos directamente a los consumidores a través de un sistema de apadrinamiento de cosechas o árboles.
- **Solución**: El consumidor "apadrina" un árbol o una parte de la cosecha, y el agricultor le envía los productos. Esto elimina intermediarios y el agricultor recibe un pago más justo por su trabajo.
- **Medida de éxito**: Es una de las plataformas más exitosas en eliminar intermediarios y permitir que los agricultores reciban un precio justo, pero el modelo de apadrinamiento no es adecuado para todos los productos agrícolas.

#### 5. Cesta Verde
- **Descripción**: Plataforma que permite a agricultores vender cestas de productos frescos de temporada directamente a consumidores locales.
- **Solución**: Facilita la venta directa de productos agrícolas, dando mayor control a los agricultores sobre el precio y la comercialización de sus productos.
- **Medida de éxito**: Ha logrado cierto éxito en conectar agricultores con consumidores locales, pero tiene un enfoque limitado a productos de temporada y depende de la proximidad geográfica.

---

#### Medida en que lo consiguen

1. **Reducción de intermediarios**: 
   - Muchas de estas plataformas logran reducir o eliminar la cadena de intermediarios, lo que permite a los agricultores fijar precios más justos y aumentar sus márgenes de beneficio. Sin embargo, algunas aún operan con intermediarios, aunque más pequeños y enfocados al comercio local.

2. **Venta directa al consumidor**:
   - La mayoría permite a los agricultores vender directamente al consumidor, lo que es un avance significativo. Sin embargo, el desafío sigue siendo alcanzar un público más amplio. Algunas plataformas están limitadas a nichos como productos ecológicos o de temporada, lo que puede excluir a agricultores convencionales.

3. **Dependencia tecnológica**:
   - Algunos agricultores no están familiarizados con el uso de plataformas digitales o no tienen el tiempo para gestionar ventas en línea, lo que limita la adopción generalizada, ya que muchas plataformas no ofrecen suficiente soporte técnico.

4. **Escalabilidad**:
   - Muchas de estas soluciones tienen éxito a nivel local o regional, pero no siempre son capaces de escalar a nivel nacional o internacional, lo que sería necesario para transformar verdaderamente el sector.

---

#### Conclusión

Existen diversas plataformas que abordan parcialmente las necesidades de los agricultores, centradas en la venta directa y la eliminación de intermediarios. Sin embargo, muchas de ellas se limitan a nichos específicos, lo que deja fuera a una parte significativa de los agricultores. 

Aunque el modelo de venta directa mejora los márgenes, la adopción tecnológica y la escalabilidad siguen siendo grandes desafíos. 

Este **marketplace agrícola** se diferencia ofreciendo una solución más integral e inclusiva, abarcando todo tipo de agricultores, no solo aquellos con productos ecológicos o locales. Además, incluye mejoras como el **chat en tiempo real entre agricultores y clientes**, para mejorar la experiencia de compra y fortalecer la relación entre ambas partes.

#### ¿Se trata de un segmento de mercado desabastecido o insuficientemente atendido?

El segmento de los **agricultores autónomos** en España, especialmente aquellos que buscan vender directamente al consumidor sin intermediarios, puede considerarse **insuficientemente atendido**. Aunque existen algunas plataformas y aplicaciones que intentan resolver los problemas del sector, aún hay desafíos y oportunidades que no se han abordado completamente.

#### 1. Limitación de nichos
- Muchas de las plataformas actuales se enfocan en nichos muy específicos, como productos **ecológicos**, **locales** o de **temporada**. Esto excluye a agricultores que no producen bajo estas categorías (agricultura convencional o a gran escala).
- **Oportunidad**: Existe un vacío para una plataforma que sea inclusiva para **todo tipo de agricultores**, independientemente de la categoría de productos o del tamaño de su producción.

#### 2. Falta de control sobre precios
- Muchos agricultores siguen dependiendo de **intermediarios**, lo que significa que no tienen control total sobre los precios de venta, afectando directamente sus beneficios.
- **Oportunidad**: Un marketplace que permita a los agricultores fijar **precios justos y transparentes** sin intermediarios podría ser altamente atractivo.

#### 3. Tecnología limitada y falta de acceso digital
- Algunos agricultores no están familiarizados con el uso de herramientas digitales avanzadas, lo que limita su acceso a las plataformas existentes. Esto requiere **capacitación** y **asistencia técnica**, que no siempre están bien cubiertas.
- **Oportunidad**: Un marketplace con una interfaz sencilla, optimizada para **usabilidad** y **soporte técnico**, facilitaría la adopción de la tecnología por parte de los agricultores.

#### 4. Escasa integración de servicios adicionales
- La mayoría de las plataformas actuales se centran únicamente en la venta de productos, sin ofrecer herramientas para la **logística**, **comunicación con clientes**, o **optimización de operaciones**.
- **Oportunidad**: Incluir servicios adicionales como **chat en tiempo real** para comunicación entre agricultores y clientes, gestión logística integrada, y analíticas de ventas diferenciaría una nueva plataforma en el mercado.

#### 5. Desafíos de escalabilidad
- Muchas plataformas funcionan bien a nivel **local o regional**, pero no han podido **escalar** a nivel nacional o internacional, dejando fuera a muchos agricultores.
- **Oportunidad**: Un marketplace con un modelo escalable que pueda operar tanto a nivel **regional** como **nacional**, cubriría esta carencia en el sector.

---

#### Conclusión
El segmento de los agricultores autónomos que desean vender sus productos directamente al consumidor sigue siendo **insuficientemente atendido**, a pesar de la existencia de algunas plataformas. Las soluciones actuales están enfocadas en nichos específicos, carecen de escalabilidad y no ofrecen el soporte técnico o servicios adicionales que muchos agricultores necesitarían.

**Oportunidad clara**: Desarrollar un **marketplace agrícola inclusivo** que ofrezca una experiencia integral (venta directa, control total de precios, soporte técnico, servicios añadidos como chat en tiempo real y gestión logística) podría cubrir un vacío importante en este segmento, atrayendo tanto a pequeños agricultores locales como a aquellos con producciones más grandes o convencionales.

#### Estrategia de Escalabilidad del Proyecto

Escalar una plataforma enfocada en la venta de productos agrícolas presenta ciertos retos únicos, especialmente debido a las diferencias regionales en producción, logística y la cultura agrícola. Sin embargo, con una planificación estratégica y las herramientas adecuadas, la plataforma puede crecer de manera eficiente tanto dentro de España como en otras regiones. A continuación, se desglosan los pasos y consideraciones clave para la escalabilidad.

1. **Adaptación Regional**

Cada región de España tiene sus propias particularidades en cuanto a cultivos, cosechas y modelos de venta agrícola. Es crucial que el marketplace pueda adaptarse a las características regionales sin comprometer la experiencia de usuario unificada.

**Estrategias de Adaptación:**

- **Secciones Regionales:** Crear subcategorías dentro de la plataforma dedicadas a diferentes regiones agrícolas. Esto permitirá destacar productos únicos de cada zona, como vinos de La Rioja, aceites de Jaén o cítricos de Valencia, lo que a su vez da valor a la identidad regional.
- **Soporte Multilingüe:** En regiones donde se hablen otras lenguas oficiales como el gallego, catalán o euskera, implementar la opción de acceder a la plataforma en su idioma local puede mejorar la adopción tecnológica y crear una mejor conexión con los usuarios.

2. **Logística y Distribución**

El éxito de una plataforma escalable radica en una logística eficiente. A medida que la plataforma crezca a nivel geográfico, gestionar el transporte de productos perecederos y frescos se convertirá en un desafío clave. Sin embargo, con una optimización logística, esto se puede manejar de forma efectiva.

**Estrategias Logísticas:**

- **Red de distribución regional:** Crear alianzas con empresas de transporte locales que se especialicen en la distribución de productos frescos. Un enfoque escalable sería empezar con alianzas locales y luego crear una red de distribución a nivel nacional.
- **Centros de acopio locales:** Estos centros actuarían como puntos intermedios donde los productos se reúnen para una distribución más amplia. Implementar esto puede reducir costes de transporte y mejorar los tiempos de entrega.
- **Gestión de inventario descentralizada:** Permitir que los agricultores y cooperativas gestionen su propio inventario y actualicen en tiempo real las existencias disponibles. Esto facilita una logística más eficiente y asegura que no haya retrasos en la entrega por falta de stock.

3. **Modelo de Franquicia Local**

La escalabilidad puede lograrse a través de un modelo de franquicia digital o multiplicidad. Esto significaría que la plataforma podría licenciarse o cederse a otras regiones para que gestionen su propio marketplace agrícola bajo el mismo modelo.

**Beneficios del Modelo de Franquicia:**

- **Adaptación local:** Cada región podría tener un administrador local que entiende las necesidades y desafíos específicos del área, mejorando la relación con los agricultores.
- **Marca nacional:** Aunque cada zona gestionaría su propio marketplace, todo estaría bajo la misma marca y estructura, manteniendo la coherencia del modelo de negocio.
- **Escalabilidad rápida:** Este modelo facilita una expansión más rápida sin necesidad de centralizar todas las operaciones, reduciendo los costes operativos y permitiendo que el negocio crezca de manera orgánica.

4. **Tecnología Escalable**

Desde el punto de vista tecnológico, es fundamental que la plataforma esté construida con una arquitectura escalable desde el inicio. Esto asegura que la infraestructura puede soportar el crecimiento en usuarios, productos y transacciones sin comprometer el rendimiento.

**Estrategias Tecnológicas:**

- **Infraestructura en la nube:** Usar una infraestructura en la nube permite escalar fácilmente la capacidad de procesamiento, almacenamiento y ancho de banda a medida que crece el número de usuarios y agricultores en la plataforma.
- **Microservicios:** Implementar una arquitectura de microservicios facilita la escalabilidad de las diferentes funciones de la plataforma (gestión de productos, pedidos, pagos, etc.) sin afectar el funcionamiento de otras partes del sistema.
- **SEO local:** Optimizar la plataforma para motores de búsqueda de forma que sea fácilmente accesible a nivel regional y nacional. Esto permitirá que los agricultores locales puedan encontrar la plataforma cuando busquen soluciones para vender sus productos en línea.

5. **Expansión Internacional**

Una vez que la plataforma esté consolidada a nivel nacional, se puede explorar la expansión a otros países con modelos agrícolas similares, como Portugal, Francia o Italia. Esto abriría nuevas oportunidades de mercado, pero también implicaría nuevos retos normativos, logísticos y culturales.

**Consideraciones para la Expansión Internacional:**

- **Regulaciones locales:** Cada país tiene su propia normativa en cuanto a la venta de productos agrícolas y la protección de datos de los usuarios, por lo que es fundamental realizar un estudio previo para asegurar que la plataforma cumple con todas las normativas locales.
- **Logística transfronteriza:** Los envíos internacionales requerirían alianzas logísticas especializadas en transporte de alimentos, además de la implementación de sistemas de aduana y control de calidad de productos.
- **Plataformas de pago internacionales:** Adaptar la plataforma a sistemas de pago que operen en los diferentes países a los que se expanda. Esto incluye la posibilidad de aceptar diferentes monedas o utilizar sistemas de pago locales.

6. **Sostenibilidad y Escalabilidad**

En un negocio agrícola, la sostenibilidad es clave. Al escalar la plataforma, se pueden incorporar elementos que promuevan una agricultura más sostenible, como incentivos para los agricultores que utilicen métodos ecológicos, etiquetas verdes para productos sostenibles y alianzas con instituciones que promuevan la agricultura orgánica.

7. **Modelo de Crecimiento Progresivo**

Para que el proyecto sea escalable, es necesario implementarlo en fases que vayan consolidando su éxito a medida que crece.

**Fases de Crecimiento:**

- **Fase 1: Validación Local:** Lanzar la plataforma en una o dos provincias clave, trabajando con agricultores y cooperativas locales para validar el modelo de negocio y asegurarse de que todo funciona correctamente.
- **Fase 2: Expansión Regional:** Ampliar el alcance a nivel regional, creando alianzas con nuevas cooperativas y agricultores en zonas de interés.
- **Fase 3: Expansión Nacional:** A medida que se establezcan más relaciones y la plataforma se consolide, expandir a nivel nacional cubriendo todas las comunidades autónomas de España.
- **Fase 4: Expansión Internacional:** Una vez que la plataforma esté bien asentada en España, comenzar con la expansión a países vecinos con características agrícolas similares.

**Conclusión**

La escalabilidad del marketplace se puede lograr mediante una combinación de adaptación local, alianzas estratégicas con cooperativas, una infraestructura tecnológica robusta y la implementación de un modelo de crecimiento por fases. La clave será crecer de manera progresiva y asegurarse de que las necesidades tanto de los agricultores como de los consumidores sean atendidas a medida que se expanda.


#### **Superando la Brecha Digital en el Sector Agrícola**

Uno de los principales desafíos que enfrenta el mercado agrícola es la resistencia de los agricultores a adoptar nuevas tecnologías. Este reto, especialmente pronunciado en segmentos de edad más avanzada o en áreas rurales con menor acceso a la digitalización, puede comprometer el éxito de una plataforma de venta online agrícola. Para abordar este obstáculo y fomentar la adopción de la tecnología, es necesario desarrollar una estrategia integral que permita a los agricultores familiarizarse con la plataforma y percibir su valor de manera rápida y efectiva.

1. Formación y Capacitación Accesible

Es fundamental ofrecer un sistema de formación continua que permita a los agricultores aprender de forma gradual y accesible cómo utilizar la plataforma de manera eficiente. La clave para superar la barrera tecnológica es proporcionar recursos educativos que les guíen paso a paso.

**Propuesta de Capacitación:**
- **Tutoriales en vídeo**: Incluir vídeos que expliquen el uso de la plataforma desde su registro hasta la gestión de productos, ventas y pagos. Estos vídeos deben ser de fácil comprensión, accesibles desde la misma plataforma y estar disponibles en varios idiomas locales.
- **Soporte técnico personalizado**: Implementar un servicio de asistencia telefónica y por chat en el que los agricultores puedan recibir orientación directa y personalizada para resolver dudas o problemas técnicos en tiempo real.
- **Talleres presenciales**: Organizar talleres en colaboración con cooperativas agrarias o asociaciones locales, donde los agricultores puedan aprender el uso de la plataforma en un entorno cercano y familiar.
- **Agricultores embajadores**: Aprovechar a agricultores jóvenes o aquellos con mayor experiencia tecnológica como embajadores que difundan el uso de la plataforma entre sus colegas, facilitando la transición tecnológica en la comunidad.

2. Interfaces Intuitivas y Simplicidad de Uso

Para atraer a un mayor número de agricultores, la plataforma debe tener una interfaz intuitiva y fácil de usar, que simplifique la gestión de las ventas online y minimice el esfuerzo requerido para aprender a manejarla.

**Propuesta de Diseño:**
- **Interfaz simplificada**: Un diseño limpio y accesible, con menús claros y fáciles de navegar. Cada sección (gestión de productos, ventas, pagos) debe estar bien diferenciada mediante iconos y descripciones simples.
- **Optimización para dispositivos móviles**: Muchos agricultores pueden preferir el uso de smartphones, por lo que la plataforma debe estar completamente optimizada para móviles, asegurando su funcionamiento incluso en áreas con baja velocidad de internet.
- **Registro y gestión rápida**: Simplificar el proceso de registro y gestión de productos para evitar la sobrecarga de información. Solo se pedirán los datos esenciales, reduciendo la complejidad inicial.
- **Dashboard personalizado**: Ofrecer un panel de control donde el agricultor pueda visualizar el estado de sus productos, ventas y pagos de un solo vistazo, sin necesidad de navegar por varias páginas.

3. Incentivos para Facilitar la Adopción

Para incentivar la adopción masiva de la plataforma, se propone ofrecer un sistema de bonificaciones y ventajas competitivas durante los primeros meses de uso, que animen a los agricultores a probarla y a obtener beneficios sin riesgos iniciales.

**Propuesta de Incentivación:**
- **Comisiones reducidas o nulas**: Implementar un sistema de comisiones reducidas durante los primeros 3 a 6 meses de uso, para que los agricultores vean cómo aumentan sus ingresos sin penalizaciones por el uso de la plataforma.
- **Bonificaciones por referidos**: Crear un sistema de referidos que recompense a los agricultores que traigan a nuevos usuarios a la plataforma, fomentando así un crecimiento orgánico y sostenible.
- **Publicidad gratuita inicial**: Ofrecer a los primeros usuarios la posibilidad de destacar sus productos sin coste adicional en las secciones más visibles de la plataforma, asegurando un incremento en sus ventas durante el lanzamiento.

4. Colaboración con Asociaciones Agrarias y Cooperativas

Las cooperativas agrarias y las asociaciones de agricultores juegan un papel clave en el ecosistema agrícola y ya cuentan con la confianza de muchos agricultores. Para potenciar el uso de la plataforma, se propone establecer alianzas estratégicas con estas instituciones.

**Propuesta de Colaboración:**
- **Demostraciones conjuntas**: Realizar demostraciones en eventos organizados por las cooperativas para mostrar cómo la plataforma puede beneficiar tanto a los agricultores individuales como a las propias cooperativas.
- **Planes específicos para cooperativas**: Ofrecer tarifas reducidas o comisiones especiales para cooperativas que utilicen la plataforma, permitiéndoles usarla como una herramienta adicional para potenciar sus ventas.
- **Testimonios y casos de éxito locales**: Publicar historias de agricultores locales que hayan aumentado sus ingresos utilizando la plataforma. Esto puede generar confianza entre otros agricultores, incentivando su adopción.

5. Reducción del Riesgo Percibido

Es posible que algunos agricultores perciban la adopción de la tecnología como un riesgo. Para mitigar este temor, la plataforma debe ofrecer garantías de seguridad tanto en los pagos como en la gestión de las ventas, de modo que los agricultores sientan que sus productos y sus ingresos están protegidos.

**Propuesta para Reducir Riesgos:**
- **Garantía de pagos**: Proveer un sistema de pagos seguro y confiable, donde los agricultores reciban su compensación puntualmente y sin problemas.
- **Política de protección al agricultor**: Establecer políticas de devolución o protección en caso de que algo falle en una transacción, brindando seguridad adicional.
- **Soporte técnico constante**: Ofrecer soporte 24/7 para resolver cualquier duda o problema técnico que pueda surgir en cualquier momento.

6. Estrategias de Comunicación y Marketing Educativo

La campaña de comunicación debe enfocarse no solo en promover la plataforma, sino en educar a los agricultores sobre los beneficios reales que la tecnología puede ofrecerles. Es importante que perciban cómo esta herramienta puede ayudarles a aumentar sus ingresos y reducir su dependencia de intermediarios.

**Propuesta de Marketing Educativo:**
- **Casos de éxito locales**: Publicar ejemplos reales de agricultores que hayan mejorado sus ventas utilizando la plataforma. Las historias cercanas son más efectivas a la hora de generar confianza.
- **Infografías explicativas**: Crear material gráfico sencillo que explique cómo la plataforma reduce intermediarios, facilita la venta directa y aumenta los ingresos.
- **Publicidad en medios rurales**: Utilizar radios locales, redes de agricultores y publicaciones rurales para llegar directamente a los potenciales usuarios de la plataforma.

#### Conclusión

Superar la resistencia de los agricultores a las nuevas tecnologías es un desafío considerable, pero con una estrategia integral que combine **formación**, **soporte**, **incentivos** y **colaboraciones estratégicas**, la adopción de la plataforma puede ser facilitada. Al simplificar la experiencia de usuario y proporcionar beneficios tangibles desde el principio, la plataforma tendrá mayores probabilidades de éxito en un entorno agrícola tradicional.

#### ¿Un producto ineficiente? ¿Un mercado nuevo?

#### 1. Producto ineficiente

Un **producto ineficiente** se refiere a una solución que no cumple con las expectativas o necesidades del usuario final, ya sea por falta de funcionalidades, por ser poco accesible, o por no resolver efectivamente el problema para el que fue diseñado. En el caso del mercado agrícola, se pueden identificar varios aspectos que contribuyen a la ineficiencia:

#### 1.1 Limitaciones de las plataformas actuales
- **Enfoque en nichos específicos**: Muchas plataformas se centran en productos ecológicos o locales, lo que limita la oferta para otros tipos de productos agrícolas, excluyendo a una parte significativa de los agricultores.
- **Intermediarios**: Aunque algunas aplicaciones buscan eliminar intermediarios, muchas siguen operando bajo modelos que dependen de ellos, lo que impide a los agricultores obtener precios justos.

#### 1.2 Falta de usabilidad
- **Interfaz compleja**: Muchas aplicaciones son difíciles de navegar o entender, lo que desincentiva su uso por parte de agricultores que no están familiarizados con la tecnología.
- **Poca formación técnica**: La falta de soporte y capacitación adecuada limita la capacidad de los agricultores para utilizar eficazmente estas plataformas.

#### 1.3 Escasa integración de servicios
- **Enfoque limitado**: La mayoría de las plataformas se centran únicamente en la venta, sin ofrecer funcionalidades adicionales como gestión logística o análisis de mercado, lo que podría ayudar a los agricultores a maximizar su rentabilidad.

#### 2. Mercado nuevo

Por otro lado, se podría considerar que estamos ante un **mercado nuevo** en el contexto de la venta directa de productos agrícolas. Las razones para esta consideración son las siguientes:

#### 2.1 Cambio en las dinámicas de consumo
- **Interés creciente por productos locales y sostenibles**: Hay un aumento en la demanda de productos frescos, locales y sostenibles entre los consumidores, impulsado por una mayor conciencia sobre la salud y el medio ambiente.
- **Apoyo a la economía local**: Los consumidores están más interesados en apoyar a los agricultores locales, lo que crea un espacio para un marketplace que conecte directamente a productores y consumidores.

#### 2.2 Avances tecnológicos
- **Adopción de e-commerce**: La creciente aceptación del comercio electrónico y la digitalización de las empresas abre la puerta a nuevas oportunidades de negocio en el sector agrícola.
- **Facilidad de acceso a herramientas digitales**: Con la evolución de las tecnologías, cada vez es más accesible crear plataformas que faciliten la conexión entre agricultores y consumidores.

#### 2.3 Cambios en la normativa
- **Iniciativas gubernamentales**: Algunas regulaciones y políticas están promoviendo la venta directa de productos agrícolas, lo que puede fomentar el crecimiento de un mercado nuevo y facilitar la creación de plataformas que respondan a estas necesidades.

---

#### Conclusión

La situación del mercado agrícola actual puede caracterizarse tanto por la **ineficiencia** de los productos existentes como por la aparición de un **mercado nuevo**. 

- **Ineficiencia**: Las plataformas actuales no satisfacen adecuadamente las necesidades de todos los agricultores, están limitadas por el enfoque en nichos específicos, la falta de usabilidad, y la escasa integración de servicios.
  
- **Mercado nuevo**: Existe una creciente oportunidad para un marketplace agrícola que conecte directamente a los agricultores con los consumidores, aprovechando el cambio en las dinámicas de consumo y la tecnología disponible.

Por lo tanto, se presenta una **oportunidad significativa** para desarrollar una solución integral que no solo resuelva los problemas de ineficiencia actuales, sino que también aproveche el potencial de un mercado en expansión.


### 2.3- Segmento de clientes

El segmento de clientes principales serán agricultores pequeños y medianos en España que buscan mejorar sus ingresos vendiendo directamente al consumidor final. Asimismo, los consumidores interesados en productos frescos y locales forman el otro segmento clave. Además, las cooperativas agrícolas también serán un segmento importante, ya que pueden beneficiarse de la plataforma para ampliar su visibilidad y mercado.

### 2.4- Competencia

El proyecto competirá con plataformas de distribución de alimentos y grandes supermercados online. Sin embargo, el marketplace se diferenciará por su enfoque en el comercio directo sin intermediarios, ofreciendo precios más justos tanto para el agricultor como para el consumidor. 

En lugar de ver a las cooperativas agrícolas físicas como competidores, se las posicionará como socios estratégicos de la plataforma online, logrando una relación de beneficio mutuo. Las cooperativas ya tienen una base sólida de agricultores y una estructura establecida de distribución, pero su visibilidad online y capacidad de captar nuevos mercados puede ser limitada. Aquí es donde el marketplace puede ofrecer un valor añadido importante.

#### Beneficios para las Cooperativas al Usar la Plataforma

1. **Mayor visibilidad en el mercado online**:
   - La mayoría de las cooperativas operan en mercados locales o regionales y su alcance suele estar limitado a clientes en un radio cercano. Al unirse a la plataforma, tendrían acceso a un mercado más amplio, lo que les permitiría vender a clientes de otras provincias o incluso de todo el país.
   - La plataforma podría ofrecer un espacio personalizado para las cooperativas, donde se muestre su catálogo completo de productos, dándoles visibilidad sin que tengan que invertir en desarrollar su propia infraestructura tecnológica.

2. **Fomento de la proximidad**:
   - Las cooperativas tienen una fuerte presencia local y una base de clientes leales. La plataforma puede aprovechar esto creando funcionalidades basadas en la proximidad, como un filtro de búsqueda geográfico, donde los clientes puedan encontrar productos locales de cooperativas cercanas. Esto refuerza la idea de consumo responsable y proximidad, que es cada vez más valorada por los consumidores.

3. **Simplificación de la logística**:
   - La plataforma podría facilitar la logística y distribución, integrando un sistema de envío y entrega optimizado. Al tener cooperativas en diferentes zonas geográficas, se podrían coordinar rutas de entrega de manera más eficiente, reduciendo costes de transporte tanto para los agricultores como para los clientes.

4. **Negociación de comisiones especiales**:
   - Para atraer a cooperativas grandes y consolidadas, se podrían negociar comisiones preferenciales o beneficios adicionales si deciden vender sus productos a través del marketplace. Por ejemplo, ofrecerles un período de prueba sin comisiones o tarifas reducidas por volumen de ventas podría ser un incentivo importante.

5. **Aprovechamiento del marketing local y la confianza**:
   - Las cooperativas tienen una fuerte relación de confianza con sus clientes locales. Se podría aprovechar esto colaborando con ellas en campañas de marketing local, donde promocionen su alianza con la plataforma y atraigan tanto a nuevos compradores como a más agricultores para que se unan. Además, se podría incluir una sección donde se destaque el impacto positivo de la compra a cooperativas locales.

#### Cómo Proponer la Colaboración

1. **Presentar la plataforma como un complemento**:
   - En lugar de presentarse como un competidor directo, la plataforma debe verse como un complemento que permitirá a las cooperativas acceder a un mercado online sin tener que asumir el coste y la complejidad de crear una tienda digital propia.

2. **Aliado tecnológico**:
   - Ofrecerse como aliado tecnológico les permitirá externalizar toda la parte técnica y logística, manteniendo su independencia en la gestión de sus productos, precios y clientes, lo que podría ser un argumento atractivo para ellas.

3. **Campaña de incorporación**:
   - Una buena estrategia sería lanzar una campaña dirigida a cooperativas bajo el lema de "Visibilidad nacional para productos locales". Esta campaña podría ofrecer a las cooperativas una experiencia piloto, mostrándoles cómo la plataforma puede ayudarlas a aumentar ventas y llegar a más clientes.

#### Ejemplo Práctico

Supongamos que una cooperativa agrícola en Galicia, que actualmente solo vende productos en tiendas locales y mercados, decide unirse a la plataforma. Esto le permitiría:

- Ampliar su base de clientes más allá de su localidad.
- Digitalizar parte de su negocio sin asumir los riesgos ni el coste de crear una web propia.
- Acceder a una infraestructura logística que facilite el envío de productos a otras regiones.
- Negociar mejores tarifas de transporte al centralizar los envíos con otros agricultores o cooperativas cercanas.

#### Conclusión

Convertir a las cooperativas físicas en socios estratégicos en lugar de competir con ellas es una estrategia clave para el éxito de la plataforma. Al ofrecerles visibilidad, simplificación logística y acuerdos comerciales ventajosos, se puede aprovechar su red de agricultores y clientes para hacer crecer el marketplace de manera rápida y eficiente.

### 2.5- Propuesta de valor

Los agricultores ganarán acceso a una plataforma sencilla y eficiente para la venta directa de sus productos. Los consumidores, por su parte, se beneficiarán de productos frescos a precios competitivos y con un acceso directo al origen de los alimentos.

### 2.6- Forma jurídica

La forma jurídica será una sociedad limitada.

### 2.7- Inversiones

#### 2.7.1- Costos y Gastos Iniciales

Al ser una sociedad limitada, las siguientes inversiones serán necesarias:

- Costes de constitución de la sociedad limitada:
   - Capital social mínimo: 3,000 EUR (requerido legalmente).
   - Gastos de constitución: alrededor de 500 EUR (notaría, registro mercantil, etc.).

- Infraestructura y equipo técnico:
   - Ordenador para desarrollo: Un ordenador de gama media adecuado para programación y desarrollo web rondaría los 1,000 EUR.
   - Servidor/hosting web: El costo de un servidor para alojar una plataforma con tráfico moderado podría oscilar entre 300 EUR y 500 EUR/año si se utiliza un servidor en la nube como AWS o DigitalOcean.
      - Coste anual del hosting: entre 300 EUR y 500 EUR.
   - Dominio web: Aproximadamente 10-20 EUR/año.
   - Certificado SSL: Recomendado para asegurar la página, costando alrededor de 50 EUR/año.

- Desarrollo y mantenimiento:
   - Desarrollo de la plataforma: Dado que planeo desarrollarlo yo mismo, no tendría que contar con los gastos de contratar a un programador. Sin embargo, para el mantenimiento y posibles actualizaciones futuras, podrías necesitar un presupuesto anual de 2,000 EUR.

- Marketing:
   Para dar a conocer el marketplace entre agricultores y consumidores, se necesitará invertir en publicidad digital. Un presupuesto inicial de marketing de 500 EUR sería razonable para campañas de redes sociales y SEO.

   ### Fuentes de Datos

   Las fuentes utilizadas para los cálculos y decisiones del proyecto provienen del Ministerio de Agricultura, Pesca y Alimentación de España, asociaciones agrarias y plataformas agrícolas existentes en España como "La Colmena Que Dice Sí" y "Crowdfarming". Estas fuentes proporcionan información sobre la rentabilidad agrícola, costes y problemas enfrentados por los agricultores.

   ### Calculo de Ingresos Usando Ejemplos Reales

   Basándonos en las comisiones estándar de plataformas similares, que oscilan entre un 20% y 30% por cada venta, hemos decidido establecer una comisión más competitiva del 15% para atraer a más agricultores y mejorar sus condiciones de venta. 

   #### Supuestos para el cálculo:

   - **Comisión**: 15% por producto vendido.
   - **Ingreso Promedio por Agricultor**: Para un agricultor que venda productos frescos (frutas, verduras, hortalizas, etc.), el ingreso promedio por mes podría rondar los 3000 - 5000 euros, dependiendo de la zona y la demanda de los productos.
   - **Coste de la plataforma**: Incluimos gastos en servidores, mantenimiento y posibles comisiones a terceros (por ejemplo, envíos).

#### 2.7.2- Ingresos Estimados

El modelo de ingresos estará basado en una comisión por cada venta realizada a través de la plataforma. Aquí una estimación con números ajustados:

- Comisión por producto vendido: Suponemos una comisión del 15% por cada transacción realizada en la plataforma.

- Ventas iniciales estimadas: Para una estimación inicial conservadora, podríamos calcular que durante los primeros 6 meses, se realicen unas 20 transacciones mensuales por agricultor, con un precio promedio por transacción de 100 EUR.

- Ventas mensuales estimadas: 20 agricultores × 20 transacciones × 100 EUR = 40,000 EUR/mes.
- Comisión mensual generada (15% de 40,000 EUR): 6,000 EUR/mes.
- Ingresos anuales estimados: 6,000 EUR × 12 meses = 72,000 EUR/año.

Resumen Financiero

Concepto | Costo (EUR)
--- | ---
Capital social mínimo | 3,000 EUR
--- | ---
Gastos de constitución | 500 EUR
Ordenador para desarrollo | 1,000 EUR
Hosting (anual) | 500 EUR
Dominio (anual) | 20 EUR
Certificado SSL (anual) | 50 EUR
Mantenimiento (anual) | 24,000 EUR
Marketing inicial | 1,500 EUR
Total costos iniciales (primer año) | 30,570 EUR

- Ingresos estimados anuales (primer año): 72,000 EUR.
- Costes operativos anuales (primer año): 30,570 EUR.
- Beneficio bruto anual antes de impuestos: 72,000 EUR - 30,570 EUR = 41,430 EUR
- Impuesto de sociedades (25%): 41,430 EUR * 0.25 = 10,357.50 EUR
- Beneficio neto anual: 41,430 EUR - 10,357.50 EUR = 31,072.50 EUR

Los vendedores de la web serían tanto agricultores como cooperativas que se quieran unir.

Este modelo es más realista y conservador, ofreciendo margen de crecimiento conforme la plataforma atraiga a más agricultores y cooperativas.

En el segundo año, los costos disminuirían (sin capital social ni constitución) y los ingresos podrían aumentar con más usuarios, lo que podría llevar a un resultado bastante positivo.

### 2.8- Viabilidad

#### 2.8.1- Viabilidad técnica

La tecnología propuesta (CakePHP, Bootstrap, JS, HTML, CSS) es adecuada para el desarrollo de este tipo de plataformas. Además, se prevé la disponibilidad de los recursos humanos necesarios para llevar a cabo el proyecto.

#### 2.8.2 - Viabilidad económica

Dado el modelo de negocio y la creciente demanda de productos directos del campo, la viabilidad económica es prometedora. Los ingresos de las comisiones por venta y suscripciones pueden cubrir los costos operativos a largo plazo.

#### 2.8.3- Conclusión

El proyecto es viable tanto técnica como económicamente. Además, puede tener un impacto positivo en los agricultores, mejorando sus ingresos.

## 3- Requerimientos técnicos

- **Infraestructura:** Se necesitará un dominio y servidor web dedicado (o nube), almacenamiento y base de datos (MySQL), y sistema de almacenamiento para imágenes.
- **Backend:** Se utilizará CakePHP para la lógica del negocio y la gestión de datos.
- **Frontend:** Se utilizarán Bootstrap, HTML, CSS y JavaScript para crear una interfaz responsiva y atractiva.
- **Base de datos:** MySQL almacenarán los datos de usuarios, productos y pedidos.

## 4- Planificación

El desarrollo del proyecto se llevará a cabo en un plazo de dos meses, comenzando el 23 de septiembre de 2024. Se seguirán las siguientes fases:

| Fase                      | Duración    | Fecha de inicio |
|---------------------------|-------------|-----------------|
| Estudio preliminar        | 1 semana    | 23/09/2024      |
| Análisis                  | 1 semana    | 30/09/2024      |
| Diseño                    | 2 semanas   | 07/10/2024      |
| Codificación y pruebas    | 4 semanas   | 21/10/2024      |
| Entrega y despliegue      | 1 semana    | 25/11/2024      |
