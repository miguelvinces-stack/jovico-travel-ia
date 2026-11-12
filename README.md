# JoViCo Travel IA | Planificador Inteligente de Viajes con RAG

Aplicación web interactiva que implementa una arquitectura pedagógica y funcional de **IA Generativa en el navegador**, integrando:

1. **RAG Local (Retrieval-Augmented Generation)**: Carga y análisis en memoria de archivos CSV turísticos utilizando PapaParse y algoritmo de ponderación léxica para inyección de contexto.
2. **Chain-of-Thought (CoT) Prompting**: Ensamblaje transparente de instrucciones paso a paso con salida forzada en esquema JSON estricto.
3. **Soporte Híbrido LLM / Simulación (Mock Engine)**:
   - Conexión directa vía API a **Google Gemini 1.5 Flash** u **OpenAI GPT-4o-mini**.
   - Modo de simulación autónomo (Mock Engine) sin necesidad de API Key, ideal para demostraciones offline.
4. **Módulo Educativo Comparativo**: Análisis pedagógico entre *Prompt Engineering / CoT*, *RAG* y *Fine-Tuning*.

---

## Archivos del Proyecto

- [index.html](file:///d:/Onedrive%20drjor/OneDrive/Documents/MAESTRIA%20IA/antigravity/index.html): Aplicación completa Single-Page Application (HTML5, Tailwind CSS, PapaParse, Lucide Icons y Vanilla JS).
- [destinos_muestra.csv](file:///d:/Onedrive%20drjor/OneDrive/Documents/MAESTRIA%20IA/antigravity/destinos_muestra.csv): Archivo CSV de prueba con destinos (Cusco, Kioto, París) y atributos enriquecidos.

---

## Cómo Ejecutar

Basta con abrir el archivo [index.html](file:///d:/Onedrive%20drjor/OneDrive/Documents/MAESTRIA%20IA/antigravity/index.html) en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari). No requiere servidor backend ni dependencias Node.js.
