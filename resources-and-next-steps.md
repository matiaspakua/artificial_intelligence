# Guía de Recursos y Pasos Iniciales
## Plan de Estudios de IA - Implementación Práctica

---

## 1. ESTRUCTURA GENERAL DEL PLAN

Has recibido tres documentos que forman tu plan de estudios:

1. **AI-learning-plan.md** - El índice completo de 24 semanas (6 meses)
2. **AI-detailed-analysis.md** - Explicaciones funcionales profundas de conceptos clave
3. **Este documento** - Recursos concretos y cómo comenzar

**Tiempo requerido:** 10-18 horas/semana (variable según fase)
**Duración:** 6 meses de estudio intensivo
**Requisitos previos:** Tu experiencia en software engineering es suficiente

---

## 2. DIAGNÓSTICO: DÓNDE ESTÁS AHORA

Antes de comenzar, auto-evalúate:

**¿Entiendes estos conceptos?** (Sí/No)
- [ ] Cómo un modelo aprende de datos (conceptualmente)
- [ ] Qué es un "token" en el contexto de LLMs
- [ ] La diferencia entre pre-training y fine-tuning
- [ ] Cómo funcionan vectors y embeddings
- [ ] Qué hace único a un transformer

**Si respondiste NO a más de 2:** Necesitas empezar en Fase 1
**Si respondiste SÍ a todo:** Puedes saltarte Fase 1 y comenzar en Fase 2

**¿Tienes experiencia con?** (Sí/No)
- [ ] Usar ChatGPT/Claude/Gemini regularmente
- [ ] Entender prompt engineering
- [ ] Trabajar con APIs de LLMs
- [ ] Implementar RAG sistemas

**Si respondiste NO a todo:** Necesitas Fase 2-3 en profundidad
**Si respondiste SÍ a 2+:** Puedes enfocarte en Fase 4-5

---

## 3. RECURSOS POR FASE

### **FASE 1: FUNDAMENTOS (Semanas 1-4)**

#### Lectura Recomendada:
- **"The Neuron AI" Blog Post**: "Three Years of ChatGPT" (retrospective 2022-2025)
  - Ubicación: theneuron.ai
  - Tiempo: 45 min
  - Por qué: Contexto histórico reciente, escrito por ChatGPT (meta)

- **3Blue1Brown - Essence of Linear Algebra** (YouTube series)
  - Capítulos: 1-5 (80 min total)
  - Por qué: Visualización intuitiva de conceptos que necesitarás

- **Andrew Ng - Machine Learning Crash Course**
  - Ubicación: coursera.org (gratis)
  - Módulos: 1-3 sobre ML basics
  - Tiempo: 6 horas

#### Cursos Online (Recomendados):
1. **Coursera - "Foundational Mathematics for AI"** (Johns Hopkins University)
   - Duración: 4 semanas
   - Costo: Gratis (auditar)
   - Contenido: Linear Algebra, Calculus, Probability
   - Nivel: Perfecto para "nivel funcional"

#### Hands-on Activities:
- **Semana 1-2:** Explorar 5 LLMs diferentes
  - ChatGPT, Claude, Gemini, Copilot, Perplexity
  - Nota diferencias en respuestas
  - Documenta limitaciones
  
- **Semana 3:** Fine-tuning pequeño
  - Dataset: Tu propio dominio (aerospace docs)
  - Plataforma: Hugging Face (gratis)
  - Meta: Crear especialización inicial

- **Semana 4:** Proyecto - "AI Landscape Report"
  - Resumen: Qué es IA, de dónde viene, a dónde va
  - Público: Colegas sin background IA
  - Extensión: 2000-3000 palabras

---

### **FASE 2: ARQUITECTURA (Semanas 5-8)**

#### Recursos Principales:
1. **DeepLearning.AI - "How Transformer LLMs Work"**
   - Costo: $49-99 (o gratis en YouTube versión educativa)
   - Duración: 8 horas
   - Crítico: Mejor introducción a transformers

2. **Google ML Crash Course - Transformers Unit**
   - Ubicación: developers.google.com/machine-learning
   - Tiempo: 4 horas
   - Contenido: Self-attention explicado visualmente

3. **Paper Académico (Simplificado):**
   - "Attention Is All You Need" (Vaswani et al., 2017)
   - Con anotaciones: "The Illustrated Transformer" (Jay Alammar)
   - Tiempo: 2 horas de lectura + notas

4. **Herramientas Interactivas:**
   - Transformer Explainer: poloclub.github.io/transformer-explainer/
   - Permite jugar con transformers en tiempo real
   - Excelente para intuición

#### Hands-on:
- **Semana 5:** Implementar transformer mini en Python
  - Repositorio: "The Annotated Transformer" (PyTorch)
  - Meta: Entender cada línea
  
- **Semana 6:** Fine-tuning DistilBERT con datos de aerospace
  - Dataset: Publicaciones técnicas NASA/ESA
  - Framework: Hugging Face transformers
  - Métrica: Mejora en clasificación de documentos

- **Semana 7:** Explorar RAG básico
  - Stack: LangChain + OpenAI API + vector DB
  - Experimento: Q&A sobre documentos propios
  
- **Semana 8:** Proyecto - "Embeddings Analysis"
  - Visualizar space de embeddings
  - Mostrar similitudes semánticas en dominio
  - Presentación: Notebook interactivo

---

### **FASE 3: APLICACIONES (Semanas 9-14)**

#### Recursos Principales:
1. **LangChain Official Documentation**
   - https://python.langchain.com/
   - Tutorial: RAG from scratch (2 horas)
   - Ejemplos: 50+ casos de uso

2. **Prompt Engineering Guide**
   - https://www.promptingguide.ai/
   - Técnicas: Chain-of-Thought, Few-Shot, etc.
   - Ejercicios: 20+ ejemplos prácticos

3. **DeepLearning.AI - Specialization Courses**
   - "ChatGPT Prompt Engineering" (1 hora)
   - "Building Systems with LLMs" (4 horas)
   - "LLM Application Development" (8 horas)

4. **Casos de Estudio de Industria:**
   - "32 LLM Use Cases in 2025" (ORQ.ai blog)
   - Specific to aerospace: ESA/NASA AI initiatives
   - Startup case studies: Anthropic, OpenAI blogs

#### Hands-on Projects:
- **Semana 9-10:** RAG System Avanzado
  - Conexión a real database (ej., satellite telemetry)
  - Retrieval + LLM + formatting
  - Evaluación: Metric de relevancia

- **Semana 11:** Prompting Engineering Mastery
  - 30 variaciones de mismo prompt
  - Análisis cuantitativo de resultados
  - Documentación: "Prompting Playbook" personal

- **Semana 12:** Multi-tool Integration
  - APIs de 3 servicios diferentes
  - Orquestación con LangChain
  - Caso: Análisis automático de datos

- **Semana 13-14:** Proyecto Final Fase 3
  - **"Satellite Anomaly Detection System"**
  - Componentes: RAG + LLM + retrieval
  - Entrada: Telemetría real o simulada
  - Salida: Reporte de anomalía en lenguaje natural

---

### **FASE 4: AGENTES (Semanas 15-20)**

#### Recursos Principales:
1. **Model Context Protocol (MCP)**
   - Especificación oficial: https://modelcontextprotocol.io/
   - Lectura: 2 horas
   - Ejemplos: 5+ implementaciones

2. **LangGraph (LangChain Foundation)**
   - Documentación: https://langchain-ai.github.io/langgraph/
   - Tutoriales: Agents, Tools, State Management
   - Tiempo: 8 horas

3. **CrewAI Framework**
   - GitHub: joaomdmoura/crewai
   - Documentación: crews, tasks, tools
   - Tiempo: 4 horas

4. **Papers y Análisis:**
   - "Agentic Systems: Guide to Vertical AI Agents"
   - "AI Agents vs Agentic AI: Conceptual Taxonomy"
   - Bain & Company: "Building Foundation for Agentic AI"

#### Hands-on Projects:
- **Semana 15-16:** MCP Server Implementation
  - Crear MCP server simple
  - Exponer 3 tools/resources
  - Conectar con LLM client
  - Ejemplo: Server para datos aeroespaciales

- **Semana 17:** Multi-Agent System (2-3 agentes)
  - Agent 1: Data Analysis
  - Agent 2: Simulation
  - Agent 3: Reporting
  - Orquestación: Orchestrator agent
  - Framework: CrewAI o LangGraph

- **Semana 18-19:** Agentic Workflow Completo
  - Objetivo: Resolver problema complejo en dominio
  - Loop: Observation → Thought → Action (ReAct)
  - Persistencia: Memory módules
  - Monitoreo: Logging y auditoría

- **Semana 20:** Proyecto Final Fase 4
  - **"Autonomous Satellite Operations Agent"**
  - Capabilidades:
    - Monitorear datos en tiempo real (MCP)
    - Detectar anomalías (razonamiento)
    - Acceder a histórico (RAG)
    - Simular trayectorias (external tool)
    - Tomar decisiones autónomas (agent)
    - Reportar a humanos (governance)

---

### **FASE 5: TENDENCIAS Y ESPECIALIZACIÓN (Semanas 21-24)**

#### Recursos Principales:
1. **Reportes de Industria:**
   - Gartner: "Top 10 Strategic Technology Trends 2025"
   - McKinsey: "The state of AI in 2025"
   - LinkedIn: "Top Tech Skills for 2025-2026"

2. **Research Papers (ArXiv):**
   - Buscar: "agentic AI 2025"
   - Filter: últimos 3 meses
   - Leer: 10+ papers relacionados a tu dominio

3. **Blogs y Newsletters:**
   - The Neuron (theneuron.ai)
   - Unfinished Labs
   - Papers with Code
   - Hugging Face blog

4. **Comunidades:**
   - Hugging Face community forums
   - Reddit: r/MachineLearning, r/LocalLLaMA
   - Discord communities: LangChain, CrewAI

#### Hands-on (Research & Planning):
- **Semana 21:** Landscape Analysis
  - Tendencias en aerospace + AI
  - Competidores y soluciones existentes
  - Gap analysis: oportunidades

- **Semana 22:** Specialization Path Definition
  - Cuál es tu nicho único
  - Cómo combinar skills
  - Qué certificaciones perseguir

- **Semana 23:** Portfolio Development
  - Documenta todos los proyectos
  - Escribe case studies
  - Prepara GitHub/blog de trabajos

- **Semana 24:** Capstone & Future Planning
  - **Final Capstone Project:**
    - Propuesta: Sistema IA para problema real en aerospace
    - Documentación: Arquitectura, design decisions, resultados
    - Presentación: Profesional, para portafolio
  - **Plan 12 Meses:**
    - Skills a desarrollar después de este curso
    - Certificaciones objetivo
    - Rol/posición target para 2026

---

## 4. CRONOGRAMA SEMANA POR SEMANA (EJEMPLO SEMANA 1)

### **SEMANA 1: Introducción a IA Moderna**

**Lunes:** (2 horas)
- [ ] Ver: "The Neuron - Three Years of ChatGPT" (45 min)
- [ ] Lectura: Primeras 20 páginas de "AI: A Guide for Thinking Humans"
- [ ] Reflexión: Notas personales sobre impacto de ChatGPT en tu trabajo

**Martes:** (2.5 horas)
- [ ] Video: 3Blue1Brown Essence of Algebra videos 1-2
- [ ] Ejercicio: Entender qué son vectores, matrices
- [ ] Aplicación: Cómo se relaciona con embeddings en LLMs

**Miércoles:** (2 horas)
- [ ] Crear cuenta/acceso: ChatGPT, Claude, Gemini
- [ ] Experimento: Mismo prompt en 3 modelos
- [ ] Documentación: Tabla comparativa de respuestas

**Jueves:** (2 horas)
- [ ] Cursos: Coursera ML Math Module 1
- [ ] Notas: Resumen en propio formato
- [ ] Quiz: Completar ejercicios de comprensión

**Viernes:** (2 horas)
- [ ] Lectura: Historia de IA (1956-2022) timeline
- [ ] Video: "From ELIZA to ChatGPT" (30 min)
- [ ] Reflexión: Entender por qué ChatGPT fue breakthrough

**Sábado:** (1 hora)
- [ ] Revisión: Resumen de semana 1
- [ ] Notas: Preguntas para investigar en semana 2

**Domingo:** (1 hora)
- [ ] Planificación: Semana 2
- [ ] Prep: Descargar materiales necesarios

**Total Semana 1:** 12.5 horas ✓

---

## 5. HERRAMIENTAS Y SETUP INICIAL

### **Software Requerido (Todos Gratis/Open Source):**
```
- Python 3.11+ (ya tienes)
- Jupyter Notebook o VSCode + Jupyter
- Git (ya tienes)
- LLM APIs: OpenAI, Anthropic, HuggingFace (free tier)
```

### **Cuentas a Crear:**
1. OpenAI API (free credits iniciales)
2. Anthropic Claude (free tier)
3. HuggingFace account
4. Coursera (para auditar cursos gratis)
5. GitHub (para tus proyectos)

### **Instalación Rápida:**
```bash
# Python environment
python -m venv ai_learning
source ai_learning/bin/activate

# Core libraries
pip install langchain langgraph crewai jupyter pandas numpy

# For early phase
pip install transformers torch huggingface-hub

# APIs
pip install openai anthropic

# Utilities
pip install python-dotenv requests beautifulsoup4
```

---

## 6. MÉTRICAS DE PROGRESO

### **Objetivo Fase 1 (Semana 4):**
- [x] Entiendes diferencia entre IA tradicional y moderna
- [x] Puedes explicar transformers a alguien sin background IA
- [x] Sabes qué es fine-tuning y cuándo aplicarlo
- [x] Completaste al menos 1 proyecto pequeño

### **Objetivo Fase 2 (Semana 8):**
- [x] Puedes leer un paper sobre transformers y extraer ideas clave
- [x] Implementaste fine-tuning pequeño correctamente
- [x] Entiendes RAG arquitectura
- [x] Completaste proyecto sobre embeddings

### **Objetivo Fase 3 (Semana 14):**
- [x] Creaste 3 sistemas funcionales con RAG/LLM
- [x] Dominas prompting engineering
- [x] Integraste 5+ APIs diferentes
- [x] Proyecto final entrega valor real

### **Objetivo Fase 4 (Semana 20):**
- [x] Creaste MCP server funcional
- [x] Implementaste multi-agent system
- [x] Entiendes governance y monitoring
- [x] Proyecto final: Agentes autónomos coordinados

### **Objetivo Fase 5 (Semana 24):**
- [x] Portfolio de 5+ proyectos completados
- [x] Especialización clara en tu dominio
- [x] Propuesta documento para aplicar en industria
- [x] Plan 12 meses para próximas etapas

---

## 7. PRÓXIMOS PASOS INMEDIATOS (ESTA SEMANA)

### **Acción 1: Establece Ambiente**
```bash
mkdir ~/ai-learning
cd ~/ai-learning
python -m venv venv
source venv/bin/activate
pip install jupyter jupyterlab langchain openai
jupyter lab
```

### **Acción 2: Crea Notebook Inicial**
- Nombre: `Week-1-Progress.ipynb`
- Contenido: 
  - Reflexiones diarias (Md cells)
  - Código de experimentos (Code cells)
  - Notas de aprendizaje

### **Acción 3: Acceso a Recursos**
- [ ] Crear cuenta OpenAI (claim free credits)
- [ ] Crear cuenta HuggingFace
- [ ] Enroll en Coursera Math course
- [ ] Descargar "Attention Is All You Need" paper

### **Acción 4: First Experiment**
- Prompt: "Explica este concepto de IA de tres maneras diferentes"
- Ejecuta en ChatGPT, Claude, Gemini
- Documenta diferencias

### **Acción 5: Calendario**
- Bloquea 10-18 horas/semana en tu agenda
- Best time: Mañana (máxima concentración)
- Mantén consistency (mismo horario)

---

## 8. RECURSOS DE REFERENCIA RÁPIDA

### **Sitios Web Clave:**
```
Teoría:
- huggingface.co/docs
- deeplearning.ai
- coursera.org
- papers.withcode.com

Práctica:
- github.com/langchain-ai
- github.com/joaomdmoura/crewai
- modelcontextprotocol.io

Actualización:
- theneuron.ai
- arxiv.org (ai section)
- news.ycombinator.com/best
```

### **Papers Clave (en orden de lectura):**
1. "Attention Is All You Need" (2017) - fundamental
2. "Language Models are Unsupervised Multitask Learners" (2019) - GPT-2
3. "The Illustrated Transformer" (Jay Alammar) - explicación visual
4. "RAG papers from Meta" - retrieval augmented generation
5. Latest agentic AI papers (ArXiv, 2025)

### **Comunidades para Preguntas:**
- LangChain Discord: discord.gg/langchain
- Hugging Face Forums: discuss.huggingface.co
- Reddit: r/MachineLearning
- Local meetups Barcelona: Buscar "AI/ML Barcelona"

---

## 9. GESTIÓN DE TIEMPO REALISTA

**Si tienes 10 horas/semana:** Toma 8 meses (alarga por 2)
**Si tienes 15 horas/semana:** Toma 6 meses (plan estándar)
**Si tienes 20+ horas/semana:** Toma 4 meses (intensivo)

**Consejo:** Consistencia > Intensidad
- 10 horas/semana constantes > 30 horas erráticas
- Mejor dedicar M-V 2 horas que un sábado 10 horas
- Anota en calendario, trata como meetings críticas

---

## 10. REFLEXIÓN FINAL

Este no es un "curso rápido." Es una **inmersión de 6 meses** en una nueva dimensión tecnológica.

Al final de 24 semanas:
- Entenderás IA a nivel funcional profundo
- Habrás construido sistemas reales
- Tendrás portfolio de proyectos
- Podrás diseñar para el futuro de agentic AI
