# Project-recipe-recommender

# Welcome to Cravings!

In this project we created Cravings. You put in your available ingredients and we provide you with unique and special recipe + a list of missing ingredients as PDF.

## Content

- [Project Description & Project goals](#descriptionandgoals)
- [Structure](#structure)
- [Resources](#resources)

<a name="descriptionandgoals"></a>

## Project Description & Project goals

By using Web Scraping and APIs, the goal was to invent a new product. As we recognised that we think a lot about what to eat and when to buy it we decided to make the day to day life easier and also prevent cooking the same meal everyday which is also not very nutritious. 
So how could we spent less time in thinking about what to cook and more in actual cooking the meal?

<a name="structure"></a>

## Structure

1. The user inputs the available ingredients he/ she has at home.
2. With the API from Edamam we are sourcing recipe recommendations.
3. We are scraping 2 different supermarkets in order to provide the price of the missing ingredients. If the first supermarket doesn´t have the ingredient
   the code starts scraping the second supermarket. 
4. Output: the user sees three different recipes ascending regarding the amount of missing ingredients.
5. We are using the spacy library for natural language processing. 
6. We are using the FDPF library in order to creat the PDF of the recipe and the missing ingredients list. 



<a name="resources"></a>

## Resources

 
[EdamamApi](https://edamam-recipe-search.p.rapidapi.com/search)  
[AbelandCole](https://www.abelandcole.co.uk/shop/)
[Dutchexpatshop](https://www.dutchexpatshop.com/en/)


