# Exploración de algoritmos de Deep Clustering sobre CIFAR-10: DEC e IDEC

Implementación de una arquitectura para el entrenamiento y la evaluación de los algoritmos fundacionales de *Deep Clustering*;
**DEC** (*Deep Embedded Clustering*) e **IDEC** (*Improved Deep Embedded Clustering*), sobre el conjunto de datos CIFAR-10, 
a través de métricas externas e internas que permiten evaluar la calidad de un agrupamiento en términos de la compactación de 
los grupos, separabilidad y representación

## Contenido del repositorio

```
|- INFORME_PROYECTO.pdf    # Informe ejecutivo del proyecto
|- DeepC_Clustpy.ipynb     # Notebook principal (DEC + IDEC)
```

## Librería base

[ClustPy](https://github.com/collinleiber/ClustPy/tree/main) v0.0.2, que implementa
diversas arquitecturas de *Deep Clustering*. Los módulos auxiliares para la métrica CVNN
se descargan automáticamente desde GitHub al ejecutar la primera celda del notebook.

- 📄 [Documentación](https://clustpy.readthedocs.io/en/latest/search.html?q=_AbstractAutoencoder&check_keywords=yes&area=default)
- 💻 [Repositorio](https://github.com/collinleiber/ClustPy/tree/main)

## Uso

El notebook es autocontenido y ejecutable de principio a fin en **Google Colab con GPU T4**.
A partir del mismo, CIFAR-10 se descarga automáticamente (~170 MB) en la primera ejecución.

1. Abrir `DeepC_Clustpy.ipynb` en Google Colab
2. Activar acelerador GPU: *Entorno de ejecución → Cambiar tipo de entorno de ejecución → T4 GPU*
3. Ejecutar todas las celdas en orden

## Video de exposición del proyecto

🎥 [Ver en YouTube: Exploración de algoritmos fundacionales de Deep Clustering: DEC y IDEC](https://youtu.be/vUKOOXhbWG4)

## Autor

**Sebastián Castaño Quinchía** · sebastian.castanoq@udea.edu.co  
Universidad de Antioquia · Junio 2026
