# Fine-Tuning-Amazon-Titan-Image-Model-V2

## Description
This project is aimed at fine-tuning image models on Amazon Bedrock with the use of the Bedrock API and Boto 3 SDK. The Dataset used in this projeect is from Huggingface.co and is of tens of thousands of Pokemon Cards. The Base
Model being used is the Amazon Titan Image Generator V2 Model.

## Table of Contents
- Within the Jupyter notebook labeled Fine-Tuning.ipynb there is code that was used to do the following below:
1. Import the dataset
2. Prepare the data for the Bedrock API
3. Create a Model Customization Job
4. Provision Throughput to the Custom Model
5. Invoke the model to generate some examples
6. Clean up resources (Delete the Provisoned Throughput)

# Important
- Due to content filters, some prompts may be limited and blocked due to the AWS Responsibility AI policy.
- If you use a different dataset, the code may need to be altered to work as intended.
- You will need to incur costs associated with services when trying to replicate this sample.
- The Role ARN's and model names will differ based on your account resources.
