# chatbot
Some companies that provides AI solutions, faces a challenge with some users
who are experiencing difficulties in utilizing specific functionalities within their solutions. In
order to address this challenge, this project aims to develop a FAQ chatbot for Intertech.
The chatbot will be used to answer frequently asked questions about one of Intertech’s
solutions. This chatbot will help increase users’ satisfaction since it is providing valuable
assistance in utilizing the AI solution effectively. To achieve this, I opted for a retrieval-based
model to build the chatbot. The development process involved several key steps including
data augmentation, data cleaning, building the model by integrating a pre-trained model as
SBERT, and finally the evaluation. The functioning mechanism of the chatbot is encoding
the user question using SBERT and comparing it to the encoded questions in the knowledge
base then retrieving the corresponding answer of the most similar question. The evaluation
results lie within 91% showing that the model is performing well in terms of answering most
of the FAQ. One of this chatbot’s limitations is that its answers may not always sound natural
or human-like. To address this limitation, one possible solution is to incorporate a natural
language generation (NLG) component into the chatbot. By leveraging NLG techniques, the
chatbot can generate more coherent and human-like responses, enhancing the overall user
experience.
