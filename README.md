# FrikoChef 🧑‍🍳📱

![Flujo Completo de Make](img/Flujo%20Completo.png)

**Documentación** de una herramienta de automatización conversacional para recomendación de recetas vía WhatsApp, construida para la marca Friko. La propuesta presenta a FrikoChef como un “sommelier de recetas” que entiende el contexto del usuario, recomienda preparaciones personalizadas y conecta ese interés con activos de marca como Momentos Friko. 

## 💡 Descripción

FrikoChef es una herramienta de automatización impulsada por inteligencia artificial que atiende a los usuarios directamente en WhatsApp, sin necesidad de instalar una app adicional. La experiencia se enfoca en captar variables del contexto culinario —como región, ocasión, número de personas, producto disponible y objetivo de preparación— para entregar una receta personalizada en segundos. 

La propuesta posiciona la solución como una mezcla entre asistente conversacional, motor de personalización y canal de activación de marca. Además de recomendar recetas, el sistema direcciona al usuario hacia contenido paso a paso en video dentro de “Momentos Friko”, fortaleciendo tráfico cualificado y engagement. 

## 🚀 Propuesta de valor

FrikoChef resuelve una necesidad concreta: ayudar al consumidor a decidir qué cocinar con productos Friko de forma rápida, simple y contextual. La experiencia es directa, sin complicaciones y diseñada para responder al momento real del usuario, ya sea una cena familiar, un almuerzo o un plan con amigos. 

Los principales beneficios que se destacan son:

- Recomendaciones hiperpersonalizadas según contexto, región, ocasión y producto disponible. 
- Atención dentro de WhatsApp, un canal de bajo esfuerzo y alta adopción para el usuario. 
- Conexión entre conversación, receta sugerida y contenido audiovisual de la marca. 
- Recolección de señales de consumo útiles para analítica y decisiones de marketing. 
- Capacidad de retención mediante mensajes semanales con nuevos productos y sugerencias generadas con IA. 

## ⚙️ Cómo funciona

El flujo se presenta en tres pasos simples. Primero, el usuario escribe o envía una nota de voz explicando su momento, cuántas personas van a comer y qué producto tiene disponible. Luego, la IA analiza esa solicitud utilizando el contexto del usuario y una base de recetas. Finalmente, entrega una receta personalizada con instrucciones y acceso a contenido complementario. 

![Primera Parte del Flujo](img/Primera%20Parte.png)

A nivel de experiencia, el proceso se resume así:

1. El usuario cuenta su momento en WhatsApp. 
2. La IA evalúa la solicitud y cruza la información con recetas y productos Friko. 
3. El sistema entrega una receta personalizada al instante. 

## 🎯 Variables de personalización

La solución toma decisiones a partir de seis dimensiones. Estas variables permiten que la automatización no responda con recetas genéricas, sino con una recomendación alineada al contexto específico del consumidor. 

| Variable | Qué aporta a la recomendación |
|---|---|
| Región | Ajusta sabores y disponibilidad por zona. |
| Ocasión | Adapta la receta al momento de consumo, como almuerzo, cena o reunión familiar. |
| Preparación | Considera nivel o método de preparación, por ejemplo parrilla, airfryer u horno. |
| Personas | Calcula cantidades adecuadas para el grupo. |
| Producto Friko | Usa el ingrediente disponible como base de la recomendación. |
| Objetivo | Prioriza rapidez, facilidad, economía o sabor. |

## 🏗️ Arquitectura de la solución

La solución está integrada por varios componentes tecnológicos que orquestan la experiencia. El motor central es GPT-5 con agentes, acompañado por WhatsApp como canal de entrada, Google Sheets como repositorio operativo de más de 150 recetas e historial por usuario, Make para automatizaciones y Telegram para alertas al equipo. 

![Tercera Parte del Flujo](img/Tercera%20parte.png)

| Componente | Rol dentro del sistema |
|---|---|
| **GPT-5 + Agentes** | Motor de IA generativa y personalización. |
| **WhatsApp** | Canal de entrada para texto y notas de voz. |
| **Google Sheets** | Base con 150+ recetas e historial conversacional por usuario. |
| **Make** | Orquestación y automatización de flujos en la nube. |
| **Telegram** | Notificación de eventos críticos al equipo de la marca. |

## 📊 Valor para marketing y marca

FrikoChef no se presenta solo como un chatbot de recetas, sino como una plataforma de marca con impacto en adquisición, retención y análisis del consumidor. La arquitectura destaca cuatro aportes centrales: hiper-personalización, tráfico cualificado hacia activos de contenido, retención proactiva y analítica de comportamiento. 

Desde un enfoque estratégico, esto convierte la automatización en una herramienta útil para marketing relacional. Cada interacción no solo resuelve una consulta del usuario, sino que también ayuda a identificar qué productos generan mayor tracción y en qué momentos del año aparecen ciertos patrones de consumo. 

## 🛡️ Protección de marca y control de uso

El sistema incluye una protección de marca basada en un esquema tipo semáforo. En uso normal, el usuario puede interactuar libremente sobre recetas y productos Friko, con un límite de cinco interacciones cada doce horas. Si el usuario consulta fuera del contexto culinario Friko por primera vez, recibe una advertencia; en una segunda ocasión, se activa un bloqueo automático y una alerta por Telegram al administrador. 

![Sistema de Seguridad y Alertas](img/Segunda%20parte%20(Seguridad).png)

Este enfoque añade gobernanza al proyecto y reduce el riesgo de desvío del canal. Estratégicamente, también ayuda a mantener la experiencia enfocada en el territorio de marca definido por FrikoChef. 

## 🍽️ Casos de uso

Un caso simple y potente: una familia en Envigado con pechuga Friko disponible y necesidad de una cena fácil. A partir de esa información, FrikoChef genera una receta personalizada con ingredientes, pasos y tiempos adaptados al contexto descrito. 

Este tipo de uso vuelve la herramienta valiosa para:

- Campañas de activación de producto. 
- Programas de fidelización y remarketing conversacional. 
- Redirección de audiencias a contenido de marca. 
- Captura de insights de consumo en tiempo real. 

## 🔗 Enlaces del Proyecto y Descargas

- 🌐 **Sitio de referencia:** [Explora la interfaz de FrikoChef](https://v0-frikochef.vercel.app/)
- ⚙️ **Visualizador de Flujo (Make):** [Ver y analizar la arquitectura del escenario](https://us2.make.com/public/shared-scenario/mTxGPAK6eSY/cambios-sin-danar-el-original-copy)

---
**Desarrollado por Lucas Trujillo**  
*Estudiante de Mercadeo | Entusiasta del Skill Stacking (Marketing, Diseño y Programación)*
