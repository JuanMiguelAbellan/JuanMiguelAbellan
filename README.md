# Hola, soy Juan Miguel Abellán

**Desarrollador full-stack especializado en IA aplicada.** Construyo productos completos (backend, frontend e infraestructura) con la IA integrada de verdad en el producto, no como un añadido.

Graduado en Desarrollo de Aplicaciones Web (CPIFP Pirámide, Huesca). Me interesa llevar la IA más allá del chatbot genérico: modelos autoalojados, RAG con embeddings, evaluación medible y detección de anomalías con deep learning. Busco trabajo en remoto, en equipos donde la IA aplicada sea parte real del producto.

[Portfolio](PORTFOLIO_URL) · [LinkedIn](https://www.linkedin.com/in/juan-miguel-abell%C3%A1n-piedrafita-b26a74425/) · [Email](mailto:wextren@gmail.com)

---

## Proyectos destacados

### [IADocuments](https://github.com/JuanMiguelAbellan/Proyecto-2-DAW) · [demo](https://iadocuments-jmabellan.vercel.app)
Asistente de IA autoalojado para preguntar, anotar y editar tus propios PDFs. RAG con pgvector, LLM propio en Ollama, respuestas en streaming por WebSocket y pagos con Stripe.
`React` `Node.js` `TypeScript` `PostgreSQL` `pgvector` `Ollama` `Docker`

### [rag-eval](https://github.com/JuanMiguelAbellan/rag-eval)
Mide con estadística real cuánto acierta un RAG, en local y sin claves de API. Aplicado a IADocuments: el punto débil era el modelo de embeddings, y la mejor configuración subió el MRR de 0.685 a 0.947 (bootstrap pareado, IC 95 %).
`TypeScript` `Ollama` `BM25` `Embeddings`

### [Reservas](https://github.com/JuanMiguelAbellan/reservas) · [demo](https://web-production-acd80.up.railway.app)
Reservas multi-negocio donde el doble booking es imposible: lo garantiza una restricción de exclusión de PostgreSQL, no el código. Horarios correctos en cambios de hora, multi-tenencia estricta, 43 tests de integración + 13 E2E.
`Next.js` `TypeScript` `PostgreSQL` `Playwright` `GitHub Actions`

### [Tablero](https://github.com/JuanMiguelAbellan/tablero) · [demo](https://web-production-1e9f.up.railway.app)
Kanban colaborativo en tiempo real que sigue funcionando si se cae la red. Server-Sent Events sobre un registro de eventos reanudable, UI optimista con reconciliación e índices fraccionarios.
`React` `Fastify` `PostgreSQL` `SSE` `Playwright`

### [docs-search-mcp](https://github.com/JuanMiguelAbellan/docs-search-mcp)
Servidor MCP de solo lectura para que una IA busque en tus documentos (BM25 + embeddings), diseñado tratando al propio LLM como no fiable.
`TypeScript` `MCP` `zod` `Ollama`

### [ReciclaB2B](https://github.com/JuanMiguelAbellan/reciclab2b) · [demo](https://web-production-4d6ac.up.railway.app)
Mercado B2B de material reciclable con mensajería en tiempo real e inventario seguro ante concurrencia. Dos auditorías de seguridad propias y 151 tests.
`Laravel` `Inertia.js` `React` `Filament` `Reverb`

### Más
- [react-agent-loop](https://github.com/JuanMiguelAbellan/react-agent-loop) · paquete [npm](https://www.npmjs.com/package/react-agent-loop) sin dependencias: bucle de agente ReAct para cualquier cliente de chat.
- [agent-cli](https://github.com/JuanMiguelAbellan/agent-cli) · agente de terminal con herramientas reales sobre un LLM autoalojado.
- [Detección de anomalías con autoencoders](https://anomaly-detection-demo-jmabellan.vercel.app) · AE/VAE para tráfico de red, hecho en prácticas; demo con inferencia en el navegador (TensorFlow.js).

---

## Hackathons

- **ANRGIT** · Hackathon 2026 · [repo](https://github.com/JuanMiguelAbellan/ANRGIT): dashboard que cruza vehículos por etiqueta ambiental con la calidad del aire de Zaragoza.
- **AWS DeepRacer** · 5º puesto en la liga online de España (2024).
- **AWS JamRock** Huesca 2025 · **AWS Jam** Zaragoza 2025 · **AWS Jam** Pirámide, Huesca 2024.

---

## Tecnologías

| | |
|---|---|
| **Frontend** | React, Next.js, TypeScript, JavaScript, HTML/CSS |
| **Backend** | Node.js, Express, Fastify, Java, Spring Boot, FastAPI, PHP, Laravel |
| **Bases de datos** | PostgreSQL, pgvector, MongoDB |
| **IA / ML** | Ollama (LLMs autoalojados), RAG y embeddings, evaluación de RAG, MCP, TensorFlow, Keras, scikit-learn |
| **Infraestructura** | Docker, AWS, Railway, Vercel, GitHub Actions |
| **Otros** | WebSockets, Server-Sent Events, Playwright, JWT, Stripe, OpenAPI |
