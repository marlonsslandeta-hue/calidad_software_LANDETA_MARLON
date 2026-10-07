# Calidad de Software

Este repositorio tiene como finalidad introducir los conceptos fundamentales de la calidad del software, con especial atención en la validación del sistema mediante pruebas automatizadas. La calidad del software no se limita a la funcionalidad del programa, sino que también considera la confiabilidad, mantenibilidad, seguridad y experiencia del usuario.

## 1. ¿Qué es la calidad de software?

La calidad de software se define como el grado en que un sistema cumple con los requisitos funcionales y no funcionales esperados, así como la satisfacción de las necesidades de los usuarios y la estabilidad del producto a lo largo de su ciclo de vida.

Entre los principales atributos de calidad se encuentran:

- Funcionalidad: el software debe realizar correctamente las tareas para las que fue diseñado.
- Confiabilidad: el sistema debe comportarse de manera estable y predecible.
- Mantenibilidad: el código debe ser comprensible y fácil de modificar.
- Usabilidad: la aplicación debe ser intuitiva y accesible para el usuario.
- Seguridad: la información y los procesos deben protegerse frente a riesgos.
- Rendimiento: el sistema debe responder de manera eficiente bajo condiciones normales de uso.

## 2. Principios básicos de la calidad de software

La calidad del software se fortalece mediante prácticas sistemáticas y disciplinadas, entre las que destacan:

- Definir claramente los requisitos antes de implementar.
- Validar cada cambio mediante pruebas.
- Escribir código limpio, legible y documentado.
- Reducir errores mediante revisión y automatización.
- Asegurar la trazabilidad entre requisitos, diseño y pruebas.
- Mejorar continuamente el proceso de desarrollo.

## 3. Importancia de las pruebas en el desarrollo de software

Las pruebas forman parte esencial del proceso de ingeniería de software porque permiten verificar que el sistema cumple con las especificaciones y detectar defectos antes de la entrega final. Sin una estrategia adecuada de pruebas, es más probable que un software presente fallos funcionales, errores de integración o problemas de usabilidad.

Existen diferentes niveles y tipos de pruebas, dependiendo del objetivo que se desea evaluar.

### 3.1 Pruebas unitarias

Las pruebas unitarias son pruebas automatizadas que validan unidades individuales del software, como funciones, métodos o clases, de manera aislada. Su objetivo principal es comprobar que cada componente cumple con su comportamiento esperado bajo distintos escenarios.

Características principales:

- Se enfocan en pequeñas partes del sistema.
- Son rápidas de ejecutar.
- Permiten detectar errores en la lógica de negocio.
- Facilitan la depuración y la corrección de fallos.

Ejemplo: si una función realiza una suma o valida un ingreso, la prueba unitarias verifica que devuelva el resultado correcto para entradas válidas e inválidas.

### 3.2 Pruebas E2E (End-to-End)

Las pruebas E2E evalúan el sistema completo, desde la interacción del usuario hasta la integración de múltiples componentes. Estas pruebas simulan escenarios reales de uso para verificar que el flujo completo funciona correctamente.

Características principales:

- Validan la experiencia completa del usuario.
- Requieren mayor tiempo de ejecución que las pruebas unitarias.
- Detectan fallos de integración y errores de flujo.
- Permiten comprobar que el sistema funciona en condiciones cercanas a la realidad.

Ejemplo: un usuario inicia sesión, realiza una operación y observa el resultado final esperado en la aplicación.

## 4. Diferencia entre pruebas unitarias y pruebas E2E

La diferencia principal radica en el alcance de la validación:

- Pruebas unitarias: validan componentes aislados.
- Pruebas E2E: validan el sistema como un todo.

Ambas son complementarias. Las pruebas unitarias permiten detectar errores de forma temprana y eficiente, mientras que las E2E aseguran que los flujos reales del usuario funcionan correctamente en un entorno integrado.

## 5. Recomendaciones para asegurar la calidad

- Diseñar pruebas que cubran casos normales y casos límite.
- Automatizar la ejecución de pruebas en cada cambio relevante.
- Mantener la documentación clara y actualizada.
- Combinar diferentes niveles de prueba para obtener mayor cobertura.
- Revisar continuamente los defectos detectados y mejorar el proceso de desarrollo.

## 6. Conclusión

La calidad de software es un objetivo fundamental en cualquier proyecto tecnológico, ya que influye directamente en la confiabilidad, la productividad y la satisfacción del usuario. Las pruebas unitarias y las pruebas E2E son herramientas esenciales para verificar que el software no solo funciona, sino que también cumple con los requisitos de calidad esperados en un entorno real.

En conjunto, estas prácticas permiten construir sistemas más robustos, confiables y sostenibles en el tiempo.
