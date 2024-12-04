# Domain Adaptation for OCR Models
This project aims to improve the performance of Optical Character Recognition (OCR) systems on handwritten text, particularly when faced with unfamiliar handwriting styles. While OCR models excel at recognizing printed text, they often struggle with the variability of handwriting, especially when labeled data is scarce. 

The primary model is a Convolutional Recurrent Neural Network (CRNN) trained on the IAM Handwriting Dataset. 
The test dataset consists of handwritten word images of different handwriting styles from different individuals.

The model performs well on the training dataset but to improve the Word Error Rate on our Target Dataset, we leveraged Spell Checking Algorithms like PySpellChecker, SymSpell Algorithm and different decoding techniques like Greedy and Beam Search to enhance model adaptability. 
