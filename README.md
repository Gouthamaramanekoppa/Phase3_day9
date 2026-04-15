# Phase3_day9

Experiments Conducted
Model 1 — Custom CNN (From Scratch)
Architecture:

3 Conv Blocks (Conv → ReLU → MaxPool)
Fully Connected Classifier
Dropout for regularization

Purpose:
To evaluate how a network trained entirely on our dataset performs without pretrained knowledge.

Model 2 — Transfer Learning CNN (Fine-Tuned)
Architecture:

Pretrained base model
Unfrozen top layers
Custom classifier head

Purpose:
To leverage pretrained features and compare performance vs scratch model.

Results Comparison
Metric	           Custom CNN	Transfer Learning
Training Accuracy	    89%	          94%
Validation Accuracy	  85%	          91%
Training Time	       Faster	     Slightly slower
Overfitting	         Higher	         Lower


Key Observations
Transfer learning significantly improved validation accuracy.
Custom CNN showed faster training but overfitted more quickly.
Pretrained features helped generalization on unseen data.
Transfer learning chosen as best architecture for optimization stage.

This marks the completion of the architecture comparison milestone.
