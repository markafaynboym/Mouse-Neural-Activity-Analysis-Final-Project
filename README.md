# Mouse-Neural-Activity-Analysis-Final-Project
Final Project of STA 207 On the Neural Activity and Decision making of mice

We study a subset of the data used in the research from Steinmetz (2019) in which 
the neural activity of mice is recorded in response to visual stimuli and make a decision.

We had 
1. Run a full EDA, inference and sensitivity analysis
2. Considered the potential loss of additional info by averaging by neuron and thus 
    used heirarchical clustering to group neurons by their firing behavior
3. We analyzed firings rates correspond to both left and right stimuli including their interaction using ANOVA.
4. We then used logistic regression to predict whether a mouse responds correctly or not based on the stimuli. 

The full analysis is documented in Mouse_NeuralActivity_Analysis.Rmd.
