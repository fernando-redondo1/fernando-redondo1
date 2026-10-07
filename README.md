# Hola, soy Fernando Redondo 👋

### Ciberseguridad Junior | Bastionado de sistemas y redes | Datos e IA

La tecnología siempre me ha fascinado, y la ciberseguridad es lo que más me motiva: cómo se protegen los sistemas, cómo fallan y cómo afecta eso al día a día de una empresa. Mi objetivo es aportar una base técnica sólida y la actitud adecuada al análisis y la defensa de entornos digitales, y cada vez más, a extraer información útil de los datos para tomar decisiones.

---

## Perfil técnico

- **Formación:** CFGS en Desarrollo de Aplicaciones Web (DAW) y Sistemas Microinformáticos y Redes (SMR), y Curso de Especialización en Ciberseguridad.
- **Enfoque:** Blue Team / SOC, monitorización y respuesta en endpoints (EDR/XDR), bastionado de sistemas (Linux/Windows) y análisis forense.
- **Datos e IA:** pipelines de Machine Learning, procesos ETL, cuadros de mando en Power BI, MySQL y análisis de datos con Python (pandas, scikit-learn).
- **Infraestructura:** gestión de firewalls, redes TCP/IP y contenedores con Docker.
- **Idiomas:** español nativo, inglés B1 (Cambridge).

---

## Proyectos y herramientas

> Algunos proyectos se han desarrollado con apoyo de IA. Mi trabajo se centra en el diseño, las pruebas y la validación de los resultados.
### Ciberseguridad

- **[Escáner de red modular (InfoScann)](https://github.com/fernando-redondo1/port-scanner)**: herramienta de reconocimiento de red con escaneo concurrente, connect scan y SYN scan (*half-open*) con Scapy, distinción entre puertos abiertos, cerrados y filtrados, *banner grabbing* con lectura de certificados TLS e identificación pasiva del sistema operativo por TTL. Soporta subredes CIDR e IPv6, y exporta los resultados a JSON para su ingesta en un SIEM. Se distribuye como paquete pip e imagen Docker publicada en GHCR.
  - `Python` · `Scapy` · `Docker` · `Redes`

- **[Blue Team Log Analyzer](https://github.com/fernando-redondo1/blue-team-log-analyzer)**: motor ligero de monitorización de logs escrito en Go para detectar anomalías en tiempo real en entornos SOC. Analiza logs del sistema y de autenticación con reglas configurables, detecta patrones de fuerza bruta, accesos no autorizados e indicios de escalada de privilegios, y genera alertas estructuradas y priorizadas con muy poco consumo de recursos.
  - **Procesamiento rápido:** usa la concurrencia nativa de Go (goroutines y channels) para procesar con baja latencia.
  - **Reglas de detección personalizables:** intentos fallidos de SSH, manipulación de logs y ataques web.
  - **Despliegue sin dependencias:** se compila en un único binario para ejecutarlo directamente en los equipos monitorizados.
  - `Go` · `Análisis de logs` · `Monitorización`

- **[CyberSOC Telegram Bot](https://github.com/fernando-redondo1/cybersoc-telegram-bot)**: asistente de ciberseguridad para Telegram basado en LangChain y Ollama, con un modelo de lenguaje que se ejecuta en local. Responde dudas de seguridad y apoya tareas de tipo SOC sin enviar datos a APIs de terceros.
  - `Python` · `LangChain` · `Ollama` · `LLM local`

### Datos e IA

- **[Predicción de la gravedad de la pancreatitis aguda](https://github.com/fernando-redondo1/acute-pancreatitis-severity-prediction)**: pipeline de Machine Learning con datos de 1.206 pacientes reales para predecir la gravedad clínica en el ingreso (AUC-ROC 0,92). ETL con pandas y MySQL, clasificación con Random Forest + SMOTE y visualización en un cuadro de mando de Power BI.
  - `Python` · `scikit-learn` · `MySQL` · `Power BI`

- **5G, IA y Big Data (Integra Conocimiento)**: formación especializada en análisis de datos, elaboración de informes con indicadores clave de negocio y obtención de conclusiones útiles para la toma de decisiones.

---

## Tecnologías

**Ciberseguridad:** Splunk · Metasploit · Bastionado Linux · TCP/IP · Docker · AWS

**Datos e IA:** Python · scikit-learn · pandas · Power BI · MySQL

---

## Certificaciones y laboratorios

- **AWS Certified Cloud Practitioner**, Amazon Web Services (2025)
- **Splunk SOC Analyst** (itinerario formativo), Splunk STEP (2026)
- **Introduction to Cybersecurity**, Cisco Networking Academy
- **HackTheBox:** @Fernandoredondo1
- **TryHackMe:** ferredit26

---

## Contacto

- **LinkedIn:** [linkedin.com/in/fernando-redondo-perez](https://www.linkedin.com/in/fernando-redondo-perez)
- **Email:** ferredit26@gmail.com
