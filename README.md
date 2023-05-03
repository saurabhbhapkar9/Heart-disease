# Heart-disease
Build a model to classify if given the data of a patient should tell if the patient is at risk of heart attack

dataset with 303 entries and 14 features.

   age --> age
   sex --> 1 - M, 0 - F
   cp --> chest pain (0,1,2,3)
   -- Value 1: typical angina
   -- Value 2: atypical angina
   -- Value 3: non-anginal pain
   -- Value 4: asymptomatic
   trestbps --> When a patient is resting, what's his blood pressure
   chol --> cholestrol level
   fbs --> Blood sugar level when the person is fasting
        (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
   restecg --> when a person is resting, what's his ecg
   -- Value 0: normal
   -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
   thalach --> Maximum heart rate achieved
   exang --> chest pain for the people who hit gym very often. 0 -. NO CP, 1 -> CP
   oldpeak --> these are values of crest and trough of ecg
   slope --> slope values of ecg
   ca --> Maximum no. of major blood vessels --> 0,1,2,3
   thal --> 0,1,2
           Genetic disorder
           0 --> no genetic disorder
           1 --> ganetic disorder(fixed effect)
           2 --> genetic disorder(reversible)
   target --> whether the person is having a heart disease or not
         0 --> The person is not having heart disease
         1 --> The person is having a heart disease 
