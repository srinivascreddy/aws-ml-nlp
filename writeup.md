{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# NLP Text classification\n",
    " Create a machine learning model to identify negative review and identify the reason for the negativity. Identifying the negative review will give an opportunity to react to customer expectation and determine if the product needs to be removed from the product offers.  \n",
    " \n",
    "# Datasets\n",
    "- Reviews from Amazon review site (Polarity). \n",
    " https://course.fast.ai/datasets\n",
    " \n",
    "    - Review Text\n",
    "    - Review Score.  Score 1 and 2 is nagative class. Score 4 and 5 is positive class. We can ignore score 3. \n",
    "\n",
    "\n",
    "# Modeling Strategy\n",
    "-  Blazing Text Supervised Classification\n",
    "-  BlazingText's Word2Vec Unsupervised Model to generate word embeddings\n",
    "-  Linear Learner for 1:1 model interpretation, using word embeddings as features\n",
    "-  Clustering negative reviews to extract topics and key words\n",
    " \n",
    "\n",
    "# End Goal\n",
    "Once the model is ready, we can deploy it and automatically tag the reviews based on the text."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "conda_python3",
   "language": "python",
   "name": "conda_python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
