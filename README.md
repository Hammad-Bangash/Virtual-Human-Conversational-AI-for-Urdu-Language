<h1>Virtual Human Assistant in Urdu</h1>
<p>This repository documents our project where we integrated a fine-tuned TTS model with a language model (LLM) to create a virtual human assistant that communicates in Urdu. This assistant can understand and respond in Urdu, making it a powerful tool for native Urdu speakers.</p>
<h2>Project Overview</h2>
<p>The project combines the capabilities of a Text-to-Speech (TTS) model and a fine-tuned Language Model (LLM) to create a seamless virtual human assistant. The TTS model converts text responses from the LLM into natural-sounding speech in Urdu, providing an engaging and interactive experience for users.</p>
<h2>Fine-Tuning the TTS Model</h2>
<p>Our TTS model was fine-tuned specifically for Urdu with the following steps:</p>
<ul>
<li><strong>Dataset Collection:</strong> We gathered a custom dataset of 300 male Urdu voice samples.</li>
<li><strong>Preprocessing:</strong> The audio files were normalized, trimmed, and resampled to 16kHz to fit the SpeechT5 model requirements.</li>
<li><strong>Transcription:</strong> Each audio sample was manually transcribed to ensure accuracy.</li>
<li><strong>Phonetization and Transliteration:</strong> The transcribed Urdu text was converted into its phonetic representation and then transliterated into English using web scraping techniques.</li>
<li><strong>Model Fine-Tuning:</strong> The SpeechT5 model was fine-tuned for 32,000 steps, achieving an accuracy of 60%.</li>
 <li><strong>Evaluation:</strong> The model's performance was assessed in terms of accuracy and naturalness of the synthesized speech.</li>
  </ul>
<h2>Integrating with the Language Model</h2>
<p>The fine-tuned TTS model was integrated with a language model that was instruction-tuned to understand and generate human-like responses. The integration process involved:</p>
<ul>
<li><strong>Instruction Fine-Tuning:</strong> The LLM was fine-tuned with specific instructions to simulate human-like conversational abilities.</li>
  <li><strong>Language Compatibility:</strong> The LLM was adapted to understand and generate responses in Urdu.</li>
  <li><strong>Speech Synthesis:</strong> The LLM-generated responses were passed through the TTS model to produce audible speech in Urdu.</li>
</ul>
<h2>Virtual Human Assistant</h2>
<p>The virtual human assistant can understand and respond to queries in Urdu, providing a natural and interactive user experience. This assistant can be used for various applications, such as customer service, virtual tutoring, and more.</p>



https://github.com/Hammad-Bangash/Virtual-Human-Conversational-AI-for-Urdu-Language/assets/129145452/f70d980e-0b57-4846-80ca-63e6938646a8


<h3>Telegram Interface</h3>
<p>We utilized a Telegram interface for interacting with the virtual human assistant, making it easy to test and use the model in real-time.</p>
<h3>Data Requests</h3>
<p>Due to privacy and storage limitations, we won't be uploading the dataset audios and other files. If you are interested in accessing the dataset, please email us at <a href="mailto:hammadraza12304@gmail.com">hammadraza12304@gmail.com</a>.</p>
<h3>Microsoft SpeechT5 Model</h3>
<p>For more information on the Microsoft SpeechT5 model, visit the official page: <a href="https://github.com/microsoft/SpeechT5">Microsoft SpeechT5</a>.</p>
</body>
