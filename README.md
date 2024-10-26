# Meeting_Summarization

1. **Project Overview**
   
      Meetings are vital for communication, strategic planning, and decision-making within organizations. However, manually summarizing meetings is time-consuming and labor-intensive, which can reduce productivity, slow decision-making,
      and result in missed insights. This project presents an Automated Meeting Summarization System designed to optimize efficiency, enhance knowledge sharing, and facilitate informed decision-making.

2. **AI Models Used**
   
   1. **Whisper by OpenAI**
      
      **Purpose:** Audio-to-text transcription
      
      **Description:** Whisper is a highly versatile speech recognition model, developed by OpenAI, capable of transcribing spoken language into text accurately across diverse languages.
      
      **Training Data:** Trained on 680,000 hours of multilingual and multitask data from the web, Whisper handles a variety of language tasks with robust accuracy.
      
   2. **Gemma 7B by Google**
      
      **Purpose:** Text summarization
      
      **Description:** Gemma 7B is a state-of-the-art text-to-text model designed for multiple tasks such as question answering, summarization, and reasoning.
      
      **Training Data:** It has been trained on a diverse dataset that includes web documents, code, and mathematical content, making it adaptable to various linguistic styles and topics.

3. **Process Flow**
   
   1. **User Upload/Recording:** Users can upload a pre-recorded audio file or record a live meeting through the app.
      
   2. **Whisper AI Transcription:** Whisper converts spoken audio into transcribed text.
      
   3. **Text Preparation:** Transcribed text is formatted and prepared for summarization.
      
   4. **Gemma 7B Summarization:** Gemma 7B summarizes the transcribed text into a concise meeting overview.
      
   5. **Summary Display:** The app displays the summarized text alongside the original audio file, which can be replayed.
