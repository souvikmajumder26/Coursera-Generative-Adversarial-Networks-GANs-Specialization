# Build-Basic-Generative-Adversarial-Networks-(GANs)
Course 1 of Coursera Specialization offered by DeepLearning.AI: Generative Adversarial Networks (GANs) Specialization

# Content of the Course -

<a href="#week-1">Week 1</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="#week-2">Week 2</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="#week-3">Week 3</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="#week-4">Week 4</a>
<p><b>Week 1, 2, 3 ---</b> all about prediciting the correct label(based on training - sarcasm, sentiment, etc.) against a particular testing text after being trained on a labeled data.</p>
<p><b>Week 4 ---</b> about predicting the most probable(calculated based on what words were present in what sequence in the training data) word that should be placed after a phrase and continuing to generate new words based on newly extended phrase(containing previous predicted words); thus generating new text(eg: story, poetry).</p>

## Week-1

Output function based outlook:

Discriminative Models - Classification models that predict the class (Y) based on features (X).

Generative Models - Predict features (Y) based on class (X) and random input noise (E).
> ![image](https://user-images.githubusercontent.com/86871718/173869967-34894139-d0f3-4cdb-a929-c0b358e31d09.png)
> ![image](https://user-images.githubusercontent.com/86871718/173870105-d764dc6d-1d6f-4ead-be01-1ec2837e8c5e.png)



### <a href="https://github.com/souvikmajumder26/DeepLearning-AI-TensorFlow-Developer-Professional-Certificate/blob/main/Course-3-Natural-Language-Processing-in-TensorFlow/c3_week1_lab_1_2_tokenizer_basics.ipynb">File: c3_week1_lab_1_2_tokenizer_basics.ipynb ---</a>
> Tokenizing natural language text into sequence of numbers/values/tokens per word so that the computer can work with them.

### <a href="https://github.com/souvikmajumder26/DeepLearning-AI-TensorFlow-Developer-Professional-Certificate/blob/main/Course-3-Natural-Language-Processing-in-TensorFlow/c3_week1_lab_3_sarcasm_detection.ipynb">File: c3_week1_lab_3_sarcasm_detection.ipynb ---</a>
> Kaggle Dataset: <a href="https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection">News Headlines Dataset for Sarcasm Detection</a>

> Only upto tokenizing the kaggle-Sarcasm-Detection dataset into sequence of numbers/tokens and creating the word_index->{key=word: value=token}.
