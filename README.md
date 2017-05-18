# kaggle_cervical

This project is held within a biomedical project course at Stanford University. We are working on the Kaggle Challenge: "Intel &amp; MobileODT Cervical Cancer Screening"

Cervical cancer is the fourth most common cancer in women, with 528,000 new cases and 266,000 deaths worldwide in 2012. One of the most difficult aspects of cervical cancer screening and treatment is determining the appropriate therapy, as treatment methods depend heavily on the patient's physiological makeup. Women who are high risk for cervical cancer are often ineffectively screened in rural parts of the world due to the difficulty of assessing cervix type, as defined by the location of the transformation zone. Therefore, almost nine out of ten (87%) cervical cancer deaths occur in the less developed regions. A novel, mobile quality assurance workflow from MobileOBT has opened up the possibility of better treatment decisions in rural settings but they lack the automated computing capabilities to make real-time determinations about a patient’s treatment eligibility based on cervix type. Recent breakthroughs in cloud- based computing and deep-learning architectures for image segmentation, recognition, and analysis have made it possible to remotely and automatically perform these analyses. In this project we aim to:

1. Develop a preprocessing algorithm for cervigrams to remove image artifacts, such as the speculum and specular reflection, and extract the region of interest

2. Build a Deep Learning Model (ConvNet, ResNet) to recognize one of three cervix types from preprocessed cervigrams

3. Train the model and tune the hyperparameters (number of layers, number of neurons, etc..)

4. Evaluate our model performance using the multiclass logarithmic loss function and repeat our tuning procedure based on the results

We propose that our system will provide the ability for real-time assessment of a patient’s cervix type, allowing for optimized treatment plans and improved patient outcomes in rural settings.
