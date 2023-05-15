# Exploring the potential of ML/DL for early Alzheimer's detection

# Dataset Description 
For Alzheimer's Detection using EEG. The dataset is downloaded from https://osf.io/s74qf/ .The database was created by Florida State University researchers using a Biologic Systems Brain Atlas III Plus workstation to record from the 19 scalp (Fp1, Fp2, Fz, F3, F4, F7, F8, Cz, C3, C4, T3, T4, Pz, P3, P4, T5, T6, O1, and O2) loci of the worldwide 10-20 system. Cerebral lobes F–T (F: frontal, C: central, P: parietal, O: occipital, and T: temporal). Four groups—A, B, C, and D—recorded in two rest states: eyes open (A and C) by visually fixating and eyes closed (B and D) utilizing a linked-mandible reference forehead ground. 24 healthy seniors comprise Groups A and B. Groups C and D have 24 likely AD patients . 8-s EEG segments band-limited to 1-30 Hz were recorded at 128 Hz and extracted without eye motion, blinking. EEG technicians tracked each patient's attention.The dataset sample size of 48 is converted to 192 in total using Data Augmentation techniques such as  
  
    i)  Time Shifting and Noising  
    ii) Rolling Mean   

  
# Model Training

For the EEG dataset(Augmented), the models used are tree based models,Probablity based models,non linear models and taking into account the small dataset combined predictions from best models are used to produce final output using majority voting.  

For EEG dataset (Non-Augmented), Few Shot Learning neural network models have been applied on the 48 samples. Few-shot learning is a subfield of machine learning that addresses the problem of insufficient data by enabling models to learn new concepts from a small number of labelled examples. It emphasizes training models to recognize or classify new classes or concepts with limited labelled data, typically one to several examples per class. For models to generalize effectively and achieve high accuracy in conventional machine learning, a large amount of labelled data is required. In medical imaging, it may be impractical or impossible to obtain such comprehensive labelled data for each class or concept. At this juncture, few-shot learning enters into play.
Instead of relying on a large labelled dataset, few-shot learning generalizes knowledge from a larger set of classes or domains to new concepts. When data is limited, this makes the solution more effective and efficient. Utilizing Siamese neural networks, the Siamese method is an efficient technique for few-shot learning. Siamese networks consist of paired neural networks that share weights and are trained to discover similarity metrics between inputs. The Siamese method is particularly useful for tasks involving comparisons of similarity.

  

