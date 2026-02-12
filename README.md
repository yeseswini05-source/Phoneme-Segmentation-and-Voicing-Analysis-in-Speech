Phoneme Segmentation and Voicing Analysis in Speech

1	Objective
The objective of this experiment is to analyze speech signals in the time domain and study different phoneme classes by:
•	Segmenting speech into phoneme-level units
•	Identifying voiced and unvoiced sounds
•	Studying fricatives and approximants
•	Comparing waveform characteristics and airflow behavior
2	Procedure
Speech was recorded using a laptop microphone. Google Colab and Python were used for processing. Librosa was used to load audio signals and Matplotlib was used for waveform visualization. Manual time-based segmentation was applied to extract phoneme regions.
3	Implementation (Python Code)
This section presents the code used to load speech signals, segment phonemes, and visualize the waveforms.
3.1	Loading Audio and Plotting Sentence 1
 
-Python code for loading the audio files and plotting the waveform of Sentence 1
This code loads both recordings using Librosa and generates the time-domain waveform.

3.2	Phoneme Segmentation Function
 
-Function used to extract and plot individual phoneme segments
The function extracts specific time intervals and visualizes selected phonemes separately.

3.3	Plotting Sentence 2 Waveform
 
-Code used to display the waveform of the second sentence
This visualization helps identify fricative and approximant regions.

3.4	Extracting Fricative and Approximant
 
-Code used to extract fricative (/s/) and approximant (/y/) segments
Selected intervals are plotted for airflow and turbulence analysis.

4	Objective 1: Phoneme Segmentation and Voicing Analysis

4.1	Full Sentence Waveform
 
 -Time-domain waveform of Sentence 1
The waveform clearly shows speech activity and silent regions.
4.2	Unvoiced Segment (sh)
 
-Extracted unvoiced phoneme (sh)
Characteristics:
•	Noise-like
•	Aperiodic
•	No vocal fold vibration
4.3	Voiced Segment (b)
 
-Extracted voiced phoneme (b)
Characteristics:
•	Periodic waveform
•	Smooth oscillations
•	Higher energy
•	Vocal fold vibration present

4.4Comparison: Voiced vs Unvoiced
Feature	Voiced	Unvoiced
Periodicity	Present	Absent
Energy	High	Low
Waveform	Smooth	Noisy

5	Objective 2: Fricatives and Approximants
5.1	Sentence 2 Waveform
 
-Time-domain waveform of Sentence 2
5.2	Fricative (/s/)
 
-Extracted fricative (/s/)
Characteristics:
•	Irregular and noisy
•	Turbulent airflow
•	High Reynolds number
5.3	Approximant (/y/)
 
-Extracted approximant (/y/)
Characteristics:
•	Smooth waveform
•	Periodic structure
•	Laminar airflow
•	Low Reynolds number
6	Learning Outcomes
•	Understood phoneme segmentation
•	Distinguished voiced and unvoiced sounds
•	Identified fricatives and approximants
•	Related airflow turbulence with acoustic patterns
•	Gained practical experience in speech signal processing
7	Conclusion
The experiment successfully demonstrated phoneme segmentation and classification using time-domain waveform analysis. Voiced sounds showed periodic behavior due to vocal fold vibration, while unvoiced sounds were noise-like. Fricatives exhibited turbulent airflow and irregular signals, whereas approximants showed smoother and periodic patterns. This study confirms that different phoneme classes possess distinct acoustic characteristics.
