# Speech-EndPoint-Detector
This Python script provides a method for speech endpoint detection in audio recordings.
The script identifies the starting and ending points of speech in order to facilitate further processing, analysis, or segmentation of speech segments within the audio.
**Usage:**
To use the speech endpoint detection script, follow these steps:

Install the required dependencies by running pip install librosa numpy matplotlib.
Place your audio file in a suitable location and specify the file path within the script.
Adjust the desired threshold values for energy and silence within the speech_endpoint_detector function. By default, the energy threshold is set to 0.1 and the silence threshold to 0.5.
Run the script and observe the output.
**Output:**
The script generates a graphical representation of the audio signal, along with additional information such as the magnitude and zero-crossing rate. The voice activity estimate, indicating the presence of speech, is also plotted.
Additionally, the script prints the start and end times of the speech segment in seconds, allowing for precise identification of the speech duration within the audio recording.
