# Pitch-Estimator
Estimate the pitch of waveforms

This GUI estimates the pitch of waveforms as described in "Theory and Applications of Digital Speech Processing" by Lawrence Rabiner Ronald Schafer.

1) To start the GUI type "Extract_Pitch";

2) "Upload directory": Upload the directory where the waveforms that need to be analyzed are stored. The code will loop through all the ".wav" files that it finds in the selected directory;

3) "Parameters time window (ms)": Choose a time window for the analysis;

4) "Parameters Auto-correlation Analysis": This is the Clipping Level (CL) expressed as percentage of the maximum signal level for the 3-level center clipped approach. This parameter is available only when the "Auto-correlation" analysis is selected;

5) "Parameters Spectral Analysis": This is the number of loops for the Spectral Analysis. At each loop, the scale of the FFT will be changed. This parameter is available only when the "Spectral Analysis" analysis is selected;

6) "Analysis": The user can select 3 different types of analysis: 1) Auto-correlation, 2) Complex Cepstrum and 3) Spectral Analysis;

7) "Extract Pitch": The code will be executed. A figure with the results will be saved in the same folder selected in "Upload directory". The name of the new waveforms will be the "Pitch_orginal_name_Analysis_Selected.fig". For instance, if the original name was "DAbase_I", the figure will be saved with the name "Pitch_DAbase_I_Spectral_Analysis.fig", if the analysis selected was "Spectral Analysis";

These Matlab files are part of a large Toolbox that I wrote and that I am using to analyze EEG and MEG data.

If you have any question and/or want to report bugs, please e-mail me (Ale) at: pressalex@hotmail.com
