How to use:
- Apply this filter to the video source you want to capture and configure the settings below. Then, use func_start to start - stop when you want to stop

Settings
- "path": directory where the file goes
- "filename": name of the file, be sure to append the .format such as .flv etc
- "audio_track": 1 to MAX_AUDIO_MIXES
- "audio_source": name of the source where audio comes from 
- "encoder": from api_get_available_encoders

Functions
- func_start("")
	Starts recording

- func_stop("")
	Stops recording

- func_get_available_formats("")
	Returns a list of valid encoder formats for the host machine
