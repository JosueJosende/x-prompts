## IMPLEMENTACIÓN

Necesito implementar [funcionalidad específica] en [lenguaje de programación].

Requisitos clave:
1. [Requisito 1]
2. [Requisito 2]
3. [Requisito 3]

Por favor, considera:
- Manejo de errores
- Casos extremos
- Optimización del rendimiento
- Mejores prácticas para [lenguaje/framework]

Por favor, no quites comentarios ni código innecesariamente.
Genera el código con comentarios claros que expliquen la lógica.



## OBTENER INFORMACIÓN

¿Puedes explicar la siguiente parte del código en detalle?:

[pega la sección de código]

Específicamente:

1. ¿Cuál es el propósito de esta sección?
2. ¿Cómo funciona paso a paso?
3. ¿Hay algún problema o limitación potencial con este enfoque?



## REVISIONES Y MEJORAS DE CODIGO

Por favor, revisa el siguiente código:

[pega tu código]

Considera:
1. Calidad del código y cumplimiento de las mejores prácticas
2. Posibles errores o casos extremos
3. Optimización del rendimiento
4. Legibilidad y mantenibilidad
5. Cualquier problema de seguridad

Sugiere mejoras y explica tu razonamiento para cada sugerencia.



## TAREAS DE CODIFICACIÓN

Para implementar un algoritmo específico:

Implementa un [nombre del algoritmo] en [lenguaje de programación]. Por favor, incluye:
1. La función principal con parámetros y tipos de retorno claros
2. Funciones auxiliares si es necesario
3. Análisis de complejidad temporal y espacial
4. Ejemplo de uso
Para crear una clase o módulo:

Crea una [clase/módulo] para [funcionalidad específica] en [lenguaje de programación].
Incluye:
1. Constructor/inicialización
2. Métodos principales con docstrings claros
3. Cualquier método auxiliar privado necesario
4. Encapsulación adecuada y adherencia a los principios de la POO
Para optimizar el código existente:

Aquí tienes un fragmento de código que necesita optimización:
[pega el código]
Por favor, sugiere optimizaciones para mejorar su rendimiento. Para cada sugerencia, explica la mejora esperada y cualquier compensación.
Para escribir pruebas unitarias:

Genera pruebas unitarias para la siguiente función:
[pega la función]
Incluye pruebas para:
1. Entradas normales esperadas
2. Casos extremos
3. Entradas inválidas
Usa la sintaxis de [framework de pruebas preferido].



## CREACIÓN DE APLICACIÓN CLIENTE-SERVIDOR

Quiero crear una aplicación que haga [DESCRIPCIÓN] con cliente y servidor

El cliente:
- Usar Vite como framework
- Ubicación: carpeta src (en la raíz)
-Crear src/config.js con:
export const SERVER_CONFIG = {
  IP: '[IP]',
  PORT: [PUERTO],
  get BASE_URL() {
    return `http://${this.IP}:${this.PORT}`;
  }
};


El servidor:
- Express.js como framework
- Ubicación: carpeta server (en la raíz)
- Base de datos SQLite con la librería 'sqlite3'
- API RESTful para el cliente


Scripts:
Agregar "agregame npm run dev:full" para el desarrollo