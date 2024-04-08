Draft (how to proceed with EDA): (DONE)

- Planning to bifercate ages in groups and then plot the distribution of heart disease in each group. (DONE)
- Planning to see how gender is related to heart disease. (Done)
- Planning to see how which chest pain type is more related to heart disease and what is the distribution of chest pain type in heart disease cases. (Done)
- Plot RestingBP to see how it is values are distributed. But it is not much correlated to output variable. So we can ignore this variable. But still we can plot it. (Done)
- Plot Cholesterol to see how it is values are distributed. (Done)
- Plot FastingBS to see how it is values are distributed and relared to output variable. (Done)
- Plot RestingECG to see how it is values are distributed and relared to output variable. (Done)
- Plot MaxHR to see its distibution (Done)
- Plot ExerciseAngina to see its distribution and relation with output variable. (Done)
- Plot Oldpeak to see its distribution and relation with output variable. (Done)
- Plot ST_Slope to see its distribution and relation with output variable (Done).


// Some planned steps: (DONE)
- build pipeline
  
// Try generating new features from the existing one

// Try removing RestingBP and train the model again.

// Outlier analysis
    - On RestingBP
  
// Try finding correlation b/w categorical features

// What if new unknown value contains 0 cholestrol, then we need to use our trained model to replace cholestrol value. So for that ig i'll need pipeline