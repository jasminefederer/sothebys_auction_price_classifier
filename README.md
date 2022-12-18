Applying the Naive Bayes Classifier model to a dataset of art house Sotheby's auction prices, based on the art movement and gender of the artist with the aim to see how these variables could help predict the sale value of the artwork

Another variable which would be interesting to explore would be the impact of race/nationality on the overall price of the artwork - in particular when this is combined with gender



Using the matplotlib python library extension could help to visualise such patterns which exist within the Sotheby's auction house and the art market, provoking interesting thought as to whether consumers are willing to pay a higher price for an artwork of the same period/movement when it is created by a white, western or male artist



<u>Sotheby's official website:  https://www.sothebys.com/en/</u>



Gender was not an original aspect of the dataset so I employed the python gender-guesser library to estimate this



Original source of dataset: https://www.kaggle.com/datasets/flkuhm/art-price-dataset/discussion/372366

*The provenance of this dataset is blurry since this is webscraped by an individual who has posted it on an open-source website... I have been in touch to request further details of the parameters such as the collections/regions and dates which were included in extracting this data which would greatly improve our context for enquiry



This classifier is a WIP and still has a long way to go in terms of outputting any reliable patterns which can be confidently reflected within the data

Upon reflection, this may not have been the most suitable dataset to work with for the ourpose of generating a Naive Bayes Classifier, but was an interesting learning experience and the code can always be applied to generate classifiers from alternative datasets in the future
