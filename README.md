# Domain Adaptation for OCR Models
This project aims to improve the performance of Optical Character Recognition (OCR) systems on handwritten text, particularly when faced with unfamiliar handwriting styles. While OCR models excel at recognizing printed text, they often struggle with the variability of handwriting, especially when labeled data is scarce. 

To address these challenges, we leveraged Spell Checking Algorithms like PySpellChecker, SymSpell Algorithm and different decoding techniques like Greedy and Beam Search to enhance model adaptability. 

The primary model is a Convolutional Recurrent Neural Network (CRNN) trained on the IAM Handwriting Dataset. 
The test dataset consists of our own handwritten word images.
The predicted text for the test images is further refined using the SymSpell algorithm to suggest corrections for spelling errors. 
