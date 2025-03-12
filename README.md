# Youtube_Profanity_Detection

## Project Overview

This project implements a YouTube Profanity Detection system designed to automatically classify and detect profane or inappropriate comments from YouTube videos. It leverages deep learning and natural language processing techniques to provide accurate, real-time moderation of user-generated content.

## Technical Approach

- **Data Collection:** Utilized the YouTube Data API (v3) to fetch comments and replies from specified YouTube videos, enabling real-time analysis of user interactions.
- **Data Preprocessing:** Employed TensorFlow's `TextVectorization` layer to convert raw text comments into numerical representations suitable for neural network processing.
- **Model Development:** Built a sequential deep learning model using TensorFlow and Keras, specifically employing Long Short-Term Memory (LSTM) layers, which are effective in capturing sequential dependencies in textual data.
- **Model Training:** Trained the LSTM model on labeled datasets to recognize patterns indicative of profanity, optimizing accuracy through iterative training and validation cycles.
- **User Interface:** Integrated Gradio to provide an intuitive web-based interface, allowing users to input comments manually and receive immediate predictions regarding profanity.
- **Visualization and Analysis:** Conducted exploratory data analysis and visualized prediction results using Matplotlib, providing insights into the distribution of profane comments across analyzed videos.

## Technologies Used

- **Python** (TensorFlow, Keras, Pandas, NumPy)
- **YouTube Data API (v3)** for comment retrieval
- **Gradio** for interactive user interface deployment
- **Matplotlib** for visualization

This system offers an efficient solution for content moderation on YouTube by automatically identifying inappropriate language, helping creators maintain community standards effectively.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/21906101/526541e4-7a98-4a2f-95df-33a52792a418/Profanity_Youtube.ipynb
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/21906101/526541e4-7a98-4a2f-95df-33a52792a418/Profanity_Youtube.ipynb

---
Answer from Perplexity: pplx.ai/share
