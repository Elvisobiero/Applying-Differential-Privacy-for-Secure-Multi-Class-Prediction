# Applying-Differential-Privacy-for-Secure-Multi-Class-Prediction

In this exercise, I test privacy measures for secure multi-class prediction problem. In this case i was trying to classify the type of obesity that one has. In the notebook, I had the target column with the following values ["Healthy", "At_risk", "Diagnosed", "Under_Observation"]. In the notebook, i compare how the accuracy changes with different types of perturbation. I had 3 types of perturbations namely:
-Input perturbation (Where noise is added to input features)
-Objective perturbation (Where noise is added to model gradients)
-Prediction perturbation (Where noise is added to the model output)
