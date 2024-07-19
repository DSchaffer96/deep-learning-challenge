# deep-learning-challenge
This deep learning model is trained to help Alphabet Soup find potentially successful organizations to work with. The model is trained by analyzing a dataset of organizations that Alphabet Soup has previously worked with and predicts success based on those organizations' metadata.
Data Preprocessing:
- The target variable is "IS_SUCCESSFUL"
- The features variables are:
  - "APPLICATION_TYPE"
  - "AFFILIATION"
  - "CLASSIFICATION"
  - "USE_CASE"
  - "ORGANIZATION"
  - "STATUS"
  - "INCOME_AMT"
  - "SPECIAL_CONSIDERATIONS"
  - "ASK_AMT"
  - "IS_SUCCESSFUL"
- The variables "EIN" and "NAME" were removed


- 3 layers, including the output later, were used in the model. The first layer used 80 neurons and the second layer used 30 neurons. 1 Activation function was used.
  - ![model_layers](https://github.com/user-attachments/assets/b59b056a-e011-455e-987f-6aa7a2ecb697)
- The accuracy score for this model was 0.9999, so the model is a success.
  - ![results](https://github.com/user-attachments/assets/7cc83a16-7fca-46fe-98e2-7d853a40d5bb)

Since this learning model is 99.99% accurate, I would recommend using this model over other ones.


