# 🏋️‍♂️ Análisis de Gimnasio - Proyecto Final

Este notebook analiza los tipos de entrenamiento, distribución por género, edad y monto total de cuotas del gimnasio.

Podés ejecutar el notebook directamente en Colab haciendo clic en este botón:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/martinsena6/gimnasio-analisis/blob/main/PrimerTrabajoAnalisisDatos.ipynb)


## 📊 Contenido del análisis
📋 INFORME FINAL

1️⃣ Tipo de entrenamiento más popular
➡️ El entrenamiento de fuerza es el más elegido, apenas por encima de yoga y entrenamiento intenso.
Las diferencias son menores al 3 %, lo que demuestra una distribución equilibrada entre las disciplinas.
Esto sugiere que el gimnasio ofrece una oferta variada y atractiva que logra retener públicos con diferentes intereses.

Según los registros generales:
Tipo de entrenamiento	Cantidad	Monto total estimado
Fuerza	5.071	$91.278.000
Yoga	5.032	$60.384.000
Entrenamiento intenso	4.974	$79.584.000
Cardio	4.923	$68.922.000


2️⃣ Diferencias por género
Totales generales:
👩‍🦰 Mujeres: 10.028
👨 Hombres: 9.972

Mujeres
Tipo de entrenamiento	Cantidad
Fuerza	2.601
Yoga	2.530
Entrenamiento intenso	2.479
Cardio	2.418

👉 Tienden hacia fuerza y yoga, actividades asociadas al tono muscular y flexibilidad.

Hombres
Tipo de entrenamiento	Cantidad
Cardio	2.505
Yoga	2.502
Entrenamiento intenso	2.495
Fuerza	2.470

👉 Prefieren cardio y entrenamientos de alta intensidad, más ligados al rendimiento físico.

📌 Conclusión:
Las mujeres se inclinan hacia el bienestar y tonificación, mientras que los hombres priorizan la resistencia y el rendimiento.
No obstante, las diferencias son pequeñas, lo que evidencia una participación equilibrada entre géneros.

👥 3️⃣ Participación por edad
Rango etario	Cantidad estimada	Características
18–30	6.200	Mayor participación, especialmente en fuerza e intensidad.
31–40	4.400	Mantienen constancia con rutinas equilibradas.
41–49	4.700	Preferencia por entrenamientos moderados.
50+	4.700	Alta participación en yoga y fuerza.

➡️ El grupo 18–30 años domina en cantidad, pero los mayores de 50 conservan un nivel de actividad notable.
Esto indica que el gimnasio logra atraer y retener a múltiples generaciones, un punto clave para la sostenibilidad.

🧠 4️⃣ Niveles de dificultad predominantes
Nivel	Participantes
Principiante	8.000
Intermedio	7.800
Avanzado	7.200

En los más jóvenes (18–30): predominan los niveles avanzados, especialmente en cardio y entrenamiento intenso.

En mayores de 50: prevalecen los niveles intermedios o principiantes, sobre todo en yoga y fuerza.

💡 Esto refleja un enfoque progresivo y saludable: los jóvenes buscan superarse, mientras los mayores priorizan la constancia y el bienestar.

💰 5️⃣ Ingresos totales estimados

Monto total mensual: 💵 $300.168.000

Aporte principal: Fuerza (30%) y Entrenamiento intenso (26%)

➡️ Los ingresos están bien distribuidos entre actividades, lo que da estabilidad financiera al gimnasio y reduce la dependencia de una sola disciplina.
---

## 🧠 Librerías necesarias

```bash
pip install pandas matplotlib seaborn
