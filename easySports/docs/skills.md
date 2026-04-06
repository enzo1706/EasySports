# Skills del Agente (Habilidades Externas)

Las siguientes "skills" están habilitadas y documentadas para que el agente extienda su capacidad mediante herramientas de IA, estructuradas para escalar las soluciones de nuestro dominio deportivo.

## 1. find-skills (vercel-labs)
- **Para qué sirve:** Buscar nuevas herramientas, scripts o integraciones de manera dinámica en registros de skills.
- **Qué problema resuelve:** Evita tener que codificar soluciones básicas o utilitarias desde cero limitándonos al stack inicial; le da autonomía al agente para buscar la pieza que falta.
- **Relevancia:** Como nuestro MVP puede escalar rápidamente (por ej. integraciones de pagos externos), forzar al agente a buscar herramientas existentes nos ahorra deuda técnica y tiempo.

## 2. skill-creator (anthropic)
- **Para qué sirve:** Permite al agente codificar, refinar y generar "skills" personalizadas a demanda.
- **Qué problema resuelve:** Las lógicas muy atadas al negocio (ej. validaciones complejas de transferencias vs asistencia) suelen carecer de herramientas públicas. Con esto, encapsulamos lógicas ad-hoc en herramientas que el agente reusará sin inflar los prompts todo el tiempo.
- **Relevancia:** Fundamental para mantener la calidad y consistencia; la creación de herramientas específicas del dominio centraliza nuestro conocimiento.
