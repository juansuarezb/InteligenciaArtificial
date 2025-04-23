> [!IMPORTANT]
> ## CLASE 3
> ## 22/04/2025

> [!TIP]
> **¿Que es inteligencia?** <br>
> Inteligencia : Capacidad de aprender, razonar y resolver problemas. <br>
> **¿Que es la ia?** <br>
> Campo de estudio que busca crear sistemas capaces de realizar tareas que requierem inteligencia humanda <br>
> **IA DEBIL** <br> 
> Tambien llamada "ia estrecha", diseñada para realizar tareas espeficicas, no tiene consciencia ni entendimiento real.<br>
> Ejemplos: Siri, Alexa, recomendaciones de netflix, ia para diagnostico médico. <br>
> **IA FUERTE**<br>
> Tambien llamada ia general o AGI (Artificial general intelligence) <br>
> Busca replicar la inteligencia humana en toda su amplitud. <br>
> Capaz de razonar, planear, aprender, comprender emociones. <br>
> Aún no existe en la práctica.

> [!NOTE]
> | Tipo IA | Descripción |
> |------------|-----------|
> | **IaGeneral(IAG)** | Ciencia ficción, puede ocuparse de cualquier tarea en general. |
> | **IaFuerte** | Equivaldria a una mente verdaderamente inteligente y consciente de si misma. |
> | **IaEstrecha(Limitada)** | Es aquella que se ocupa de una sola tarea. | 
> | **IaDebil** | Sistemas que muestran comportamientos inteligentes a pesar de ser computadoras. |

> [!IMPORTANT]
> <p><strong>Tarea: </strong>Ver el <a href="https://www.youtube.com/watch?v=5rvZBsueMoc"> video </a> completo e identificar que tecnica de ia se esta implementando en cada ejemplo</p><br>
> <sectipn>
> <figure>
> <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/ajedrez.avif" alt="imagenAjedrez" width="60%"/>  
> </figure> <br>
> <figcaption><strong>Caso3: El enfrentamiento entre Garry Kasparov y Deep Blue</strong></figcaption>
> <ol><a href="https://stanford.edu/~cpiech/cs221/apps/deepBlue.html"><strong>Técnicas utilizadas: </strong></a>
>    <li><details><summary><strong>Tree Search</strong></summary>
>     </details></li>
>    <li><strong>The Evaluation Function</strong></li>
>    <li><strong>The Minimax Algorithm</strong></li>
>    <li><details><summary><strong>Heuristics</strong></summary>
>    <p>La <strong>Función heurística</strong> se utiliza para gestionar arboles de juegos gigantescos.</p>
>    </details></li>  
> </ol>
> </section>

  
> <section>
> <figure>
> <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/watson.avif" alt="imagenWatson" width="60%"/>  
> </figure> <br>
> <figcaption><strong>Caso1: Watson</strong></figcaption>
> <section>
> <figure>
> <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/imageCaso2.avif" alt="imagenCaso2" width="60%"/>
> </figure> <br>
> <figcaption><strong>Caso2: Carros Autónomos</strong></figcaption>
> <p>La preocupación de utilizar estas tecnologías se basa en el instinto y algunas son: </p>
> <ul>
> <li>El auto ve las cosas como yo veo?</li>
> <li>El auto actua de la forma en la que yo actuaria basado en las cosas que ve?</li>  
> </ul>
> <p>El auto debe tener una percepión (las cosas que ve) y averigua cuales son objetos, carriles, etc. Tambíen, una capacidad de predicción (como se mueven los objetos) finalmente, en base a estos 2 puntos una planificación (a donde tiene que ir)</p>
> <p>El <strong>Aprendizaje Profundo </strong> ayuda al auto a entender los elementos externos (ej. Niños jugando con una pelota al costado).</p>  
> <p>Aprende a crear un simulador de un autoautonomo en javascript <a href="https://www.youtube.com/watch?v=Rs_rAxEsAvI">aquí.</a></p>
> </section>

> [!NOTE]
> <p>Los autos autónomos requieren de una combincación de diversos tipos de IA</p>
> <ul>
> <li><strong>Búsqueda y planificación:</strong> Para hallar la ruta más conveniente de A->B </li>
> <li><strong>Toma de decisiones en situaciones de incertidubmre</strong></li>
> <li><strong>Visión mediante ordenador</strong></li>  
>  </ul>

> [!NOTE]
> <p>Muchos problemas pueden formularse como <strong><em>problemas de búsqueda</em></strong></p>
> <p>Para ello se <strong>plantean las opciones alternativas y sus consecuencias</strong></p>

> [!TIP]
> <section>
> <h3>Aprendizaje Automático</h3>
> <p>En el aprendizaje automatico una computadora analiza datos, encuentra patrones y utiliza estos patrones para encontrar la mejor ruta hacia un objetivo</p>
> <figure>
> <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/recomendacion.avif" alt="imagenAjedrez" width="60%"/> 
> </figure> <br>

> [!NOTE]
> <p><strong>Burbujas de filtro</strong></p>
  
> <figcaption><strong>Caso 4: Ia de recomendación de canciones de Spotify</strong></figcaption> <br>
> <figure>
>  <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/SpaceInvaders.avif" alt="DeepMind vs SpaceInvaders" width="60%"/>
> </figure> <br>  
> <figcaption><strong> 2013 - Ia de Google DeepMind aprendiendo a jugar SpaceInvaders</strong></figcaption> <br>
> <h4>Deep Q-learning</h4>
> <p>Lo único que tiene a disposición el agente es un input de lo que ve la en la pantalla y así, se le ordenó maximizar el puntaje de la pantalla</p>
> <p>No hay un <strong>Dominion del conocimiento</strong> previo, (esto quiere decir que el algoritmo no entiende el concepto de bola ni lo que hacen los controles)</p>
> <p>Mira el código original del agente <a href="https://github.com/kuz/DeepMind-Atari-Deep-Q-Learner"> aquí.</a></p>
> <p>Más información <a href="https://medium.com/@prmj2187/mastering-atari-with-deep-q-learning-6d8b2138491c"> aquí.</a></p>  
> <figure>
>  <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/Go.avif" alt="DeepMind vs SpaceInvaders" width="60%"/>
> </figure> <br>
> <figcaption><strong> 2017 - (AlphaGo Cero) La misma técnica es utilizada para un juego muy complicado (GO)</strong></figcaption>
> <p>Esta ia aprendió a jugar Go consigo mismo de la manera más humana posible (prueba-error) </p>  
> </section>
> <section>
> <figure>
>   <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/sawyer.avif" alt="robotSawyer" width="60%"/> 
> </figure> <br>
> <figcaption>Robot sawyer, Robot compañero de humanos en pequeñas fábricas de Boston.</figcaption>
> <p>Sawyer aprende por demostración no por programación. Puede ser capacitado para diferentes tareas.</p>
> <p>Se entrena al robot como se entrenaría a una persona.</p>  
> </section>
> <section>
> <figure>
>  <img src="https://github.com/juansuarezb/InteligenciaArtificial/raw/Semana2/Imagenes/bostonD.avif" alt="Robot BostonDynamics" width="60%"/>
> </figure> <br>
> <figcaption>El robot BostonDynamics </figcaption>  
> </section>

> [!IMPORTANT]
> ## CLASE 4
> ## 23/04/2025


[![Semana1](https://img.shields.io/badge/🏠_Volver_a_Semana1-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/juansuarezb/InteligenciaArtificial/blob/Semana1/README.md)

[![Semana3](https://img.shields.io/badge/🏠_Ir_a_Semana3-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/juansuarezb/InteligenciaArtificial/blob/Semana3/README.md)
