# Apuntes_UF2_1

## Pruebas de software
### ¿Qué son?

- Cuando hablamos de pruebas de software nos referimos a ver si el software que hemos creado está bien escrito ya sea optimización, estructura, código redundante etc. Y a ver si su funcionamiento es correcto.

### Como se realizan estas pruebas 

- Normalmente para hacer estos test se usan frameworks. 
  
- Una framework es una herramienta, con código fuente para usarlo en tu software. 
  
- Cada framework de pruebas es para un lenguaje en específico. 

- Frameworks que se utilizan para hacer pruebas en java: 
  - JBehave
  - JUnit
  - Serenity
  
### Tipos de pruebas

- Funcionales: Pruebas para ver si el software hacer la función para la que ha estado diseñado.

- No funcionales: Pruebas para ver si el rendimiento es correcto, la seguridad, la estructura del código, si está bien optimizado el código etc.
- #### Tipos de pruebas funcionales
- Pruebas de unidad
- Pruebas de integración
- Pruebas de sistema
- #### Tipos de pruebas no funcionales
- Pruebas de usabilidad
- Pruebas de rendimiento
- Pruebas de estrés
  
### Froma de las pruebas

- Dinámicas: Pruebas que se llevan a cabo cuando el código se está ejecutando

- Estáticas: Pruebas que se llevan a cabo cuando el código no se está ejecutando para ver el código fuente línea por línea.

### Estrategias de prueba

- Caja Negra: Este tipo de estrategia solo mide la funcionalidad del programa es decir si hace la función que queremos que haga. Una técnica que se usa en esta estrategia son los valores límite.

- Caja Blanca: Este tipo de estrategia mide la funcionalidad y el código fuente del programa para ver si la estructura es correcta, si el código es redundante etc. Una técnica que se usa en esta estrategia es la prueba de bucles.

## Integración de software
### ¿Qué es?
Cuando hablamos de integración en el ámbito de software nos referimos a integrar o "poner" un software en un sistema. 

### Formas de integración de software

 - Integración Big Bang
 - Integración Descendente
 - Integración Ascendente
 - Integración Continua
  
### Ejemplos de servidores donde poder hacer una integración continua

- Jenkis
- Bamboo
- TravisCI
- CircleCI

## Cobertura del código
### ¿Qué es?
Cuando hablamos de cobertura del código nos referimos a cuanto código fuente ha sido probado. Más bien dicho a cuanto % del código fuente ha sido testeado.

Si la cobertura del código es 100% es que todo el código fuente ha sido ejecutado, siempre es recomendable que sea lo más próximo al 100%, ya que así podemos asegurar una mayor calidad del mismo.

## Calidad del software
Para sacar un buen software al mercado primero hay que realizarle unas pruebas es decir, un control de calidad del producto. 

### QA (Calidad del proceso)
Control de calidad para ver como se esta desarrollando el producto 

### QC (Calidad del producto)
Control de calidad para ver que defectos tiene un producto ya acabado. 

## Factores de Calidad
El modelo McCall dice que factores hay que seguir
 - Operación de producto 
   - Corrección
   - Fiabilidad
   - Eficiencia
   - Seguridad
   - Facilidad de Uso
 - Revisión del producto
   - Mantenibilidad
   - Flexibilidad
   - Facilidad de prueba
 - Transición del producto
   - Portabilidad
   - Reusabilidad
   - Interoperatividad