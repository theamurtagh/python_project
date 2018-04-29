# python_project

Project to investigate  **fishers iris dataset** (https://en.wikipedia.org/wiki/Iris_flower_data_set)
![iris_germanica_ purple_bearded_iris _wakehurst_place _uk_-_diliff](https://user-images.githubusercontent.com/36824025/39383140-117c858a-4a60-11e8-9ed2-4c565890401f.jpg)

## The Iris Dataset 
The Iris Flower data set was introduced by the statistician and biologist Ronald Fisher in 1936. It is also sometimes called Andersons Iris Dataset because Anderson collected the data. The Iris data set provides the measurements in cms of the variables sepal length and width and petal length & width for 50 flowers from three species of Iris.  

## What is the function of the Sepal 
The sepal refers to the outer parts of the flower, typicall green and leaf like.  It is first part of a flower to form.Sepals function to protect the developing flower and keep it from drying out.

## What is the function of the Petal 
Petals are modified leaves that surround the reproductive parts of flowers. They are often brightly colored or unusually shaped to attract pollinators. Collectively they are called carolla 

## Iris Setosa
The Iris Setosa is characterized with having tall branching stems, medium green leaves and violet to purple to blue flowers, though there are also plants with pink and white flowers. It is sometimes called the beachhead Iris due to its tolerance to thrive in salty maritime conditions. It is also on the red list in Japan as an endangered species 

![iris setosa](https://user-images.githubusercontent.com/36824025/39409195-a86a0488-4bda-11e8-8ffc-de5cb934c52f.jpg)

## Iris  Versicolor
The Iris Versicolor is known as the purple Iris in Ireland and UK Versicolor means variously coloured. Its flowers are typically pale to deep blue and bloom during may to july. Its leaves are sword shaped and grow from the lowest part of its stem and it has properties that make it mildly poisonous to humans. Its mass roots protect shorelines of rivers and lakes

![iris_versicolor_3](https://user-images.githubusercontent.com/36824025/39409205-d29ede7c-4bda-11e8-9471-0d49a7149d2e.jpg)


## Iris Virginica
Has light blue to deep violet flowers. The plants are up to two feet tall. It grows commonly in wet ditches , swamps, meadows and the edges of streams. 
The Cherokee use this medicinal plant for traditional medicine uses. The root is pounded into a paste that is used as a salve for skin. An infusion made from the root is used to treat complaints of the liver

![iris_virginica](https://user-images.githubusercontent.com/36824025/39409211-f210b758-4bda-11e8-8e81-14b787c4fb81.jpg)




# My Investigation of the Iris Dataset
For this investigation I began with importing the dataset and opening it in Python. I tried different tools to open the file with and used Pandas to process the text, as i found it useful to be able to see the species name and which measurements referred to what part.

<img width="634" alt="screen shot 2018-04-29 at 17 12 47" src="https://user-images.githubusercontent.com/36824025/39409384-f68f1d44-4bdd-11e8-8897-a93e876bebb2.png">


I took averages from each column with the following results. 

| Col 1 | COL 2  | COL 3 | COL 4 |
|-------|--------|-------|-------|
| 5.1   | 3.5    | 1.4   | 0.2   |

I studied a tutorial on Machine learning and was able to the following infomration summary. 

|       | Sepal Length | Sepal width | Petal Length | Petal Width |
|-------|--------------|-------------|--------------|-------------|
| Count | 150          | 150         | 150          | 150         |
| Mean  | 5.843333     | 3.054000    | 3.758667     | 1.198667    |
| Std   | 0.828066     | 0.433594    | 1.764420     | 0.763161    |
| Min   | 4.300000     | 2.000000    | 1.000000     | 0.100000    |
| 25%   | 5.1          | 2.8         | 1.6          | 0.3         |
| 50%   | 5.8          | 3.0         | 4.35         | 1.3         |
| 75%   | 6.4          | 3.3         | 5.1          | 1.8         |
| Max   | 7.9          | 4.4         | 6.9          | 2.5         |


I used Matplotlib to generate a histogram

![figure_1](https://user-images.githubusercontent.com/36824025/39409094-e727e318-4bd8-11e8-9312-9053009524e1.png)

I then used scattermatrix to generate a scatterplot diagram.


![figure_1](https://user-images.githubusercontent.com/36824025/39409125-538063a0-4bd9-11e8-80bb-feb2a6d09333.png)







