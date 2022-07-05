# Barrio ideal en CABA
Trabajo final grupal para el curso de Data Analytics con R de la Escuela Argentina de Nuevas Tecnologías (EANT)

R
Datos abiertos de CABA
Librerias de R (tidyverse, ggplot2, dplyr, sf, janitor, ggmap, leaflet, reshape)

El objetivo del trabajo fue explorar ¿Cuál es tu barrio ideal en la Ciudad Autónoma de Buenos Aires (CABA, Argentina)? Al elegir en donde vivir, cada persona tiene distintas preferencias en cuanto a que es imprescindible y debe tener el lugar ideal. Definimos 6 criterios que consideramos podrían definir la búsqueda del barrio ideal, estos son:

    disponibilidad de escuelas,
    espacios deportivos,
    precio de alquileres,
    familiar (con niños y adolescentes),
    centros de salud, y
    transporte.

Los datos los obtuvimos de Buenos Aires Data, posteriormente construimos una variable numérica que cuantificó dichos criterios para cada comuna (15 comunas a las que pertenecen los 48 barrios). Luego cada comuna adquirió una ponderación entre 1 y 5, donde 1 es menos preferido y 5 es la mayor preferencia. Finalmente eligiendo 4 criterios, el primero que se elige siempre tendrá más valor sobre los otros, obtenemos la comuna y los posibles barrios ideales para vivir.

Si tenés planes de mudarte próximamente a CABA, este análisis te ayudará a descubrir cuál es tu barrio ideal para vivir.
