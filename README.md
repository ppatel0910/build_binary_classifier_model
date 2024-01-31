## Background
### You work as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.
### The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

## Results
### The initial model's accuracy was 72.82%. In my first optimization attempt, I increase the number of epochs from 50 to 200. This had a very minimal effect on its accuracy, resulting in a mere 0.03% increase. The second alternative model included an additional hidden layer, and used the original epochs of 50. This alteration to the model had a greater positive effect, it produced an accuracy of 72.98%. This model was the most successful of the three. These results can be seen below, as well as in the jupter notebook. 

![accuracy_results_of_neural_network_models](https://github.com/ppatel0910/build_binary_classifier_model/blob/main/results_visualization/neural_network_results.png)