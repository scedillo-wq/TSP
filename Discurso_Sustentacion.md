# Discurso de sustentación · 15 minutos

Guion para las 20 diapositivas. Son 1985 palabras: a un ritmo de 135 palabras por minuto dura 14:42. Los tiempos son acumulados, para que ensayes con cronómetro.

El mismo texto está en las notas del orador de cada diapositiva (en PowerPoint: *Presentación con diapositivas → Vista del moderador*).

## 1. Portada · 0:00–0:23

Buenos días, señores miembros del jurado. Mi nombre es Samir Cedillo y presento mi trabajo de suficiencia profesional: la recuperación de los indicadores de mantenimiento de la flota 980E-5 de acarreo minero, afectados por la falla del eje palier del sistema de propulsión, desarrollado con la asesoría del ingeniero Carlos Juárez.

## 2. Metas contractuales · 0:23–1:08

El punto de partida no fue una falla, sino un contrato. La flota está formada por diez camiones 980E-5 de 400 toneladas con propulsión eléctrica, cuyo mantenimiento integral está a cargo de una empresa contratista. El contrato se mide con tres indicadores: 91 % de disponibilidad física, 64,5 horas de MTBF y un MTTR máximo de 4 horas. Como muestran las gráficas, entre 2022 y 2024 la disponibilidad no alcanzó la meta en ningún año y el MTBF se mantuvo por debajo de su objetivo. El contrato estaba expuesto a penalización, por la frecuencia de las fallas y por reparaciones de larga duración.

## 3. La falla más crítica · 1:08–2:00

Al revisar qué fallas explicaban esa brecha, una destacó sobre las demás: la fractura por fatiga del eje palier del motor de tracción. En 36 meses se registraron 13 eventos. Cada uno detuvo el equipo 59,3 horas en promedio y obligó a una evaluación y reparación mayor del motor de 763 mil dólares. En conjunto, consumía 0,36 puntos de disponibilidad de flota, una parte importante de la brecha con la meta. Lo más revelador es que cada evento tuvo su análisis de falla y su informe metalográfico y, aun así, la falla persistió y reapareció en posiciones ya intervenidas. El eje no llegaba al TBO de 20 000 horas: entregaba una vida inferior a la planificada.

## 4. Objetivos · 2:00–2:35

De ahí se desprende el objetivo general: recuperar el MTBF, el MTTR y la disponibilidad del motor de tracción eliminando la fractura del eje palier. Para lograrlo planteé cuatro objetivos específicos. Primero, identificar la falla recurrente y cuantificar su impacto. Segundo, determinar sus causas latentes mediante un análisis de causa raíz. Tercero, implementar el rediseño de la unión soldada, sustentado en la lógica de decisión del RCM. Y cuarto, evaluar la recuperación de los indicadores y el costo evitado.

## 5. Etapas de la metodología · 2:35–3:24

La metodología sigue cuatro etapas: el cálculo de los indicadores y de la desviación contractual; la focalización mediante una matriz de criticidad; el proceso RCM, respondiendo en secuencia las siete preguntas de la norma SAE JA1011; y la implementación como cambio controlado, con su verificación. Dos precisiones sobre el proceso RCM. La pregunta 3, sobre los modos de falla, se respondió en profundidad con un análisis de causa raíz, y dentro de él los análisis de falla resolvieron el nivel físico. Y las preguntas 6 y 7 forman la lógica de decisión: una tarea proactiva solo se adopta si es técnicamente factible y si su beneficio supera su costo.

## 6. Focalización · 3:24–4:13

La primera decisión fue sobre qué modo de falla trabajar. La matriz de criticidad combina la frecuencia con cuatro dimensiones de consecuencia: seguridad, operación, costo e impacto contractual. El eje palier obtiene la frecuencia máxima, 5, con 4,33 eventos por año, y nivel 4 en todas las consecuencias: pérdida de tracción y de retardo dinámico en rampa, 59,3 horas de reparación, más de 760 mil dólares por evento y 0,36 % de disponibilidad. Además, su detectabilidad es la peor posible, porque la grieta nace dentro del motor cerrado. Eso lo ubica en el cuadrante de criticidad máxima, donde la acción que corresponde no es inspeccionar más, sino eliminar la causa raíz.

## 7. Preguntas 1 y 2 · 4:13–4:56

Con el activo delimitado, respondí las dos primeras preguntas. La función del eje palier es transmitir a la rueda el par del motor de inducción, con una reducción de 35 a 1, y sostener la tracción y el retardo dinámico durante 20 000 horas entre reparaciones mayores. La falla funcional es que deja de transmitir ese par: la rueda queda libre, lo que se conoce como free wheeling. El monitor del equipo lo registra con claridad: el canal M1 marca 2 545 rpm frente a 10 rpm del M2, con par nulo y el código 775-1.

## 8. Pregunta 3: quince hipótesis · 4:56–5:33

La pregunta 3 es el núcleo del trabajo. Formulé quince hipótesis, organizadas en cinco familias: diseño, fabricación, montaje, operación y mantenimiento, y contrasté cada una con evidencia. El criterio fue estricto: una hipótesis se descartaba solo si era incompatible con la evidencia, no por parecer menos probable. Trece quedaron descartadas y dos se confirmaron, ambas en la rama de diseño: la raíz sin fusión de la unión soldada de penetración parcial, como causa determinante, y la sección resistente insuficiente del tubo, como causa contribuyente.

## 9. Diagrama de Ishikawa resuelto · 5:33–6:22

Este es el diagrama de Ishikawa resuelto: las quince hipótesis en sus cinco familias, cada una marcada como confirmada o descartada con evidencia. Esa evidencia provino de los análisis de falla. Los AFA de campo muestran la misma firma en todos los eventos: origen en el diámetro interior, en la raíz de la soldadura. El laboratorio externo confirmó que el material es conforme, y el AFA 01-23040 encontró la operación dentro de parámetros. Por eso solo la espina de diseño queda en rojo: penetración parcial con raíz sin fusión y espesor de pared insuficiente. Aun así, cada AFA resolvió su evento, pero ninguno consolidó la recurrencia. Volveré sobre este punto.

## 10. Verificación de la causa física · 6:22–7:08

Esta es la verificación de la causa física. A la izquierda, el eje F1 en campo: el sector oscuro y liso es la propagación estable de la grieta, el sector claro y granular es la rotura final, y el origen está en el diámetro interior. Al centro, la fractografía muestra marcas de trinquete, que indican nucleación múltiple, y una zona de fractura final de apenas el 20 %. A la derecha, la macrografía ubica la iniciación en una discontinuidad tipo grieta en la raíz de la unión. Una rotura final tan reducida indica que el eje operó mucho tiempo con la grieta avanzando.

## 11. Descarte de la operación · 7:08–7:54

Luego había que descartar la operación, y se hizo con la data del propio equipo. En el CM403, la carga útil media fue de 366,7 toneladas, sin ningún ciclo por encima del 120 %; no hubo sobrevelocidad; el peso suspendido se mantuvo bajo las 800 toneladas; y el grado efectivo quedó por debajo del promedio de comparación. Pero el argumento decisivo no es la comparación de valores, sino la distribución de los eventos: una causa operacional se concentraría en las unidades o rutas con la desviación, y esta fractura aparece de forma transversal en toda la flota y en un rango amplio de horas.

## 12. Descarte de la fabricación · 7:54–8:46

Quedaba la fabricación. El material se descartó con los ensayos del laboratorio: su composición es compatible con el acero ASTM A618 grado III, con 212 HBW de dureza, 619 MPa de fluencia y 717 MPa de resistencia a la tracción. Para distinguir entre un defecto de fabricación y un problema de diseño, la prueba la dio la propia operación: en los motores reparados se instaló un eje nuevo, con el mismo número de parte, y la fractura volvió a aparecer en el mismo lugar y con el mismo patrón. Si fuera un defecto de una pieza o de un lote, la pieza nueva lo habría eliminado. La única condición común era la geometría de la unión soldada.

## 13. Verificación por resistencia de materiales · 8:46–9:34

Hasta aquí, el diseño quedó identificado por eliminación; la verificación por resistencia de materiales lo confirma de forma independiente. El par transmitido en la posición es de 17,81 kN·m, que genera un esfuerzo cortante nominal de 35,7 MPa y un rango de esfuerzo de 53,6 MPa. Por su raíz sin fusión, la unión se clasifica como detalle FAT 36, y con esos valores el factor de seguridad a la vida planificada es de 0,31. Un factor menor que uno significa que la unión, tal como estaba diseñada, no podía alcanzar la vida planificada bajo el par nominal. La fractura no era una anomalía: era el comportamiento esperado del diseño.

## 14. Del mecanismo físico a la causa latente · 9:34–10:27

Pero explicar la fractura no bastaba. La pregunta de fondo era por qué la organización convivió tres años con un modo de falla de criticidad máxima. El análisis descendió en cuatro niveles. En el físico, la raíz sin fusión nuclea la grieta. En el humano, el componente se recibía con su diseño predeterminado, sin verificar su resistencia. Y en el latente, dos causas de sistema: cada análisis de falla se hacía por evento y ninguno consolidaba el conjunto de casos, y no existía un proceso que asignara responsable, plazo y cierre a sus recomendaciones. La causa raíz latente es la ausencia de un mecanismo que convierta el hallazgo de un análisis de falla en un cambio de diseño.

## 15. Preguntas 6 y 7 · 10:27–11:15

Con las causas identificadas, las preguntas 6 y 7 definen qué hacer. La tarea a condición no es factible: la grieta nace en la raíz interna y no hay acceso de inspección. El reacondicionamiento cíclico tampoco, porque no restituye la resistencia de la soldadura. La sustitución cíclica a la vida B10 sí es factible, pero no conveniente: costaría 4,3 millones de dólares al año frente a 3,05 millones de consecuencias evitadas. Descartadas las tres, y tratándose de una consecuencia operacional con implicación de seguridad, la norma prescribe la acción a falta de: el rediseño. Quiero subrayarlo: el rediseño es el resultado del proceso RCM, no su punto de partida.

## 16. La solución y su implementación · 11:15–12:09

La solución es el cambio de la unión soldada. El componente obsoleto tenía una soldadura de penetración parcial con raíz sin fusión y un factor de seguridad de 0,31. El mejorado tiene penetración completa sobre una sección mayor, con el mismo material, y su factor sube a 2,23. Es una mejora del fabricante, no un desarrollo propio: surgió de las recomendaciones de los AFA, y esta operación fue la primera en implementarla, en 2025. Se ejecutó como cambio controlado, en tres pasos: priorizando las posiciones con más horas acumuladas, reemplazando el motor completo por uno de intercambio con el nuevo número de parte, y registrando el número de parte instalado en cada posición, para que el obsoleto no vuelva a montarse.

## 17. Verificación del componente · 12:09–13:00

La verificación se hizo en dos niveles. En el del componente, con el número de parte mejorado la flota acumuló 96 000 horas de operación sin una sola fractura desde diciembre de 2024. Con la tasa anterior se habrían esperado 6,3 eventos, y la probabilidad de observar cero si nada hubiera cambiado es de 0,0018. Por eso se rechaza, con 95 % de confianza, que el modo de falla persista. El MTBF del modo pasa de 15 231 horas a más de 32 046, por encima del TBO, y el MTTR del sistema de propulsión baja de 6,2 a 3,3 horas. La verificación seguirá abierta hasta que las unidades superen el rango de vidas observado.

## 18. Verificación de la flota y costo evitado · 13:00–13:43

En el nivel de la flota, 2025 es el primer año del período en que se cumplen ambos compromisos contractuales: 93,6 % de disponibilidad y 108,4 horas de MTBF. Aquí debo ser preciso con la atribución: en el mismo período se intervino el motor diésel por fisura de culatas, y esa acción explica parte de la mejora. El aporte del eje palier es de 0,36 puntos de disponibilidad, y el rediseño se acredita en el nivel del componente, donde el efecto sí es atribuible. En términos económicos, el modo eliminado costaba 3,05 millones de dólares al año.

## 19. Conclusiones · 13:43–14:35

Para concluir. Primero, el modo de falla tenía un impacto medible: 4,33 eventos por año, 59,3 horas por evento y 0,36 puntos de disponibilidad. Segundo, su causa física es la raíz sin fusión, con un factor de seguridad de 0,31, y debajo de ella había causas de sistema. Tercero, el rediseño fue el desenlace de la lógica RCM, no una decisión previa, y eleva el factor de seguridad de 0,31 a 2,23 sin cambiar el material. Y cuarto, la recuperación está verificada: 96 000 horas sin fracturas. El aporte de la ingeniería de confiabilidad no fue explicar por qué se fracturaba el eje, sino eliminarlo como modo de falla con la lógica de decisión del RCM.

## 20. Cierre · 14:35–14:42

Con esto concluyo mi presentación. Muchas gracias por su atención; quedo atento a sus preguntas y comentarios.

## Si vas justo de tiempo

Las diapositivas 7 (preguntas 1 y 2), 9 (Ishikawa) y 11 (operación) admiten una versión de una o dos frases sin perder el hilo: la función y la falla funcional, “solo la espina de diseño queda confirmada” y “la operación está dentro de parámetros y la falla es transversal a la flota”. Así se recupera cerca de un minuto.
