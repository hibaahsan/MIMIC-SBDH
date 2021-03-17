# MIMIC-SBDH
Dataset containing 7,025 discharge summary notes from the MIMIC III dataset annotated for 7 SBDHs

MIMIC-SBDH is a data set containing 7,025 discharge summary notes randomly selected from the MIMIC III dataset.  The notes are annotated for the patient’s status of the following Social and Behavioral Determinants of Health (SBDHs):
1. Community
2. Economics
3. Education
4. Environment
5. Alcohol Use
6. Tobacco Use
7. Drug Use.
In addition, we mark SBDH-related keywords are also marked in the notes. The folder contains two files:
1. MIMIC-SBDH.csv: This file contains the labels for the seven SBDHs:
	a. Community-Present (0: False, 1: True)
	b. Community-Absent (0: False, 1: True)
	c. Education (0: False, 1: True)
	d. Economics (0: None, 1: True, 2: False)
	e. Environment (0: None, 1: True, 2: False)
	f. Alcohol Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)
	g. Tobacco Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)
	h. Drug Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)

2. MIMIC-SBDH-keywords.csv: This file contains the start and end indices of the SBDH-related keywords.


