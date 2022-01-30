# DL_Waste_Classification

# Introduction
If we, as a society, do not take action to prevent it from happening, the accumulation of non-recyclable garbage on landfills throughout the world, as well as the lengthy period it takes for most of its contents to biodegrade, will have a substantial impact on our lifestyle in the near future. Furthermore, among the most well-known threats to humans, waste buildup can aid disease transmission via vectors such as flies, mosquitoes, and a variety of other insects. Furthermore, in addition to the destruction of natural ecosystems' beauty, deforestation, and terrain occupancy to make room for landfills, soil and water can be contaminated by harmful substances found in inadequately handled trash. At the same time, pollution may disrupt the food chain, resulting in increased illnesses and health problems for humans and natural ecosystems throughout the planet.

There are three key reasons why trash buildup has become a more serious concern during the last 50 years. 
- The first is the lack of recyclable things on the market, despite the fact that corporations have been manufacturing more sustainable and environmentally friendly products for a long time. 
- The second cause is overpopulation, which is one of the most widely discussed issues today. The fact that a large number of people require a variety of resources creates a complex logistic challenge when it comes to trash generation, resulting in an increase in the percentage of products that could be recycled but instead end up in a landfill or even the ocean, endangering the lives of thousands of marine species. 
- Finally, the third cause is our lack of participation as a society in issues such as climate change.

To demonstrate the waste accumulation problem in terms of data, it is necessary to know that the global population produces between 7 and 9 billion tonnes of waste per year, of which 70% is mistreated and ends up in landfills, polluting natural environments and posing new health risks such as ocean microplastics. This information relates to the total quantity of utilised, unwanted, and discarded items produced by humans. There is, however, a difference to be made between total trash produced and so-called Municipal Solid Waste (MSW), which only comprises rubbish created in metropolitan centres or their impact regions. In terms of the volume of MSW produced in comparison to the rest of the trash, around 2 billion tonnes of urban rubbish is created each year, with approximately 33% of that not being properly handled. It indicates that each individual produces between 0.1 and 4.5 kilos of garbage every day, on average 0.7 kilogrammes. Furthermore, because to the constantly rising world population and the necessity for intense use of natural resources for the growth of industry and the maintenance of our civilization, it is predicted that MSW will increase to 3.4 billion tonnes by 2050.

In an ideal world, a fully implemented circular economy model would be a good answer to the accumulation problem, as well as climate change and even supply shortages in some parts of the world. That's because its three guiding principles (reducing waste and pollution, cycling goods and materials, and renewing nature) lead to a more efficient manner of managing natural resources that we don't always value appropriately. However, due to technological, engineering, and logistical constraints, carrying out such a complicated scheme in its entirety is difficult.

### Machine Learning in Environmental Care
Despite these limits, certain developing new state-of-the-art technologies are beginning to alter our perceptions of and responses to these issues. Machine Learning, a branch of Artificial Intelligence that allows machines to learn specific and complex tasks such as classification, prediction, decision making, content generation, and so on, by combining large amounts of data with advanced learning algorithms inspired by how humans learn, is one of the most well-known nowadays. Because of its scalability and effectiveness, automating such jobs with machine learning may be immensely beneficial to people.

Machine learning has the potential to automate a wide range of jobs when it comes to sustainability and circular economy implementation. From data trend predictions that improve the quality of the air we breathe to finding patterns in data collected to measure global warming over time, identifying waste in natural environments, and even classifying between different types of garbage materials to improve the performance of waste treatment plants, there are many applications for data analytics. As a result, accurate identification and discrimination of recyclable goods from the rest of the trash can be a key step toward a circular economy model that is sustainable. However, machine learning is currently used in more environmental processes than one may assume. A model's accurate prediction of energy or product demand, for example, helps prevent natural resource waste. Furthermore, sophisticated models can interact with chemical structures to develop novel materials, enhancing the efficiency and recyclability of daily items.

# Objectives
The goal of this project is to contribute to the development and improvement of machine learning techniques aimed at addressing environmental issues such as the ones listed above (waste accumulation, global warming, pollution, and so on) by developing a model capable of sorting between nine different types of waste based on fabrication materials and thus recyclability. Furthermore, because it is open-source, it will be subjected to testing by professionals and subject matter experts. When it comes to increasing the performance of models in the field of machine learning, as well as the data collection and processing techniques utilised in the process, experimenting is crucial.

Furthermore, detailing the fundamental workings of machine learning algorithms and the advantages they may offer to humanity in the future will help society get a better understanding and faith in such new exponential technologies. Furthermore, concentrating on the adoption of new disruptive ways to try to tackle environmental problems raises our collective awareness of the need of environmental protection, allowing for the possible application of new sustainable habits in our everyday lives.

# Action Plan
- Prepare the dataset and preprocess it. (Create training, validation, and testing datasets)
- Outline the Model and choose the activation function/s.
- Set the appropriate advanced optimizers and the loss functions.
- Make the Model learn. (Backpropagation)
- Test the accuracy of the model.

# Algorithm
### 1) Import the relevant libraries.
### 2) Data Collection and Preprocess the Data.
  - i. Load the Dataset.
  - ii. Split the Dataset into training and testing dataset.
  - iii. Optimise the training and the testing performance.
  - iv. Perform Data Augmentation.
### 3) Model Outlining (Customised ResNet152)
  - i. Load the pre-trained ResNet152 Model. (without feed-forward NN)
  - ii. Add Customised CNN on top of ResNet152 Model.
  - iii. Combine ResNet152 and Customised CNN.
  - iv. Optimise the algorithm.
  - v. Fit the model on the training dataset. (Make the model learn)
  - vi. Test the model

### Note: - The Models have been tested on Mac M1
