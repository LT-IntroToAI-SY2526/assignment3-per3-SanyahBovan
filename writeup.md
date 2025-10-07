# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?

Some key programming concepts or techniques that I learned while completing this assignment is how I can use input to search and successfully find my output, I also learned how to use the for & if functions in python.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The overall movie chatbot system works by using an input from user spanning from the year, director,title  or actors to find a movie in the database. An example of this would be the year by title; the user would input a title of a movie and the year it was made will outprint. 

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

This type of pattern-matching chatbot system could be used in a fashion collection database, and it could use user input such as year of debut, stylist/brand, models, and places to find the seasonal collections of different brands. I actually have no idea how I might improve this system for practical use, but maybe I could utilize adjectives to describe the collections such as "elegant".