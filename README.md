# 🎮 IMDb Review Sentiment Classification 🎭  

## 📌 Project Overview  
This project focuses on classifying IMDb movie reviews as **positive** or **negative** using **deep learning** techniques. The primary goal is to develop an efficient sentiment analysis model that can accurately predict the sentiment of a given review.  

## 🚀 Actions Performed  
1. **Data Preprocessing**  
   - Loaded IMDb dataset 📂  
   - Performed text cleaning (removal of special characters, stopwords, and lowercasing) ✨  
   - Tokenized text and converted it into sequences using **TensorFlow's Tokenizer** 🔢  
   - Applied **padding** to ensure uniform input size  

2. **Word Embeddings**  
   - Used **GloVe (Global Vectors for Word Representation) - 100D** 🌍  
   - Loaded pre-trained word embeddings to improve text understanding  

3. **Model Training & Evaluation**  
   - Implemented a **Bidirectional LSTM (Long Short-Term Memory)** model for sentiment classification 📊  
   - Compiled the model with **Adam optimizer** and **binary cross-entropy loss**  
   - Trained the model on the IMDb dataset and evaluated its accuracy 🎯  
   - Achieved high accuracy on test data  

4. **Prediction on Unseen Data**  
   - Loaded new IMDb reviews and applied the trained model  
   - Generated sentiment predictions and stored results in a CSV file 📝  

## 🤖 Models Used  
✅ **Simple Neural Networks** (SNN) 
✅ **Convolution Neural Networks** (CNN)   
✅ **Recurrent Neural Networks Long Short-Term Memory** (LSTM)  
✅ **GloVe Word Embeddings** - Pre-trained embeddings to improve model accuracy  

## 📌 Plan of Action  
📌 **Step 1**: Load & preprocess the dataset  
📌 **Step 2**: Implement text tokenization and padding  
📌 **Step 3**: Integrate pre-trained word embeddings (GloVe)  
📌 **Step 4**: Build and train the BiLSTM model  
📌 **Step 5**: Evaluate the model's performance  
📌 **Step 6**: Test the model on unseen data  

## 🔥 How to Use  
1. Clone the repository  
2. Install dependencies   
3. Run the Jupyter Notebook or Python script to train and test the model  
4. Use the trained model to predict sentiment on new IMDb reviews  

## 💡 Future Improvements  
- Implement **attention mechanisms** for better sentiment classification  
- Train on a **larger dataset** for improved accuracy  
- Optimize model parameters for **faster training**  

Happy Coding! 🚀
