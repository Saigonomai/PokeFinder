# Project1Team5

## What is it?
The purpose of our webpage is to find the nearest place near you that would suit a Pokémon.

By parsing through the various locations in a typical city, we have created a simple site that would cross-reference the information gained through the TomTom maps to find habitats that would suit various Pokémon’s from generation 1.

This is a fun website where Pokémon fans can find where their favorite Pokémon may flourish in real life. Which fan would not want that?
## How Does it work

Based on user input (name of Pokemon):
1. Reference the Pokemon API and return the Pokemon's image, name and habitat
2. Take the value of habitat and interpret it into our own search terms that aligns with google's search API
3. Cross-reference the habitat  with the translated search term with the Google API and return a habitat result on the page. 
4. Display the map of the habitat location on the web.


| Habitat           | Keyword     |
|-------------------|-------------|
| Cave              | Escape Room |
| Forest/Grasslands | Botanical   |
| Mountain          | Bouldering  |
| Rare              | Attraction  |
| Rough-terrain     | Fitness     |
| Sea               | Rigging     |
| Urban             | City Center |
| Waters-edge       | Beach       |
