# Checkpoint 1 - Coordinador de Agenda

Flujo de n8n que implementa un AI Agent (Tools Agent) para gestionar solicitudes 
de reuniones de forma autónoma, verificando disponibilidad y agendando en 
Google Sheets.

## Componentes
- Chat Trigger
- AI Agent (modo Tools Agent, maxIterations: 10, modelo Groq/Llama 3.3 70B debido a que es gratis)
- Tools: Disponibilidad (lectura) y Agendamiento (escritura) en Google Sheets
- Notificación por Gmail condicionada a que la reunión se haya confirmado

⚠️ Nota: el JSON exportado no incluye credenciales por motivos de seguridad.

Link al archivo sheets https://docs.google.com/spreadsheets/d/1HGd4B3K-kWFjlPIf1gPp-a8cU8QJAwWXnFQk4c_hGNs/edit?usp=sharing
