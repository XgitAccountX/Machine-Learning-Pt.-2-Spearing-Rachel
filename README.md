# Machine-Learning-Pt.-2-Spearing-Rachel


'''
Data Set Link: https://catalog.data.gov/dataset/mypyramid-food-raw-data#sec-dates
Publisher: Food and Nutrition Service, Department of Agriculture
Maintainer Angela Leone
Metadata: created Date November 10,2020
Metadat updated data November 13, 2020

My Pyramid Food Raw Data

Food and Nutrition Service USDA (United States Department of Agriculture)
'''


Part one: calories spread across multiple distribution.
![histogramCalories](https://user-images.githubusercontent.com/95445097/167066798-469f57a9-5ac9-4664-9748-464c4e6d5223.png)


#Three. Dropping non-numeric columns.
#food_Code should be dropped because its unique identifier doesn't carry any 
#value/weight in model training
#portion_Display_Name should be dropped because we have portion_amount 
#which tells us the actual numeric amout, and we don't need a label for that.
#keepingDisplay_Name because we may want to label what food the calories 
#generated belong to



#label encoding chosen because while there is a size difference between a 
#chocolate bar and a cereal box, it is difficult to order an equally weighted
#can of ravioli versus a soda can. 



It was showing a graph of training data for linear regression, but when I changed to test train method it stopped working and threw errors based on input which I wasn't sure how to fix--cutting the rows didn't do anything.

#part 6. make argument.
# I believe that logistic regression would've worked better if i had managed to get the error out of my code,
#I think it woudl handle the multiple different types of vairables
#to predict calories better than linear regression, which has a very simplistic
#approach to prediction.
