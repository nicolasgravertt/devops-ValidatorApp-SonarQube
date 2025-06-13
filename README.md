# Preguntas y Respuestas sobre SonarQube

---

### ¿Qué tipo de errores detectó SonarQube que podrían haber pasado desapercibidos?

SonarQube detectó vulnerabilidades y malas prácticas como:

- ⚠️ Credenciales hardcodeadas en el código, que representan un riesgo de seguridad.
- 💡 Uso de nombres de variables poco descriptivos o débiles.
- ⚠️ Comparaciones sin manejo adecuado de valores nulos que podrían causar errores en ejecución.

---

### ¿Qué ventajas tiene el análisis estático respecto al dinámico?

| Análisis Estático                         | Análisis Dinámico                         |
|------------------------------------------|------------------------------------------|
| No requiere ejecutar el programa         | Requiere ejecutar el código               |
| Detecta errores en etapas tempranas      | Detecta errores en tiempo de ejecución    |
| Es automatizable en pipelines de CI/CD   | Requiere pruebas o simulaciones           |
| Identifica vulnerabilidades y malas prácticas | Evalúa el comportamiento del software    |

---

### ¿Cómo impacta SonarQube en la calidad del software antes del despliegue?

- ✅ Detecta errores críticos y vulnerabilidades antes de que el software llegue a producción.
- 📈 Mejora la mantenibilidad y legibilidad del código.
- 🛡️ Establece políticas de calidad (Quality Gates) para evitar despliegues con problemas.
- 🔄 Fomenta una cultura de mejora continua y refactorización temprana.

---

### ¿Qué políticas o reglas personalizarías según el tipo de proyecto?

- 🔐 En aplicaciones sensibles: bloquear credenciales hardcodeadas y exigir cifrado.
- 🚀 En microservicios: reglas para gestión de errores, logs y tiempos de respuesta.
- ♻️ En proyectos legacy: ajustar severidad de code smells para facilitar migraciones.
- 🎓 En proyectos educativos: habilitar reglas que refuercen buenas prácticas y diseño.

---
