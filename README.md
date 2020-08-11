# bible-text-generator

#### Simple RNN model trained on the King James Bible to generate text.

#### Most code adapted from this article.
[Generating Eminem Lyrics using Neural Networks](https://towardsdatascience.com/generating-eminem-lyrics-using-neural-networks-96e7f9c45e8a)

#### Try It Yourself
To run the code in Google Colab, open the notebook bible_generator_colab.ipynb

The data is small enough to host the text file on GitHub, so the Google Colab notebook pulls
the text data and saves to the /tmp/ directory.  The all of the data can be processed and
the model trained.  The current iteration, even with GPU acceleration, still takes 30 minutes
to train.
