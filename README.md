# RNN_Project

This project demonstrates building a language model using an LSTM (Long Short-Term Memory) neural network architecture to generate text based on Shakespeare's writings. LSTM is a type of recurrent neural network (RNN) particularly effective for tasks involving non-sequential data like natural language processing and time series analysis. Implemented using TensorFlow and Keras libraries, the model is constructed, trained, and evaluated.

The model serves as a text generator, starting with a given initial sentence to produce new text. During training, a segment of Shakespeare's texts is used to teach the model. Initially, the text data is processed, a character-level dictionary is created, and each character is indexed to a corresponding number. Subsequently, an LSTM layer is added to enable the model to learn context, followed by an output layer to finalize predictions.

Results are showcased through generated text examples at different temperature values. Lower temperatures (0.2-0.4) yield more consistent and meaningful text, while higher temperatures (0.6-1.0) produce more creative and varied outputs. This demonstrates how the temperature parameter influences the model's text generation process by balancing predictability and diversity.

## Lower temperature
![image](https://github.com/pinarkurtunluoglu/RNN_Project/assets/77545059/ac65fe0f-15f2-4102-81c7-63282f943b1c)

## Higher temperature
![image](https://github.com/pinarkurtunluoglu/RNN_Project/assets/77545059/d07d85aa-ae7b-4868-aca1-81cbffb45b0d)

The project aims to illustrate the workings of language models and showcase the application of deep learning techniques such as LSTM in handling complex data structures. Such models find broad utility in natural language processing tasks and applications like virtual authorship.

