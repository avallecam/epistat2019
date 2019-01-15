# plan

## pendiente
- consultar info básica
- presentar silabo
- Buscar bases de datos, default RStudio
- explorar Rstudio Cloud

## info preliminar

- población: estudiantes de medicina socimed peru
- localizacion: upch-miraflores, auditorio?
- tiempo: 4h
- Internet: conexión a CSUR-LIBRE, buena calidad y saturación?
- Rstudio Cloud: 
  - depende de la calidad de conexión a internet
  - evita problemas por heterogeneidad de hardward
- proceso de selección:
  - requisitos de postulación?
  - definir con cuántos días de anticipación nos comunicaremos con estudiantes.

## objetivo general

- generar medidas de asociación con scripts básicos en R
- entender problema e interpretar resultados

## silabo

### obligatorio

0. Presentar el problema y enfoque (20 min)
  	- Presentar problema cancer y fumar.
	- Enfoque causal, confusion con el ejemplo de cafe y cancer de pulmon.
  	- cuadro comparativo: disenos y medidas de asociacion!

1. Introducción: (10 min)
	- objetivo: Crear y organizar proyectos en R
  	- herramienta: Rstudio IDE

2. Analisis descriptivo: (30 min)
  	- objetivo: generar automáticamente tabla 1 y 2
  	- paquete: tableone, compareGroups

3. qué es un regresion, cómo funciona, como la interpreto (30 min)
	- lm
	- logistica: odds
	
3. Estudios transversales (50 min)
	- outcome: Categorico Dicotómico
		- medida: PR
		- función: glm log-binomial, log-poisson
	- Ejecutar el modelo
	- Saber interpretar el modelo

4. Estudios caso y control (50 min)
	- outcome: Categorico Dicotómico
		- medida: OR
		- función: glm logit-binomial

5. Tiempos a evento (50 min)
	- outcome: Categórico Dicotómico
		- medida: kaplan-meier
		- paquete: survival, survminer

### extra

6. Estudios prospectivos
	- outcome: Categórico Dicotómico
		- medida RR
		- funcion: glm log-binomial, log-poisson

## Tareas

Competencia a medir: 

- Identificar tipo de estudio y calcular medida de asociación de interés.
- Problema -> Estudio -> R

## links

- https://stats.idre.ucla.edu/other/mult-pkg/whatstat/

## hecho

- Crear GitHub
