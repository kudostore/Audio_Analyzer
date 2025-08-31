# Audio_Analyzer
This code downloads a YouTube video, extracts the audio, transcribes the audio, and then performs several analyses on the transcription, including calculating talk time ratio, counting questions, determining the longest monologue, and analyzing the overall sentiment of the call.

Approach

My approach involves downloading the YouTube video and extracting the audio. I then use the Whisper model to transcribe the audio. Finally, I analyze the transcription to calculate the talk time ratio for each speaker, count the number of questions asked, determine the longest monologue duration, and assess the overall sentiment of the call using VADER sentiment analysis. Based on these analyses, I generate an actionable insight.

Tasks :

Create a system that takes a sales call recording and returns:

Talk-time ratio (what % each person spoke)
Number of questions asked
Longest monologue duration
Call sentiment (positive/negative/neutral)
One actionable insight
