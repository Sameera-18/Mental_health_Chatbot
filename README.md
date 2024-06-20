
# Mental-Health Chatbot

The Mental Health Chatbot is designed to provide supportive responses to mental health-related inquiries. It leverages a pre-trained language model, fine-tuned on a custom dataset, to enhance its ability to understand and respond to such questions effectively.This project aims to create a chatbot that provides mental health support by answering questions and engaging in conversations related to mental well-being.


## Dataset
The dataset was created from scratch and includes around 210 rows with two columns: questions and answers. These rows represent sample questions and answers related to mental health.

## Limitations
While the dataset provides a foundation for the chatbot, it has several limitations:

 1. The dataset is relatively small, which may affect the chatbot's ability to generalize to a wide range of questions.

 2. Responses may not cover all possible mental health topics comprehensively.

 3. The dataset's quality is dependent on the accuracy and relevance of the manually curated questions and answers.

## Fine-Tuning
The model was fine-tuned using our custom dataset to tailor its responses specifically to mental health-related queries. Fine-tuning involved training the model on our dataset to improve its performance on the given task.

## Quantization
To optimize the model for deployment, we quantized it. This process reduces the model size and improves inference speed, making it more efficient for real-time use.