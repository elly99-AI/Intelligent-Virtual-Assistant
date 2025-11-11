# Assistente Virtuale Multimodale per la Finanza Personale

Un progetto innovativo sviluppato in **Google Colab** che combina riconoscimento vocale, NLP avanzato e analisi dati per offrire un assistente virtuale capace di comprendere e rispondere a richieste finanziarie in modo naturale e personalizzato.

## Funzionalità principali

- **Trascrizione vocale** con [Whisper](https://github.com/openai/whisper)
- **Comprensione del linguaggio naturale** con NLP zero-shot (Hugging Face)
- **Analisi di transazioni** su dataset fittizio
- **Risposte personalizzate** basate sull’intento dell’utente
- **Gestione del flusso conversazionale** con [LangGraph](https://github.com/langchain-ai/langgraph)
- Supporto sia per **input vocali** che **testuali**

## Esempio d’interazione

> Utente: *"Quanto ho speso questa settimana?"* (audio)  
> Assistente: *"Hai speso 81 euro questa settimana."*

## Architettura

Il sistema è composto da tre moduli principali:

1. **ASR (Automatic Speech Recognition)** – trascrive l’audio in testo
2. **NLP** – rileva l’intento dell’utente tramite classificazione zero-shot
3. **Generatore di Risposte** – analizza i dati e restituisce una risposta coerente

Il tutto orchestrato tramite un grafo di stati con **LangGraph**, per una conversazione fluida e modulare.

## Idee per evoluzioni future

Ho rispettato tutti i requisiti del progetto, ma ho anche pensato a come renderlo ancora più potente:

- **Visualizzazione delle spese settimanali** con **Matplotlib**
- **Output vocale** per una risposta completamente multimodale
- **Integrazione con API finanziarie reali** per dati aggiornati
- **Interfaccia mobile-friendly** per accesso ovunque

## Tecnologie utilizzate

- Python 3.10+
- Google Colab
- Whisper
- Hugging Face Transformers
- LangGraph
- Torchaudio
- Matplotlib (in fase di estensione)

