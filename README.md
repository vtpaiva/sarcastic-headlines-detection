# sarcastic-speech-detection

This project focuses on using **Natural Language Processing (NLP)** techniques to predict whether a headline from a news website contains sarcasm. The task involves building a predictive model using two distinct approaches for data modeling.

---

## Installing requirements

In order to be able to run the *Jupyter* notebooks to enhance the code **reproducibility**, it is necessary to install the requirements.

```bash
pip install -r requirements.txt
```

## Data Modeling Approaches

1. **Word Frequency and Word Count Analysis**
   - Utilize the difference in word frequency between the target classes.
   - Incorporate the word count of each headline as a feature for prediction.

2. **Neural Network with Word Embeddings**
   - Employ a word embedding method with `Keras` to extract patterns in the data.
   - Leverage neural network architectures to capture semantic relationships between words.

---

## Objectives

- Develop models capable of accurately identifying sarcasm in headlines.
- Compare and evaluate the performance of traditional feature engineering techniques against deep learning methods.

![Word cloud](assets/output_40_1.png)

---

## Conclusion

This project highlights the versatility of NLP techniques by contrasting traditional and deep learning-based approaches for sarcasm detection. The insights gained from this work can be applied to broader sentiment analysis and language understanding tasks.

---

### References

https://thecleverprogrammer.com/2021/08/24/sarcasm-detection-with-machine-learning/

🤖 <a href="https://scikit-learn.org/1.5/user_guide.html">Scikit-learn Documentation</a>

🐼 <a href="https://pandas.pydata.org/docs/user_guide/index.html">Pandas Documentation</a>

🌊 <a href="https://seaborn.pydata.org/tutorial.html">Seaborn Documentation</a>

🖼️ <a href="https://matplotlib.org/stable/users/index">Matplotlib Documentation</a>