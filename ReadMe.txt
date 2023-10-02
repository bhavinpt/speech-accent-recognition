Created By: Bhavin Patel (015954770) as a part of EE257 Spring 2022 term project

To generate the MFCC coefficient:  (This is not a part of main code. It is optional. You may use it to see how additional MFCC are calculated)

1. Download and extract this folder : https://drive.google.com/drive/folders/1o7PBS7bE0EgSK5JEVsGfsryLnu36FeOl?usp=sharing
	-- It will have the top level directory 'EE257-Term_project_MFCC-Generator_Speech_accent_archive'
2. Start jupyter notebook with root set to 'EE257-Term_project_MFCC-Generator_Speech_accent_archive' directory
3. Run Audio-splitter_EE257_Term-Project_Bhavin-Patel-015954770.ipynb
	-- this will generate audio files containing word inside 'EE257-Term_project_MFCC-Generator_Speech_accent_archive/audio_processed/splitAudio' directory.
4. Run MFCC-calculator_EE257_Term-Project_Bhavin-Patel-015954770.ipynb
	-- this will generate a 'mfcc_calc.csv' file inside 'EE257-Term_project_MFCC-Generator_Speech_accent_archive/audio_processed' directory.
	-- Note: if mfcc_calc.csv already exists then you may need to remove it
5. Explore the new generated MFCC in mfcc_calc.csv