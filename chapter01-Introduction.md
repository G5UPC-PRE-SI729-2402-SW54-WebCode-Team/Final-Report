# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos GreenGo, un startup conformado por 5 estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC),
que trabajará en el desarrollo del producto GreenMove, dedicada a facilitar el alquiler de vehículos eléctricos.
Nuestro enfoque se centra en brindar soluciones tanto para usuarios que buscan alquilar vehículos eléctricos para fines de
transporte como para personas que tienen vehículos eléctricos y buscan generar ganacias alquilandolo, nuestro objetivo es
facilitar el acceso a vehículos eléctricos de forma segura y conveniente para nuestros usuarios, nuestro sitio
web ofrece una experiencia excepcional, garantizando la disponibilidad y seguridad de sus vehículos.

<table border="1px" style="text-align: center; width: 100%;">
    <tbody>
        <tr>
            <td><strong>Misión</strong></td>
            <td><strong>Visión</strong></td>
            <td><strong>Valores</strong></td>
        </tr>
        <tr>
            <td>Transformar la movilidad urbana y recreativa con un acceso conveniente, económico y seguro a vehículos eléctricos.</td>
            <td>Ser líderes en el mercado de desarrollo de aplicaciones orientadas al cuidado del medio ambiente.</td>
            <td>
                <ul style="list-style-type:none; padding-left: 0;">
                    <li><strong>Innovación:</strong> La innovación constante para ofrecer soluciones creativas.</li>
                    <li><strong>Calidad:</strong> Buscamos la excelencia en nuestro producto.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

### 1.1.2. Perfiles de integrantes del equipo

<table border="1px" style="width: 100%; text-align: center;">
    <thead>
        <tr>
            <th>Integrante</th>
            <th>Foto</th>
            <th>Descripción del Perfil</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Adriana María Diestra Zambrano</td>
            <td><img src="/assets/Adriana.png" width="370"/></td>
            <td>Estudiante de la carrera Ingeniería de Software de 6to ciclo. Con conocimientos en C++, Python, HTML y CSS, así como una actitud positiva para trabajar en equipo, generando un ambiente tranquilo y responsable. </td>
        </tr>
        <tr>
            <td>Yair Christofer Aru Acevedo	</td>
            <td><img src="/assets/Yair.jpg" width="370"/></td>
            <td>Estudiante de 6to ciclo de la carrera de Ingenieria de Software. Conocimientos en vue y el uso de los lenguajes de programación: C++, C#, Javascript, Python, Java.</td>
        </tr>
        <tr>
            <td>Enrique Manuel Villon Amez	</td>
            <td><img src="/assets/Enrique.png" width="370"/></td>
            <td>Estudiante de quinto ciclo de la carrera de Ingeniería de Software en la UPC. Cuento con conocimientos avanzados en Swift y  Javascript  con sus frameworks o librerias mas populares (React, Angular, React Native), además profundos conocimientos en C++, Python, AWS). Actualmente soy Mobile Developer Senior en Auna tengo mas de 5 años en la industria tecnológica. Me considero una persona comunicativa y dedicada, me gusta el trabajo en equipo y la tecnología.</td>
        </tr>
        <tr>
            <td>Eduard Gedeon Travezaño Patiño	</td>
            <td><img src="/assets/FotoEduard.jpg" width="370"/></td>
            <td>Soy Eduard, tengo 20 años actualmente estoy cursando la carrera de Ingeniería de Software. Considero que soy alguien que se adapta a lo que requiera el trabajo, logrando aportar en este de buena manera, para asegurar un trabajo bien hecho. Con conocimientos en distintos lenguajes de programación como C++, Python, SQL y entre otros. Además mis motivaciones me ayudan a dar lo mejor de mí y mantenerme constante apoyando al equipo en lo que se requiera.</td>
        </tr>
        <tr>
            <td>Fabio Ernesto Horna Silva	</td>
            <td><img src="/assets/FabioHorna.jpg" width="370"/></td>
            <td>Soy Fabio, tengo 21 años y soy sumamente apasionado al análisis de datos y a los videojuegos. Actualmente me encuentro trabajando como analista de datos y poseo conocimientos avanzados de redes neuronales, SQL, y otras herramientas como Python, donde manejo pandas y otras herramientas para la minería de datos. Me considero una buena persona para trabajar en equipo y me gusta ayudar a mis compañeros.</td>
        </tr>
    </tbody>
</table>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Nuestra capital Lima, es una de las ciudades con mayor tráfico del mundo, lo que genera grandes costos económicos para las millones de personas que transitan diariamente por la ciudad de lima y callao, el sistema de transporte se encuentran notablemente retrasados. En el 2023 nuestra ciudad de Lima pasó del quinto al segundo país en el ranking de ciudades con mayor tráfico a nivel mundial. Según TomTom Traffic, trasladarse 10 kilómetros (distancia entre plaza San Martín y el Óvalo Naranjal al norte o al Larcomar al sur) demora 24 a 30 minutos en promedio.

<table border="1px" style="text-align: center; width: 100%;">
    <tr>
    <td valign="top"> What (Qué) </td>
    <td valign="top"> El problema identificado radica en el tráfico de Lima, que es uno de los más congestionados del mundo, generando costos económicos significativos y afectando la calidad de vida de millones de personas. </td>
   </tr>
    <tr>
        <td valign="top"> When (Cuándo) </td>
        <td valign="top"> El problema del tráfico se experimenta diariamente, especialmente durante las horas pico de la mañana y la tarde, afectando los desplazamientos laborales y personales. </td>
    </tr>
    <tr>
        <td valign="top"> Where (Dónde) </td>
        <td valign="top"> El tráfico congestionado se encuentra generalmente en las avenidas principales, intersecciones críticas y puntos de entrada y salida de la ciudad. </td>
    </tr>
    <tr>
        <td valign="top"> Who (Quiénes) </td>
        <td valign="top"> El problema afecta a todos los residentes y usuarios de Lima, que dependen del transporte terrestre para sus actividades diarias, incluidos trabajadores, estudiantes y visitantes. </td>
    </tr>
    <tr>
        <td valign="top"> Why (Por qué) </td>
        <td valign="top"> La congestion vehicular se debe a una combinación de factores, como el crecimiento poblacional desmedido, la falta de infraestructura vial adecuada, el aumento del parque automotor, la falta de sistemas de transporte público eficientes y sobre todo el desconocimiento de transportes alternativos. </td>
    </tr>
    <tr>
        <td valign="top"> How (Cómo) </td>
        <td valign="top"> Como una congestión constante en las vías principales, causando retrasos significativos en los tiempos de viaje y aumentando el estrés y la frustración de los usuarios. La congestión tiende a empeorar durante las horas pico y en días laborables. </td>
    </tr>
    <tr>
        <td valign="top"> How much (Cuánto) </td>
        <td valign="top"> La congestión vehicular causa un impacto diario a millones de personas, provocando retraso en sus actividades diarias, pérdida de productividad y el aumento en el coste de transporte que asciende a mas de 500 soles anuales por manejar en horas pico o la alza de pasajes en el transporte público que a aumentado en casi 100 soles mensuales desde 2010. </td>
    </tr>
</table>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem statements


1.  Alta congestión vehicular en Lima: La alta congestión vehicular en Lima afecta negativamente la movilidad urbana, causando largos tiempos de desplazamiento y contribuyendo a la contaminación del aire. Esta situación limita la calidad de vida de los residentes y plantea un desafío significativo para la adopción de soluciones de transporte más sostenibles.

- **Owner:** Propietarios que desean contribuir a la reducción de la congestión vehicular al alquilar sus vehículos eléctricos, pero enfrentan dificultades para conectar con usuarios interesados en utilizar estos vehículos como alternativa al transporte convencional.
- **Cliente:** Personas que desean evitar el tráfico congestionado y reducir su impacto ambiental al elegir vehículos eléctricos, pero enfrentan desafíos para encontrar opciones disponibles y accesibles.
  
2.  Ineficiencia en el transporte público de Lima: El sistema de transporte público en Lima está notablemente retrasado y no satisface adecuadamente las necesidades de los residentes, contribuyendo a la alta congestión vehicular. Los tiempos prolongados de desplazamiento y la falta de alternativas rápidas y eficientes agravan el problema, afectando la movilidad diaria de millones de personas.

- **Owner:** Propietarios que desean alquilar sus vehículos eléctricos pero enfrentan dificultades debido a la alta congestión causada por un sistema de transporte público ineficiente, que limita la demanda y el uso de sus vehículos como alternativa efectiva.
- **Cliente:** Residentes que buscan alternativas de transporte más eficientes debido a la ineficiencia del transporte público, deseando una solución que ofrezca tiempos de viaje más cortos y una experiencia de movilidad más cómoda.
  
3.  Costos elevados de transporte convencional: Con el aumento constante de los precios del combustible, los usuarios de transporte ecológico enfrentan altos costos asociados con el uso de vehículos convencionales, lo que impulsa la búsqueda de opciones más económicas y sostenibles.

- **Owner:** Propietarios que ven en el alquiler de sus vehículos eléctricos una forma de contrarrestar el impacto financiero de los altos precios del combustible, generando ingresos adicionales.
- **Cliente:** Personas que desean reducir sus gastos en transporte y están motivadas a buscar alternativas más económicas debido al incremento de los precios del combustible.
  
4.  Necesidad de información sobre el impacto ambiental: Los usuarios de transporte ecológico quieren conocer el impacto ambiental de sus decisiones de transporte, pero a menudo carecen de información clara y accesible sobre cómo sus elecciones contribuyen a la sostenibilidad.

- **Owner:** Propietarios interesados en demostrar el impacto positivo de sus vehículos en el medio ambiente a los usuarios y así atraer más interés en el alquiler de sus vehículos.
- **Cliente:** Personas que buscan no solo alternativas de transporte sostenibles, sino también información sobre cómo su uso contribuye a la reducción de la huella de carbono.
  
5.  Pérdida de productividad debido a la congestión: La congestión vehicular en Lima resulta en pérdida de productividad significativa para los residentes debido a los largos tiempos de desplazamiento. Esto afecta negativamente tanto a las personas que se desplazan diariamente como a los propietarios de vehículos que buscan maximizar el uso de sus vehículos eléctricos en un entorno congestionado.

- **Owner:** Propietarios que buscan optimizar el uso de sus vehículos eléctricos y contribuir a la reducción del tráfico, pero enfrentan dificultades debido a la alta congestión que limita la efectividad de sus vehículos como solución a la pérdida de productividad.
- **Cliente:** Personas que desean reducir el tiempo perdido en el tráfico para aumentar su productividad diaria, buscando alternativas de transporte que puedan ofrecerles una experiencia más eficiente y menos estresante.

  
6.  Acceso limitado a transporte ecológico: En áreas urbanas con alta congestión vehicular y escasas opciones de transporte sostenible, los usuarios de transporte ecológico enfrentan dificultades para encontrar vehículos eléctricos accesibles y en buen estado. Esto se traduce en una experiencia de movilidad insatisfactoria y un aumento en el uso de medios de transporte menos sostenibles.

- **Owner:** Individuos que poseen vehículos eléctricos pero no los utilizan regularmente y desean encontrar una plataforma que facilite el alquiler de sus vehículos de manera eficiente.
- **Cliente:** Personas jóvenes y adultas que buscan alternativas sostenibles para sus desplazamientos diarios pero encuentran que las opciones disponibles son limitadas o difíciles de acceder.
  

#### 1.2.2.2. Lean UX Assumptions

- Business Outcomes

1. Aumentar el número de usuarios registrados en la plataforma en un 30% en los primeros 6 meses, como resultado de la creciente demanda de transporte eficiente y ecológico.
2. Expandir las fuentes de ingresos a través de la inclusión de diferentes tipos de vehículos y tarifas, optimizando las ganancias por alquiler.
3. Lograr una tasa de satisfacción del cliente del 85% o más, derivada de la facilidad de uso de la plataforma y la experiencia positiva del usuario.
  
- Users Outcomes

1. Los usuarios podrán encontrar y reservar vehículos eléctricos de manera rápida y sencilla, lo que mejorará su experiencia de movilidad diaria.
2. Al optar por vehículos eléctricos en lugar de vehículos convencionales, los usuarios podrán reducir significativamente sus gastos de transporte, especialmente en un contexto de precios de combustible elevados.
3. Los usuarios experimentarán una mayor satisfacción emocional al saber que están contribuyendo a la reducción de la huella de carbono, lo que también fortalecerá su conexión con GreenMove.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** al simplificar el proceso de registro en nuestra plataforma, aumentaremos la cantidad de nuevos usuarios. **Sabremos que** hemos tenido éxito **cuando** observemos un aumento significativo en el número de cuentas creadas en los primeros 7 días después del lanzamiento.

- **Creemos que** al facilitar la información de cada vehículo disponible, aumentaremos la cantidad de usuarios que alquilen un vehículo. **Sabremos que** hemos tenido éxito **cuando** observemos un aumento significativo en el número de personas que pongan en alquiler sus vehículos.

- **Creemos que** al ofrecer una plataforma de alquiler de vehículos eléctricos, reduciremos la congestión vehicular en Lima. **Sabremos que** hemos tenido éxito **cuando** observemos un aumento en la adopción de vehículos eléctricos y una disminución en la congestión en áreas clave de la ciudad.
  
- **Creemos que** al ofrecer una opción de alquiler de vehículos eléctricos como alternativa al ineficiente sistema de transporte público, los residentes podrán experimentar tiempos de viaje más cortos y una movilidad más cómoda. **Sabremos que** hemos tenido éxito **cuando** veamos una mayor utilización de los vehículos eléctricos en lugar del transporte público.

- **Creemos que** ofrecer vehículos eléctricos a precios competitivos atraerá a quienes buscan reducir costos de transporte. **Sabremos que** hemos tenido éxito **cuando** veamos un incremento en la demanda de alquiler de vehículos eléctricos.
  
- **Creemos que** proporcionando información clara sobre el impacto ambiental, atraeremos a usuarios interesados en reducir su huella de carbono. **Sabremos que** hemos tenido éxito **cuando** aumente la adopción de vehículos eléctricos y la interacción con la información ambiental.

- **Creemos que** al ofrecer vehículos eléctricos, ayudaremos a los residentes a reducir el tiempo perdido en el tráfico y mejorar su productividad. **Sabremos que** hemos tenido éxito **cuando** mejore la percepción de eficiencia del transporte y se reduzcan los tiempos de desplazamiento.

#### 1.2.2.4. Lean UX Canvas

<img src="/assets/Lean UX Canvas.png"/>

## 1.3. Segmentos Objetivo

- **Owner:** Este segmento está compuesto por propietarios de vehículos eléctricos que residen en áreas urbanas densas (Lima) y que buscan generar ingresos adicionales al alquilar sus vehículos cuando no los están utilizando. Estos propietarios son conscientes del valor económico de sus activos y están interesados en maximizar el retorno sobre su inversión. Además, tienen una fuerte orientación hacia la sostenibilidad y desean participar activamente en la economía colaborativa. Son personas que valoran tanto la rentabilidad como la contribución a un transporte más limpio en su ciudad.
    - **Ocupación:** Profesionales, empresarios, o individuos con conciencia ambiental y sentido de responsabilidad social.
  - **Motivaciones:** Maximizar la rentabilidad de un activo subutilizado, contribuir a la reducción de emisiones y fomentar el uso de transporte sostenible en la comunidad.
  - **Comportamiento:** Están abiertos a plataformas digitales que ofrecen seguridad, control y conveniencia en la gestión del alquiler de su vehículo.
- **Cliente:** Este segmento incluye a profesionales jóvenes y familias pequeñas que viven en grandes ciudades y buscan soluciones de transporte que sean sostenibles, asequibles y convenientes. Son personas con un fuerte sentido de responsabilidad ambiental que buscan minimizar su impacto ecológico, pero también necesitan opciones de movilidad que se adapten a sus estilos de vida urbanos ocupados. Además, valoran la flexibilidad de alquileres de corto o mediano plazo, sin el compromiso de poseer un vehículo.
    - **Ocupación:** Profesionales, freelancers, familias jóvenes, estudiantes de posgrado.
    - **Motivaciones:** Reducir la huella de carbono, evitar el tráfico y la congestión, opciones de transporte asequibles, cómodas y sin complicaciones.
    - **Comportamiento:** Prefieren opciones de movilidad que ofrezcan flexibilidad y conveniencia, utilizan aplicaciones móviles para la gestión de servicios diarios, y están dispuestos a pagar un poco más por opciones ecológicas.
