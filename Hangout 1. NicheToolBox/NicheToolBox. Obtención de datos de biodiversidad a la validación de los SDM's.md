---
"Create by:": Vizuet cf
Descripción: En ésta platica se dará un panorama genral de como usar las funciones incluídas en la aplicación web NicheToolBox. Esta plataforma stá basada en el framework "Shiny" de R, para la obtención, exploración y analisis de los datos de biodiversidad.
Links: http://shiny.conabio.gob.mx:3838/nichetoolb2/
Ponente: Luis Osorio Olvera
Date: 1616-01-11
---
# Que es NicheToolBox

Es una herramienta para la obtención, limpieza, visualización, análisis y modelación del nicho ecológico, utilizando información espacial de las capas climáticas de WoldClim. Es una plataforma desarrollada usando el FrameWork  Shiny de R,por los que es posible desarrollar e incorporar las funciones de los paquetes de R.

Las funciones mas principales de NTB son las siguientes: 

- Obtención de datos de presencia.
- Limpieza de los datos georreferenciados.
- Visualización de nicho n-dimensional (bios WC)
- Análisis de Cluster en E.
- Análisis bivariado de correlaciones.
- PCA
- ENM (modelos de elipsoides; distancias de Mahalanobis).
- Algunas métricas de evaluación de SDM´s.
	- Evaluación no dependiente de umbral.
		- ROC parcial.
	- Evaluación dependiente del umbral
		- Matriz de confusión, TSS, Kappa...

### Algunos ajustes necesarios

NicheToolBox tiene una pagina de Settings & Materials donde se especificará lo siguiente:

- Resolución de las capas climáticas .
	- 10 minutos de arco
	- 5 minutos de arco
	- 2.5 minutos de arco
- El conjunto de datos sobre los que se harán los análisis.
	- Los datos de GBIF
	- Datos de presencias subidos por el usuario

---
## Obtención de datos georreferenciados.

Los datos son solicitados a la API (Aplication Programing Interface) de GBIF usando funciones del paquete "spoc" de R.

## Cómo usar NicheToolBox

#### Settings & Materials

En la pestaña "**Settings & Materials**" (Imagen 1) elegimos las siguientes opciones:

![[Captura de pantalla de 2023-09-26 21-43-55.png]]
	Imagen 1. Settings & Materials de NicheToolBox

1. **Resolución de las capas climáticas**

- Elegimos una de las tres opciones disponibles.

![[Captura de pantalla de 2023-09-26 22-03-46.png]]
	Imagen 2. Resolución de las capas climáticas


1. **Conjunto de datos sobre los que se harán los análisis**

- Mas abajo en la misma página elegimos una de las tres opciones disponibles.

![[Captura de pantalla de 2023-09-26 22-10-41.png]]
	Imagen 3. Conjunto de datos.




---
# Bibliografía

> 	**Video**
> 1. [Hangout 1: NicheToolBox: de la obtención de datos de biodiversidad a la validación de los SDMs.](https://www.youtube.com/watch?v=cco3KFwZaL4&list=PLu_3tLNPCPDZd0VvvXVCt9XHcNx7L9E_e&index=1&t=280s)
> 	**NicheToolbox**
> 2. [NicheToolBox](http://shiny.conabio.gob.mx:3838/nichetoolb2/)
> 3. 