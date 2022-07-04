## What is a neural network?
A neural network is a method in artificial intelligence that teaches computers to process data in a way that is inspired by the human brain. It is a type of machine learning process, called deep learning, that uses interconnected nodes or neurons in a layered structure that resembles the human brain. It creates an adaptive system that computers use to learn from their mistakes and improve continuously. Thus, artificial neural networks attempt to solve complicated problems, like summarizing documents or recognizing faces, with greater accuracy.


# An Introduction to Deep Learning
### Why are neural networks important?
Neural networks can help computers make intelligent decisions with limited human assistance. This is because they can learn and model the relationships between input and output data that are nonlinear and complex. For instance, they can do the following tasks.
#### Make generalizations and inferences
Neural networks can comprehend unstructured data and make general observations without explicit training. For instance, they can recognize that two different input sentences have a similar meaning:

* Can you tell me how to make the payment?
* How do I transfer money?
A neural network would know that both sentences mean the same thing. Or it would be able to broadly recognize that Baxter Road is a place, but Baxter Smith is a person’s name.

#### Reveal hidden relationships and patterns
Neural networks can analyze raw data more deeply and reveal new insights for which they might not have been trained. For example, consider a pattern recognition neural network that analyses consumer purchases. By comparing the buying patterns of numerous users, the neural network can suggest new items that might interest a specific consumer.
#### Create autonomous, self-learning systems
Neural networks can learn and improve over time based on user behavior. For example, consider a neural network that automatically corrects or suggests words by analyzing your typing behavior. Let us assume that the model was trained in the English language and can spell-check English words. However, if you frequently type non-English words, like danke, the neural network can automatically learn and correct these words too.
#### Learn and model highly volatile data
Some datasets, such as loan repayment amounts in a bank, can have large variations. Neural networks can model such data as well. For example, they can analyze financial transactions and flag some of them for fraud detection. They can also process complex data that holds the key to difficult biological problems like protein folding, DNA analysis, and more.
### What are neural networks used for?
Neural networks have several use cases across many industries, such as the following:

* Medical diagnosis by medical image classification
* Targeted marketing by social network filtering and behavioral data analysis
* Financial predictions by processing historical data of financial instruments
* Electrical load and energy demand forecasting
* Process and quality control
* Chemical compound identification

We give four of the important applications of neural networks below.

#### Computer vision
Computer vision is the ability of computers to extract information and insights from images and videos. With neural networks, computers can distinguish and recognize images similar to humans. Computer vision has several applications, such as the following:

* Visual recognition in self-driving cars so they can recognize road signs and other road users
* Content moderation to automatically remove unsafe or inappropriate content from image and video archives
* Facial recognition to identify faces and recognize attributes like open eyes, glasses, and facial hair
* Image labeling to identify brand logos, clothing, safety gear, and other image details
#### Speech recognition
Neural networks can analyze human speech despite varying speech patterns, pitch, tone, language, and accent. Virtual assistants like Amazon Alexa and automatic transcription software use speech recognition to do tasks like these:

* Assist call center agents and automatically classify calls
* Convert clinical conversations into documentation in real time
* Accurately subtitle videos and meeting recordings for wider content reach
#### Natural language processing
Natural language processing (NLP) is the ability to process natural, human-created text. Neural networks help computers gather insights and meaning from text data and documents. NLP has several use cases, including in these functions:

* Automated virtual agents and chatbots
* Automatic organization and classification of written data
* Business intelligence analysis of long-form documents like emails and forms
* Indexing of key phrases that indicate sentiment, like positive and negative comments on social media
* Document summarization and article generation for a given topic
#### Recommendation engines
Neural networks can track user activity to develop personalized recommendations. They can also analyze all user behavior and discover new products or services that interest a specific user. For example, Curalate, a Philadelphia-based startup, helps brands convert social media posts into sales. Brands use Curalate’s intelligent product tagging (IPT) service to automate the collection and curation of user-generated social content. IPT uses neural networks to automatically find and recommend products relevant to the user’s social media activity. Consumers don't have to hunt through online catalogs to find a specific product from a social media image. Instead, they can use Curalate’s auto product tagging to purchase the product with ease.

## How do neural networks work?
The human brain is the inspiration behind neural network architecture. Human brain cells, called neurons, form a complex, highly interconnected network and send electrical signals to each other to help humans process information. Similarly, an artificial neural network is made of artificial neurons that work together to solve a problem. Artificial neurons are software modules, called nodes, and artificial neural networks are software programs or algorithms that, at their core, use computing systems to solve mathematical calculations.
### Simple neural network architecture:
A basic neural network has interconnected artificial neurons in three layers:
### Input Layer
Information from the outside world enters the artificial neural network from the input layer. Input nodes process the data, analyze or categorize it, and pass it on to the next layer.
### Hidden Layer
Hidden layers take their input from the input layer or other hidden layers. Artificial neural networks can have a large number of hidden layers. Each hidden layer analyzes the output from the previous layer, processes it further, and passes it on to the next layer.
### Output Layer
The output layer gives the final result of all the data processing by the artificial neural network. It can have single or multiple nodes. For instance, if we have a binary (yes/no) classification problem, the output layer will have one output node, which will give the result as 1 or 0. However, if we have a multi-class classification problem, the output layer might consist of more than one output node.
### Deep neural network architecture
Deep neural networks, or deep learning networks, have several hidden layers with millions of artificial neurons linked together. A number, called weight, represents the connections between one node and another. The weight is a positive number if one node excites another, or negative if one node suppresses the other. Nodes with higher weight values have more influence on the other nodes.
Theoretically, deep neural networks can map any input type to any output type. However, they also need much more training as compared to other machine learning methods. They need millions of examples of training data rather than perhaps the hundreds or thousands that a simpler network might need.

## What are the types of neural networks?
Artificial neural networks can be categorized by how the data flows from the input node to the output node. Below are some examples:
### Feedforward neural networks
Feedforward neural networks process data in one direction, from the input node to the output node. Every node in one layer is connected to every node in the next layer. A feedforward network uses a feedback process to improve predictions over time.
### Backpropagation algorithm
Artificial neural networks learn continuously by using corrective feedback loops to improve their predictive analytics. In simple terms, you can think of the data flowing from the input node to the output node through many different paths in the neural network. Only one path is the correct one that maps the input node to the correct output node. To find this path, the neural network uses a feedback loop, which works as follows:

1. Each node makes a guess about the next node in the path.
2. It checks if the guess was correct. Nodes assign higher weight values to paths that lead to more correct guesses and lower weight values to node paths that lead to incorrect guesses.
3. For the next data point, the nodes make a new prediction using the higher weight paths and then repeat Step 1.
 
### [Convolutional neural networks](https://www.simplilearn.com/tutorials/deep-learning-tutorial/convolutional-neural-network)
The hidden layers in convolutional neural networks perform specific mathematical functions, like summarizing or filtering, called convolutions. They are very useful for image classification because they can extract relevant features from images that are useful for image recognition and classification. The new form is easier to process without losing features that are critical for making a good prediction. Each hidden layer extracts and processes different image features, like edges, color, and depth.

## How to train neural networks?
Neural network training is the process of teaching a neural network to perform a task. Neural networks learn by initially processing several large sets of labeled or unlabeled data. By using these examples, they can then process unknown inputs more accurately.
### [Supervised learning](https://www.javatpoint.com/supervised-machine-learning)
In supervised learning, data scientists give artificial neural networks labeled datasets that provide the right answer in advance. For example, a deep learning network training in facial recognition initially processes hundreds of thousands of images of human faces, with various terms related to ethnic origin, country, or emotion describing each image.
The neural network slowly builds knowledge from these datasets, which provide the right answer in advance. After the network has been trained, it starts making guesses about the ethnic origin or emotion of a new image of a human face that it has never processed before.

## What is deep learning in the context of neural networks?
Artificial intelligence is the field of computer science that researches methods of giving machines the ability to perform tasks that require human intelligence. Machine learning is an artificial intelligence technique that gives computers access to very large datasets and teaches them to learn from this data. Machine learning software finds patterns in existing data and applies those patterns to new data to make intelligent decisions. Deep learning is a subset of machine learning that uses deep learning networks to process data.

### Machine learning vs. deep learning
Traditional machine learning methods require human input for the machine learning software to work sufficiently well. A data scientist manually determines the set of relevant features that the software must analyze. This limits the software’s ability, which makes it tedious to create and manage.
On the other hand, in deep learning, the data scientist gives only raw data to the software. The deep learning network derives the features by itself and learns more independently. It can analyze unstructured datasets like text documents, identify which data attributes to prioritize, and solve more complex problems.
For example, if you were training a machine learning software to identify an image of a pet correctly, you would need to take these steps:
* Find and label thousands of pet images, like cats, dogs, horses, hamsters, parrots, and so on, manually.
* Tell the machine learning software what features to look for so it can identify the image using elimination. For instance, it might count the number of legs, then check for eye shape, ear shape, tail, fur, and so on.
* Manually assess and change the labeled datasets to improve the software’s accuracy. For example, if your training set has too many pictures of black cats, the software will correctly identify a black cat but not a white one.
* In deep learning, however, the neural networks would process all the images and automatically determine that they need to analyze the number of legs and the face shape first, then look at the tails last to correctly identify the animal in the image.
