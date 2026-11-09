**Class note**:

- Fine-tune is a way to improve the model on accuracy, faster, and smaller than before.

- Model choosing focuses on:
  - What task we'll do

  - does our local machine and data can work with that model
  - model architecture

  - how it transfer the training to improve model

  - document and community support

- Model loader focus on the process of loading model into our local machine. Since the model has their own package which has tokenizer, model, etc. So, what we need to load into our machine and save the memory.

- Model loader has two way for loading: model-specific load and auto model load.
  - Model-specific load, we need to load the model with specific name and type.

  - Auto model loader, we just just automodel loader library and load the model by name.

- Process loader is used for selecting the model processor to combine with the model for working. this step focus on the support file of the model to work with its architecture.

- Quantization is the process to reduce the memory spending on the model execution. This reduce by define the bit of the weight of model.
