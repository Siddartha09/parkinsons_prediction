Parkinson’s disease (PD) is a chronic neurodegenerative disorder characterized by the progressive loss of dopaminergic neurons.
Previous studies report that approximately 70%–90% of patients with PD show some form of vocal impairment. 
The dataset used is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD).
The main aim of this assignment is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD.

The original data is in ASCII CSV format which has been converted to .xlsx for analysis. 
The rows of the CSV file contain an instance corresponding to one voice recording. 
There are around six recordings per patient, the name of the patient is identified in the first column.

Attirbutes Information:

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency

MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude

NHR,HNR - Two measures of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE,D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation


We tried to build several machine learning algorithms to diagnose Parkinson's disease and find the key predictors.
