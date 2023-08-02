After compiling the code and the results, this study produced a least squares regression line of ŷ=914.90212, x-
1291.32081. The y-value, in this case, is the byte size of the intents.json file; the x-value is the runtime in seconds.

To confirm this data, the study tried the following numerical values in the training. The program compiled three
different byte sizes (7547 bytes, 13248 bytes, and 28496 bytes) and got three different runtimes (9.75s, 15.77s, and
32.59s, respectively). Repeated trials with these byte sizes resulted in the same runtimes since the program is a
deterministic algorithm.
Deterministic algorithms produce the same result given the same input and conditions, providing a consistent
runtime [8]. The algorithm follows a fixed set of steps with no elements of probability or randomness, allowing for
the same execution time. In a more nuanced sense, the process of training the chatbot using TFLearn and Tensor
Flow followed a fixed set of steps.
The model training process involved processing the input data, creating/configuring the neural network architecture,
specifying the number of epochs (1000) and batch size of eight, and fitting the model to the training data. These
deterministic steps were combined with the bag-of-words representation, which simply converted user input into
numerical vectors, which is another deterministic process. It tokenized the input sentence, applied stemming (using
Lancaster Stemming in NLTK), and compared the words to a predefined vocabulary, ultimately producing the same
results given the same input and conditions. In the Table 1 and Figure 1, the numbers are completely consistent
for any trial.
