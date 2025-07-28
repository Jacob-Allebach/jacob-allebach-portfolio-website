---
title: Unity Map Generator Plugin (Senior Thesis)
emoji: 🗺️
metaDescription: This is a sample meta description. If one is not present in your page/project's front matter, the default metadata.desciption will be used instead.
date: 2024-05-23T00:00:00.000Z
summary: A plugin for Unity that generates two-dimensional dungeons based on user inputs and creations
---

### Project Info

*Completed Spring 2024*

This project was created as my senior thesis at Allegheny College and is the culmination of my research throughout my last two years there. The research paper written as part of this work examines several different methods of generating two-dimensional maps as well as the use cases for them. Most of my findings when researching the topic were focused on tile-by-tile map generation using algorithms like Perlin noise, so I thought it would be helpful to create an article that focuses on room and connector generation instead as there weren't many resources discussing this style.

The product of this project is a plugin for Unity that generates two-dimensional dungeon maps by taking user-created rooms and hallways and randomly connecting them until the user specified conditions are met. The user of the plugin must make room and hallway objects in a particular way for them to work with the plugin, then they can specify how many rooms they want to generate and which object in the scene they will generate under. Although the resulting maps are very simplistic, it's a good showing of this generation style and how it can be utilized in games.

[Here](https://dspace.allegheny.edu/items/e1bf6faf-d369-496c-8346-fdb7344e8003) is a link to the DSpace page with the two scripts required to run the generator as well as the thesis paper which includes instructions on how to set up the program.