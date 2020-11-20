# Corona_Tweet_Sentiment
Sentiment Classification of Corona Tweets using sequence classification

## Link to Kaggle page

Link to Kaggle competition Page:
###  [https://www.kaggle.com/datatattle/covid-19-nlp-text-classification]( https://www.kaggle.com/datatattle/covid-19-nlp-text-classification )

* Packages used
	* nltk
	* scikit-learn
	* tensorflow
	* scipy
	* matplotlib
	* seaborn
	* tensorflow addons
  
* The project also evaluates the model performance by plotting class-wise ROCs
* The model was not evaluated for latency or deployed on cloud platforms
* Tensorflow addons have a lot of new features like activation functions -- mish (used in this notebook) by Diganta Mishra, used in YOLOv4, swish and hard swish, they perform better than the old activation functions like RELU
* Tensorflow addons also has the Bahandau attention

### Conclusion

 * The model is able to distinguish between extremely positive, extremely negative and neutral sentiments with ease
 * May be we should merge the positives with extremely positives and negatives with extremely negative to achieve better performance on the dataset
 * This is not a set of good performing models, but a cavalierly put forth model. In actual world, we would have to follow a more structured methodology and refine the ask to provide a better and more directed solution. A huge part of this is manipulating and cleaning the data and inferring from various kinds of models about what can be fixed with the existing dataset and what can be expected as inputs.

## For more information about me

Follow me on Instagram:
###  [https://www.instagram.com/ovishake2020/?hl=en]( https://www.instagram.com/ovishake2020/?hl=en )
###  [https://ovishake.com] ( https://ovishake.com )
