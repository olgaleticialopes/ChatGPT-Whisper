# 📓🔗 ChatGPT+ Whisper - Voice chat with chatGPT using Whisper (openAI) and python

~~~~mermaid
classDiagram
  class RecordingUserAudio {
    pythonScript: string
    jsScript: string
    recordAudio(): void
  }

  class WhisperSpeechRecognition {
    openaiAPI: string
    convertToText(audioData): string
  }

  class ChatGPTIntegration {
    gptAPI: string
    integrateWithChatGPT(textData): string
  }

  class SynthesizeUsinggTTS {
    googleTTSAPI: string
    synthesizeText(textData): audioFile
  }

  RecordingUserAudio --|> WhisperSpeechRecognition
  WhisperSpeechRecognition --|> ChatGPTIntegration
  ChatGPTIntegration --|> SynthesizeUsinggTTS

~~~~

Explore the codebase in detail on [GitHub](https://github.com/olgaleticialopes/ChatGPT-Whisper/blob/main/Whisper_e_ChatGPT.ipynb). The code initially started in Google Colab and has been seamlessly exported to GitHub. Dive into the intricacies of the application and witness the evolution from Colab to a more polished GitHub version.
