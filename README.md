# Multimodal Virtual Assistant for Personal Finance

Project developed during the Master in AI Developer at Profession AI

An innovative project developed in **Google Colab** that combines speech recognition, advanced NLP, and data analysis to deliver a virtual assistant capable of understanding and responding to financial queries in a natural and personalized way.

## Key Features

- **Speech transcription** with [Whisper](https://github.com/openai/whisper)
- **Natural language understanding** using zero-shot NLP (Hugging Face)
- **Transaction analysis** on a mock dataset
- **Personalized responses** based on user intent
- **Conversational flow management** with [LangGraph](https://github.com/langchain-ai/langgraph)
- Supports both **voice and text input**

## Sample Interaction

> User: *"How much did I spend this week?"* (audio)  
> Assistant: *"You spent 81 euros this week."*

## Architecture

The system is composed of three main modules:

1. **ASR (Automatic Speech Recognition)** – transcribes audio into text  
2. **NLP** – detects user intent via zero-shot classification  
3. **Response Generator** – analyzes data and returns a coherent answer  

All orchestrated through a state graph using **LangGraph**, enabling fluid and modular conversations.

## Future Enhancements

I met all project requirements, but also explored ways to evolve the assistant:

- **Visual representation of weekly expenses** using **Matplotlib**
- **Voice output** for fully multimodal responses
- **Integration with real financial APIs** for live data
- **Mobile-friendly interface** for on-the-go access

## Technologies Used

- Python 3.10+
- Google Colab
- Whisper
- Hugging Face Transformers
- LangGraph
- Torchaudio
- Matplotlib (planned extension)



