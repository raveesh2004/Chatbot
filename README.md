# Chatbot


## Data Analysis
- It is the process of systematically applying statistical and/or logical techniques such as cleaning, transforming, and modeling data to discover useful information for business decision-making. 

## Dataset used 
[https://github.com/raveesh2004/Chatbot/blob/main/intents1.json
](url)



## Important instructions
- **python version should be *latest***

## Technologies used :
### Language 
- *Python*- for programming and writing logic.
  
### Python libraries 
-   numpy,random,tensorflow,nltk,pickle,keras .
### Models 
- Machine Learning Models such as keras ,tensorflow and nltk.
## Working of the app :
> - This code appears to be a Python script for building a simple chatbot using TensorFlow and Keras libraries for natural language processing. Let me break down how it works:
> - *Importing Libraries*: The script starts by importing necessary libraries like json, numpy, random, tensorflow, nltk, and others. These libraries are used for tasks > - like data manipulation, machine learning, and natural language processing.
> - *Data Preprocessing*:
> - It loads intents from a JSON file named "intents.json". These intents likely contain patterns of user messages and corresponding responses.
> - It tokenizes the patterns using the NLTK library, removes unnecessary characters, and lemmatizes the words.
> - It prepares the training data by creating a bag of words representation for each pattern and associates it with the corresponding intent.
> - *Neural Network Model*:
> - It constructs a neural network model using Keras Sequential API.
> - The model consists of Dense layers with ReLU activation functions and dropout layers to prevent overfitting.
> - It compiles the model using the stochastic gradient descent optimizer (SGD) and categorical cross-entropy loss function.
> - *Training the Model*:
> - It trains the model using the prepared training data.
> - The training is done with 200 epochs and a batch size of 5.
> - *Saving the Model*: After training, it saves the trained model to a file named "chatbot_model.h5".
> - *Function Definitions*:
> - Several functions are defined for sending messages, cleaning up sentences, creating bags of words, predicting classes, and getting responses. These functions are > - essential for the chatbot's functionality.
> - *Main Loop*:
> - The script enters an infinite loop where it continuously waits for user input.
> - Upon receiving input, it predicts the intent of the message using the trained model and generates an appropriate response based on the predicted intent.
> - The loop continues until the user inputs "break".


### Adding functionality : features
> - **NumPy**- *It is  a Python package used for performing the various numerical computations and processing of the multidimensional and single-dimensional array elements.*
> - **Random**: *Facilitates random number generation, sampling, and probability distributions, crucial for various applications such as simulations, statistical analysis, and machine learning.*
> - **TensorFlow**: *Offers a comprehensive framework for building and training machine learning models, particularly deep neural networks, with flexibility, scalability, and extensive tooling support.*
> - **NLTK**: *Provides a suite of libraries and programs for natural language processing tasks, including tokenization, stemming, tagging, parsing, and semantic reasoning, aiding in text analysis and understanding.*
> - **Pickle**: *Allows serialization and deserialization of Python objects, enabling the saving and loading of data structures and models, vital for storing and transferring complex data across sessions or systems.*
> - **Keras**: *Simplifies the creation and experimentation of deep learning models by providing a high-level API with user-friendly interfaces and seamless integration with TensorFlow, enabling rapid prototyping and development.*





## Application of Chatbot 
> - Customer Support: Chatbots offer instant assistance, answering FAQs, troubleshooting issues, and guiding users through processes, enhancing customer satisfaction and reducing support costs effectively.
> - Sales and Marketing: Chatbots engage prospects, recommend products/services, provide personalized offers, and streamline the purchasing process, boosting conversion rates and improving overall marketing efficiency.
> - Information Retrieval: Chatbots retrieve and deliver relevant information on-demand, such as news updates, weather forecasts, or educational content, offering convenience and quick access to knowledge for users.
