La predicción climática a diferencia de de la predicción del tiempo puede ser de semanas a décadas incluso. Esto se debe a la naturaleza caótica de la atmósfera que es en lo que se basa la predicción del tiempo mientras que la predicción climática requiere de la variación de los océanos, suelo o hielo que varía con mucha lentitud.

## Metodología de profiling

1. Determinar el area de estudio
	 - Se estudia un único time step
	 - Se divide en diferentes áreas de cómputo
2. Eficiencia de despliegue
	- Opciones de coma flotante
	- Optimización de compilador
	- Otimización de librerías externas
3. Benchmarking
	- Realizar test básicos de métricas de hardware
	- weak y strong scaling
	- Comparar optimizaciones (float vs double)
4. Análisis del profiling
	- Analizar todo lo obtenido con Extrae
		- Analizar diferentes optimizaciones
		- Problemas de desbalanceo
		- Latencia de red y ancho de banda
5. Validación
	- Tests de replicabilidad
		Aunque no se dé el mismo resultado siempre serán similares
	- 