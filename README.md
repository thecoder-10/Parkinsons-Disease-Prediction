# Parkinsons Disease Prediction
Implementing different supervised machine learning models to predict Parkinsons in patients based on vocal features.
<br>


Parkinsons Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Thus, here we will use a dataset which contains vocal features of 195 different patients to train the model. 
<br><br>Dataset Information:
<br>
Rows - 195
<br>
Columns/Features - 24
<br><br>
Feature Description:
<br>
name - ASCII subject name and recording number
<br>
MDVP:Fo(Hz) - Average vocal fundamental frequency
<br>
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
<br>
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
<br>
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several
measures of variation in fundamental frequency
<br>
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
<br>
NHR,HNR - Two measures of ratio of noise to tonal components in the voice
<br>
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
<br>
RPDE,D2 - Two nonlinear dynamical complexity measures
<br>
DFA - Signal fractal scaling exponent
<br>
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation
