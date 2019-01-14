# plan

## pendiente
- consultar info básica
- presentar silabo
- Buscar bases de datos, default RStudio
- explorar Rstudio Cloud

## info preliminar

- población: estudiantes de medicina socimed peru
- localizacion: upch-miraflores, auditorio?
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

0. Introducción: 
  - objetivo: Crear y organizar proyectos en R
  - herramienta: Rstudio IDE

1. Analisis descriptivo:
  - objetivo: generar automáticamente tabla 1 y 2
  - paquete: tableone, compareGroups

2. Tipos de modelamiento (10 - 15 mins)
  - objetivo: presentar enfoques epidemiológico causal y bioestadístico (exploratorio o predictivo)
  - material: cuadro comparativo con ejemplos
 
3. Estudios transversales
	- outcome: Numérico Continuo
    - medida: coeficiente
    - función: lm
  - outcome: Categorico Dicotómico
    - medida: PR
    - función: glm log-binomial, log-poisson

4. Estudios caso y control
	- outcome: Categorico Dicotómico
    - medida: OR
    - función: glm logit-binomial

### extra

x. Tiempos a evento
  - outcome: Categórico Dicotómico
    - medida: HR
    - paquete: survival, survminer

y. Estudios prospectivos
	- outcome: Categórico Dicotómico
    - medida RR
    - funcion: glm log-binomial, log-poisson

## Tareas

Competencia a medir: 
- Identificar tipo de estudio y calcular medida de asociación de interés.
- Estudios -> Problema -> R

## links

- https://stats.idre.ucla.edu/other/mult-pkg/whatstat/

## hecho

- Crear GitHub
