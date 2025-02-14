# A small machine learning project for university, developed by Sviston and FireBlastV.

The project includes training and using a CNN neural network that classifies screenshots from Minecraft based on player activity into six classes: walking, swimming, fighting, building, mining and archery.

Due to the small dataset, overfitting occurred, making the model less effective when working with real images compared to those from the dataset.

Although data augmentation is still shown in the Jupyter Notebook, it is not used for training the model because it negatively impacted the stability of the validation score. Additionally, such augmented screenshots are unlikely to appear in real-world scenarios.
