# MIMIC-SBDH
Dataset containing 7,025 discharge summary notes from the MIMIC III dataset annotated for 7 SBDHs

MIMIC-SBDH is a data set containing 7,025 discharge summary notes randomly selected from the MIMIC III dataset.  The notes are annotated for the patient’s status of the following Social and Behavioral Determinants of Health (SBDHs):
1. Community
2. Education
3. Economics
4. Environment
5. Alcohol Use
6. Tobacco Use
7. Drug Use.

In addition, we mark SBDH-related keywords are also marked in the notes. The folder contains two files:

**MIMIC-SBDH.csv**: This file contains the labels for the seven SBDHs:
1. Community-Present and Community-Absent (0: False, 1: True)
2. Education (0: False, 1: True)
3. Economics (0: None, 1: True, 2: False)
4. Environment (0: None, 1: True, 2: False)
5. Alcohol Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)
6. Tobacco Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)
7. Drug Use (0: None, 1: Present, 2: Past, 3: Never, 4: Unsure)
 
**MIMIC-SBDH-keywords.csv**: This file contains the start and end indices of the SBDH-related keywords.


