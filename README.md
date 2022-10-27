# blending_stacking
useful scripts for blending/stacking ensembles


- Stacking steps:
  1. Collect Data
  2. Divide into folds, train and validation.
  3. Train a bunch of models
  4. Models predict on validation folds.
  5. Fold predictions will be your **new training data.**
  6. Stack them column wise and keep the ids
  7. Train models on these predictions as features.
  8. Test predictions will be the "new validation set" (use same folds)
  9. Predictions now will be the Final OOF predictions
  
  
  
  
  ![image](https://user-images.githubusercontent.com/67332395/198299779-a856f281-95b8-44a9-ae5b-29fd2372a8b2.png)

  ![image](https://user-images.githubusercontent.com/67332395/198300388-da1e139d-123d-4182-b1eb-f70942f04378.png)

source: https://www.youtube.com/watch?v=TuIgtitqJho
