---
title: Experimenting with Unity Netcode for GameObjects
emoji: 📶
metaDescription: This is a sample meta description. If one is not present in your page/project's front matter, the default metadata.desciption will be used instead.
date: 2019-01-01T00:00:00.000Z
summary: A study of a Unity plugin that adds online functionality
---

### Project Info

This project was created for an independent study I worked on during the first semester of my senior year at Allegheny College. It is an application of the Unity plugin called *Unity Netcode for GameObjects* and serves to show its most basic implementation. After researching the function of online gaming and parsing through the documentation of the plugin, I was able to create a game-like environment to test it. The application can be opened as a server, client, or host. The server mode creates a live instance of the environment and provides its code that players can use to connect. The client mode takes in a server code and connects to that server, spawning in the player as a capsule object that they can move around. The host mode acts as both a server and a client, immediately connecting the client to its own server. Because this project uses a client server model, the running client side programs use interpolation to try and make the application less laggy.

[Here](https://github.com/Jacob-Allebach/UnityNetworkTesting) is a link to the repository where you can download the files and test its functionality.
