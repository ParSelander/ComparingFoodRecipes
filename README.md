# Comparing food recipes for identifying unique ones 

## Summary

Compare recipes and group similar ones together to make it easier to find interesting alternative dishes to cook.
Also classification of recipes based on ingredients, e.g. meat, poultry or vego

## Background

Many people have accumulated a plethora of recipes but cannot find it or can only find recipes that are similar to what they want.
By specifying the ingredient (s), you can then get suggestions for dishes and these grouped if they are largely the same, regardless of what they are called.

Problem:
* Recipes have different names, e.g. taco dinner, Friday dinner with tacos and guacamole 
* Category is missing, e.g meet, fish
* Ingredients may vary slightly
* Quantities vary
* Different cooking methods

## How is it used?

By an window app connected to a Azure datastore with recipes.
In it you can search för recipes and/or upload your own for storage / to be analyzed.

## Data sources and AI methods
I am going to use a document store of pdf recipies.
All documents are analyzed and all text is stored in a SQL server.
I will use the methods I learned in the course to look at what and how I can group dishes.

## Challenges
To start with, learn Python.

## What next?
Writing a web application.
## Acknowledgments
I'd like to thank Reaktor, University of Helsinki and everyone else who have been a part in making both Elements of AI and Building AI a reality.
