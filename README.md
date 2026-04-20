# Pizzeria Rapallo - AI Chatbot

Questo progetto contiene il workflow n8n per la gestione automatizzata degli ordini della Pizzeria Rapallo.

## Funzionalità
- **AI Chatbot**: Utilizza OpenAI per comprendere le richieste dei clienti.
- **Memoria**: Mantiene il contesto della conversazione.
- **Integrazione Google Sheets**: Salva automaticamente gli ordini in un foglio di calcolo dedicato.

## Come utilizzare questo workflow
1. Assicurati di avere un'istanza [n8n](https://n8n.io/) attiva.
2. Scarica il file `Pizzeria Chatbot Veloce.json` da questa repository.
3. Importa il file su n8n tramite la funzione "Import from File".
4. Configura le credenziali necessarie:
   - **OpenAI API Key** per l'AI Agent.
   - **Google Sheets API** per il salvataggio degli ordini.
