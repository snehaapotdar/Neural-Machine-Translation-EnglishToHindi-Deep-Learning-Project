# Neural-Machine-Translation-EnglishToHindi-Deep-Learning-Project
Performed English to Hindi language neural machine translation using LSTM model to obtain a BLEU score of 0.65 with the TensorFlow library/Keras API.

# Introduction:
This project aims to evaluate different approaches to neural machine translation, incorporating deep learning techniques such as sequence to sequence models, LSTM cells and attention models. As part of this project we made an in-depth analysis of each approach and an error analysis of translations made by the model. The accuracy metrics used are BLEU scores. The models build perform English to Hindi translation.

# Conclusion:

After running variations in models and hyperparameters we observed that the best balance of training speed and performance was possible (BLEU score) through ADAM as the optimizer as it accommodates not just the learning rates, momentums but also prioritizes current set of rates over the previous ones so that the performances are more influenced in the recent context. Hence this would likely be our go to model for larger sample sizes.
Even though Deeper capacity Word to Word LSTM models present great results, Attention model though computationally expensive can give great performance over larger epochs. This can be done using “Transformer model” which uses only attention and gets rid of all Convolutional and Recurrent layers making it highly “parallelizable” and computationally efficient.
