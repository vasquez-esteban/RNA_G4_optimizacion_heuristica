# Trabajo 1: Optimización Heurística

## Descripción del Proyecto

Este proyecto hace parte del curso *Redes Neuronales y Algoritmos Bioinspirados* de la Universidad Nacional de Colombia. Se abordan técnicas de optimización numérica y combinatoria mediante el uso de métodos heurísticos como algoritmos genéticos, optimización por enjambre de partículas, evolución diferencial y colonias de hormigas. Además, se comparan con métodos clásicos como el descenso por gradiente.

## Integrantes

- Marcos David Carrillo Builes  
- Tomás Escobar Rivera
- Jose Fernando López Ramírez  
- Esteban Vásquez Pérez  

## Links Relevantes

- 📝 [Entrada de Blog en RPubs](https://rpubs.com/evasp/rna-g4-optimizacion-heuristica)

## Estructura del Repositorio

```
.
├── src/                            # Directorio principal de código
│   ├── files/                      # Archivos de entrada y salida
│   │   ├── input/                  # Datos de entrada (Excel y CSV)
│   │   └── *.gif                   # GIFs generados por el algoritmo
│   ├── RNA_G4_Trabajo1.Rmd         # Código principal del proyecto
│   ├── apa_style.css               # Estilo CSS para la portada
│   ├── logo_unal.png               # Logo de la Universidad Nacional
│   ├── ruta_colonia_hormigas.gif   # GIF de visualización de la ruta
│   └── ruta_vecino_más_cercano.gif # GIF comparativo de algoritmo vecino más cercano
```

## Requisitos

Para ejecutar este proyecto necesitas:

- R (versión recomendada: 4.0 o superior)
- RStudio (versión recomendada: 1.4 o superior)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/[usuario]/[nombre-repositorio].git
   cd [nombre-repositorio]
   ```

2. Abre el archivo `RNA_G4_Trabajo1.Rmd` en RStudio

3. Instala las dependencias necesarias ejecutando los primeros bloques de código manualmente desde RStudio:
   ```R
   # Este código se encuentra en los primeros bloques del archivo Rmd
   install.packages(c("ggplot2", "dplyr", "readxl", "gifski", "gganimate"))
   # Más dependencias según sea necesario
   ```

## Contenido

- **RNA_G4_Trabajo1.Rmd**: Contiene todo el código principal para ejecutar el algoritmo de colonia de hormigas, incluyendo la carga de datos, procesamiento, visualización y análisis de resultados.

- **files/input/**: Contiene los archivos CSV y Excel necesarios como entrada para el algoritmo.

- **files/**: Almacena todos los GIFs generados por el algoritmo durante su ejecución, mostrando la evolución de las rutas.

- **ruta_colonia_hormigas.gif** y **ruta_vecino_más_cercano.gif**: Visualizaciones principales ubicadas en la raíz del directorio `src/` para acceso rápido (nota: esta ubicación no sigue la estructura estándar pero se mantiene por compatibilidad).

- **apa_style.css**: Archivo de estilo CSS utilizado para la generación de la portada y formato del documento final.

- **logo_unal.png**: Logo oficial de la Universidad Nacional utilizado en la documentación.

## Versiones

El repositorio muestra un desarrollo iterativo con diferentes versiones:

- v10.0 - Entrega Final
- v7.0 - Metodología de matriz de costos
- v6.0 - Conclusiones y Detalles
- v3.0 - Adición de Visualizaciones Gradiente y Mejora de Organización

## Ejecución

Para ejecutar el proyecto:

1. Abre `RNA_G4_Trabajo1.Rmd` en RStudio
2. Ejecuta los bloques de código secuencialmente usando el botón "Run" o presionando Ctrl+Enter (Cmd+Enter en Mac)
3. Para generar el documento completo, usa el botón "Knit" en RStudio

## Visualizaciones

El algoritmo genera diferentes visualizaciones en formato GIF que muestran:

- La evolución de la colonia de hormigas buscando la ruta óptima
- Comparación con el algoritmo del vecino más cercano
- Gradientes de optimización de rutas