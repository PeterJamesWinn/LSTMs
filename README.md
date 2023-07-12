# LSTMs
 RNN and LSTM models for generating text.

input.txt - tiny Shakespeare text for training.
generative_text_rnn.ipynb - Jupyter notebook  with RNN for text generation. More details below.
generative_text_lstm.ipynb - Jupyter notebook with LSTM for text generation. More details below.

Inspired by Andrej Karpathy's Youtube tutorial on language models.
Refactored his code from his ChatGPT tutorial have a text class
which has methods to process and encode/decode the text.
Initially replaced the tranformer with pytorch's RNN and then 
duplicated the code developed to wrap the RNN to use an LSTM instead. 
Used simple strings, ABABAB repeated and 
"ABCD EFGH IJKL MNOP QRSTU VWXYZ "*100 plus investigation of 
verbose output to ensure that the code is doing what I expect it to.
Finally:
using Tiny Shakespeare example data
wget https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt
which gives surprisingly good data generation for such a simple and 
minimally trained network. 

 
