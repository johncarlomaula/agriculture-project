# Optimizing Agricultural Production

**Project Description:** In this project, I use k-means clustering to discover patterns in agriculture data before building a predictive model to recommend suitable crops to plant depending on a given set of farming and environmental conditions. 

**Main Goals:**
- Explore and analyze the data
- Use a clustering algorithm to find patterns in the data
- Build a predictive model to recommend suitable crops for planting


### [View Project](https://github.com/johncarlomaula/agriculture-project/blob/main/agriculture.ipynb)

##


**Key Findings:**
1. The k-means clustering algorithm did well in determining which crops share similar environmental conditions for growth with NPK ratios and humidity being the most distinguishing variables:
    - One cluster is characterized by a **large ratio of nitrogen content in the soil** and consists of watermelon, cotton, coffee, banana, jute, rice, muskmelon, and maize.
    - Another cluster is characterized by a **moderate ratio of phosphorus content** with **low humidity** and consists of lentil, moth beans, chickpea, kidney beans, mango, black gram, and pigeon peas.
    - Another cluster is characterized by a **large ratio of phosphorus and potassium content** and consists of grapes and apples.
    - The final cluster is characterized is characterized by a **low ratio of nitrogen, phosphorus, and potassium content** with **high humidity** and consists of pomegranate, mung bean, orange, coconut and papaya. 
2. The random forest model did well in predicting suitable crops to plant based on a given set of conditions with almost perfect accuracy, but the dataset used in this analysis might not be representative of farming conditions around the world.
3. This process could be useful for precision agriculture with the potential to increase farming efficiency and yield.



## 

**Links**

Here are the resources I used to complete this project:

1. https://github.com/Gladiator07/Harvestify
2. https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm
3. Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani. (2013). An Introduction to Statistical Learning with Applications in R.
