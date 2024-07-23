__*ALL THANKS TO OLLAMA API*__

This is intended to be a highschool kid python project that aims at a chatbot with face unlock, speech recognition with google's engine, text-to-speech responses and much more. The aim was to simply kill time, and I'm pretty much confident that I peaked at it, I mean...at killing time. *Only the python script available at the moment.*

__System Requirements__ :
              
1. Atleast 16 GB RAM.
2. Preferrably a GPU that is listed on -- https://github.com/ollama/ollama/blob/main/docs/gpu.md#gpu.
3. A modern CPU (at least quad-core) with high-performance capabilities.

__STEPS__ :

1. Download and install Ollama for your OS from : https://ollama.com/download
2. Download and install python from : https://www.python.org/downloads/
3. Necessary python libraries are speech_recognition, pyttsx3, requests, json, cv2, face_recognition, time, subprocess and os.
4. Have Ollama up and running. To do that, on the terminal type 'ollama serve'. This should also give you a tcp address like 127.0.0.1:11434 with an error because ollama has already been occuppied at a port, note the address down.
5. On line 50 of the python file, type in the correct port as obtained from the terminal on step 4.
6. Remember that if you are using speech recognition, the language is set to English-India, and this is intentional. If you want to use any other ones please do so. on line 19.
7. Speech recognition uses google's engine thus requiring internet connection. If you are keen on running it completely offline, use the Typing input method as input method.


