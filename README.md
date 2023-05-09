# Exploring the potential of ML/DL for early Alzheimer's detection

# Dataset Description 
For Alzheimer's Detection using EEG. The dataset is downloaded from https://osf.io/s74qf/ .The database was created by Florida State University researchers using a Biologic Systems Brain Atlas III Plus workstation to record from the 19 scalp (Fp1, Fp2, Fz, F3, F4, F7, F8, Cz, C3, C4, T3, T4, Pz, P3, P4, T5, T6, O1, and O2) loci of the worldwide 10-20 system. Cerebral lobes F–T (F: frontal, C: central, P: parietal, O: occipital, and T: temporal). Four groups—A, B, C, and D—recorded in two rest states: eyes open (A and C) by visually fixating and eyes closed (B and D) utilizing a linked-mandible reference forehead ground. 24 healthy seniors comprise Groups A and B. Groups C and D have 24 likely AD patients . 8-s EEG segments band-limited to 1-30 Hz were recorded at 128 Hz and extracted without eye motion, blinking. EEG technicians tracked each patient's attention.The dataset sample size of 48 is converted to 192 in total using Data Augmentation techniques such as  
  
    i)  Time Shifting and Noising  
    ii) Rolling Mean   

  
# Model Training

For the EEG dataset(Augmented), the models used are tree based models,Probablity based models,non linear models and taking into account the small dataset combined predictions from best models are used to produce final output using majority voting.  
For EEG dataset(Non-Augmented), Few Shot Learning neural network models have been applied on the 48 samples.In deep learning, few-shot learning involves training a neural network to learn from only a few examples of each class or category. The goal is to enable the network to quickly generalize to new classes, without requiring a large amount of additional labeled data for each new class.
  

