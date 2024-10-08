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
   - La mayoría de los agricultores dependen de las **subvenciones de la PAC**, que pueden representar hasta el **30%-40%** de sus ingresos.

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
   - Si la plataforma cobra una comisión del **5%**, el agricultor pagaría **200 euros** de comisión por esos 4.000 euros en ventas, lo que le dejaría un ingreso neto de **3.800 euros**.

#### Diferencia con la situación actual

En este ejemplo, el agricultor podría generar entre **3.600 y 4.000 euros adicionales** al año gracias a la venta directa a través de la plataforma. Para un agricultor que actualmente obtiene un beneficio neto de **10.000 euros**, esto podría aumentar sus ingresos a **14.000 euros**, lo que representa una mejora de hasta un **40%** en su rentabilidad.

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

El segmento de clientes principales serán agricultores pequeños y medianos en España que buscan mejorar sus ingresos vendiendo directamente al consumidor final. Asimismo, los consumidores interesados en productos frescos y locales forman el otro segmento clave.

### 2.4- Competencia

El proyecto competirá con plataformas de distribución de alimentos y grandes supermercados online. Sin embargo, el marketplace se diferenciará por su enfoque en el comercio directo sin intermediarios, ofreciendo precios más justos tanto para el agricultor como para el consumidor.

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
    - Servidor/hosting web: El costo de un servidor para alojar una plataforma con tráfico moderado podría oscilar entre 20 EUR y 50 EUR/mes si se utiliza un servidor en la nube como AWS o DigitalOcean.
        - Coste anual del hosting: entre 240 EUR y 600 EUR.
    - Dominio web: Aproximadamente 10-20 EUR/año.
    - Certificado SSL: Recomendado para asegurar la página, costando alrededor de 50 EUR/año.

- Desarrollo y mantenimiento:
    - Desarrollo de la plataforma: Dado que planeo desarrollarlo yo mismo, no tendría que contar con los gastos de contratar a un programador. Sin embargo, para el mantenimiento y posibles actualizaciones futuras, podrías necesitar un presupuesto anual de 2,000 EUR.

- Marketing:
    - Para dar a conocer el marketplace entre agricultores y consumidores, se necesitará invertir en publicidad digital. Un presupuesto inicial de marketing de 500 EUR sería razonable para campañas de redes sociales y SEO.

#### 2.7.2- Ingresos Estimados

El modelo de ingresos estará basado en una comisión por cada venta realizada a través de la plataforma. Aquí una estimación con números:

- Comisión por producto vendido: Suponemos una comisión del 10% por cada transacción realizada en la plataforma.

- Ventas iniciales estimadas: Para una estimación inicial conservadora, podríase calcular que durante los primeros 6 meses, se realicen unas 300 transacciones mensuales, con un precio promedio por transacción de 20 EUR.

- Ventas mensuales estimadas: 300 transacciones × 20 EUR = 6,000 EUR/mes.
- Comisión mensual generada (10% de 6,000 EUR): 600 EUR/mes.
- Ingresos anuales estimados: 600 EUR × 12 meses = 7,200 EUR/año.

Resumen Financiero

Concepto | Costo (EUR)
--- | ---
Capital social mínimo | 3,000
Gastos de constitución | 500
Ordenador para desarrollo | 1,000
Hosting (anual) | 240 - 600
Dominio (anual) | 20
Certificado SSL (anual) | 50
Mantenimiento anual | 2,000
Marketing inicial | 500
Total costos iniciales (primer año) | 7,310 - 7,670

- Ingresos estimados anuales: 7,200 EUR.
- Balance final del primer año: Ingresos (7,200 EUR) - Costos (7,310 EUR) = -110 EUR (cercano al equilibrio).

En el segundo año, los costos disminuirían (sin capital social ni constitución) y los ingresos podrían aumentar con más usuarios, lo que podría llevar a un resultado positivo.

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
