# meta-f2p

In this project you will find the necessary resources to apply use model driven approach for game monetization.
Meta-F2P is a domain specific modeling language used to design free-to-play games' monetization.
It is represented as an ecore meta-model that contains the necessary rules and elements to specify how a game will be monetized base on a set of common monetization strategies.

Here you will find the following:
 - Working unity test script showing how a instantiated game monetization can be loaded in a game
 - Meta-f2p ecore meta-model: cam be loaded and edited inside Elipse Modeling Framework
  - Meta-f2p API: code generated from the meta-model using ecore-csharp framework. Needed to programatically instantiate new models using cross-ecore library inside a game project.
 - Summoners.gamemonetization: sample monetization model based on Summoners War game. It can also be edited inside the Game Monetization Editor(Eclipse Runtime Aplication) generated using EMF ecore tools.

![Model Driven Game Monetization](Assets/Images/mdgd.png)


##IMPORTANT NOTES
- Fix for XMI Error: eet Unity to .NET4 in Edit>Project Settings>Player>API Compatibility Level 
- Plugin for visualizing instantiated models as class diagrams http://dynamicgmf.sourceforge.net/