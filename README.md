# Speech_To_Text
To use this code to transcribe an audio file, please make sure you:
Upload your audio file to this Colab workspace.
Set up your Google Cloud authentication. You can authenticate by pointing to a service account credentials JSON file:

import os
os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = "/path/to/your/service-account-key.json"

Call the function with your file path:

transcribe_file("your_uploaded_audio.wav")
