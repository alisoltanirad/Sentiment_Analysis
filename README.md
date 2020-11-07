# Sentiment Analysis On Small Datasets
It's an open source project under MIT licence by Ali Soltani Rad.  <br/><br/>Sentiment analysis on small datasets using <b>fine-tuning</b> technique and <b>LSTM neural network</b> model.  <br/><br/>
Since the number of data records in an small dataset is not enough for a relative accurate result, I used Keras IMDB large dataset to train an LSTM neural network, then save the weights of the layers in neural network. On the next step I used that weights to train another LSTM neural network this time for small dataset with one additional layer to fit better to the small dataset. We can obtain better results using this technique.  <br/><br/>
The procedure is specially useful for languages which not have enough data for a proper modeling. In this project I used Farsi (Persian) comments from "digikala.com" translated to English using "google translate". You can access datasets here: [datasets](https://github.com/alisoltanirad/Sentiment-Analysis-Farsi-Dataset)  <br/><br/>
* On the code you can change number of batch size and epochs of neural networks according to the computaion power of your system.  <br/><br/>
