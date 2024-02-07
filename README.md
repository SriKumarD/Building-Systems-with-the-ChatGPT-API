# ChatGPT API System Building Course Notes

## Overview

This course dives into how to construct sophisticated applications using the ChatGPT API, with an emphasis on creating systems that are more complex than a simple prompt-response setup. It's geared towards crafting applications that interact with users in a nuanced and intelligent manner, using Large Language Models (LLMs) like ChatGPT.

## Core Concepts

### Evaluating User Input

- **Initial Check**: The first step involves scrutinizing the user's input to ensure it's free from any harmful or inappropriate content. This step is crucial for maintaining a positive and safe interaction environment.

### Understanding the Query

- **Query Classification**: Once the input is deemed safe, the system analyzes the essence of the query. This could range from identifying whether the request is for information, a complaint, or another type of inquiry.
- **Decision Making**: Based on the query's classification, the system decides the next steps, such as fetching data or crafting a response directly.

### Generating Responses

- **Data Retrieval**: For queries needing specific information (like product details), the system retrieves relevant data.
- **Crafting Replies**: Using the retrieved data, the system then employs the LLM to generate informative and helpful responses tailored to the user's inquiry.

### Quality Assurance of Responses

- **Accuracy and Appropriateness**: Before a response is sent to the user, it's checked for accuracy and to ensure it's appropriate. This step is vital to avoid misinformation or potentially offensive content.

## Building Multi-Step Systems

A significant theme of this course is the realization that user-friendly applications often require several behind-the-scenes steps to process inputs and generate outputs. These multi-step processes are designed to refine the user's input into a response that is both relevant and helpful.

## Continuous Improvement

Developing applications with LLMs is presented not as a one-off task but as an ongoing journey of improvement. The course emphasizes the importance of:

- **Iterative Development**: Regular updates and refinements based on user feedback and performance data.
- **Best Practices**: Adopting strategies that have been proven effective in enhancing system performance and user satisfaction over time.

## Practical Application

The course centers around building an end-to-end customer service assistant as a practical example. This assistant showcases how to chain multiple LLM calls and integrate external data sources to handle complex user queries efficiently and effectively.


## Training LLMs

<div align="center">
<img src="https://github.com/SriKumarD/Building-Systems-with-the-ChatGPT-API/blob/main/Supervised_learning.png" width="600" height="500" alt="Iterative Promts image">
</div>

- **Supervised Learning**: It's the main method for training LLMs. The model learns from labeled data, where each piece of data is tagged with the correct output.
- **Example**: If teaching a model to understand restaurant review sentiments, reviews are labeled as positive or negative based on their content.

## How LLMs Generate Text
<div align="center">
<img src="https://github.com/SriKumarD/Building-Systems-with-the-ChatGPT-API/blob/main/Largr_language_model.png" width="600" height="500" alt="Iterative Promts image">
</div>

- Given a prompt (e.g., "I love eating"), LLMs predict likely completions (e.g., "bagels with cream cheese").
- This ability comes from training on a massive amount of text data, learning to predict the next word in a sequence.

## Types of LLMs

<div align="center">
<img src="https://github.com/SriKumarD/Building-Systems-with-the-ChatGPT-API/blob/main/Type%20of%20LLMS.png" width="600" height="500" alt="Iterative Promts image">
</div>

1. **Base LLMs**: Predict the next word in a sequence without specific instructions, good for generating narrative content.
2. **Instruction Tuned LLMs**: Trained further to follow explicit instructions, making them more accurate for specific queries or tasks.

## Training Process

<div align="center">
<img src="https://github.com/SriKumarD/Building-Systems-with-the-ChatGPT-API/blob/main/Base_LLM_Instuction_LLM.png" width="600" height="500" alt="Iterative Promts image">
</div>

- **Base LLM Training**: Involves training on hundreds of billions of words, a process that can take months on powerful computers.
- **Instruction Tuning**: After training a Base LLM, it's fine-tuned with data where outputs follow specific instructions. This process is quicker, taking maybe days with less data and computational resources.

## Enhancing LLM Output Quality

- **Reinforcement Learning from Human Feedback (RLHF)**: After fine-tuning, LLMs are improved by adjusting them based on human ratings of the outputs, focusing on criteria like helpfulness and accuracy.

## Practical Takeaways

- **Instruction Tuned LLMs** are more suitable for tasks requiring precise answers, like "What is the capital of France?" where the expected answer is "Paris."
- The transition from a Base LLM to an Instruction Tuned LLM involves not just initial training but also fine-tuning and reinforcement learning to refine the model's responses.


