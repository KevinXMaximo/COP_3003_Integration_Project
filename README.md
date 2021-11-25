# COP_3003_Integration_Project

**What is this project?**

This project will be a mobile app developed using Flutter, it will consist of a clicker/idle styled game meant to serve as a demonstration of the programming concepts I have learned.

A good example of a clicker game is http://orteil.dashnet.org/cookieclicker/

A good video to understand idle games is https://www.youtube.com/watch?v=g-LziX2HynI

A good video to understand clicker games is https://www.youtube.com/watch?v=j_nI6G3ZDiE

**Why was this project chosen?**

The reason why I chose this project is due to an interest in mobile and game development. I like the idea of making a project I can run anywhere as long as I have my phone with me, and I would also like to do a project which I can easily share with friends and family.

**By when will this be done?**

The project will be delivered December 15th, but as detailed in the issues page there will be different sprints commited both on November 4th and November 24th.

**First Prototype**

![Prototype1ActualReal](https://user-images.githubusercontent.com/62119614/140718015-a6da43ed-90c6-4cd1-94d4-98a3a3abb556.PNG)
  
The first prototype consists of two buttons, one with a counter for oranges and one with a counter for apples. These buttons can be pressed to increment their respective counters, while at the same time incrementing the overall "fruits" counter. This concept will eventually evolve into upgrades which will allow for more fruits to be obtained per click bought at the expense of total fruits, as well as an automic fruit farm which will earn the player a set number of fruits based on real time passage.

**Second Prototype**

The second prototype adds tutorials, farmers and timers. The tutorials are meant to guide the player through the mechanics of a clicker game, explaining the basics.

Tutorial 1:

![tutorial1Actual](https://user-images.githubusercontent.com/62119614/143375001-6d24b689-811d-48e5-8e81-7e5500464a18.PNG)

The app begins by only showing the total fruit counter, the apple counter and the "+1 apple" button, along with tutorial 1. The first tutorial explains to the player that they can make fruit by pressing the button, and prompts them to do so. This is meant to demonstrate the most basic aspect of a clicker game: you can click to increment a counter. Once the user has clicked the button 6 times, the game assumes they understand what the tutorial has to teach and moves on.

Tutorial 2:

![tutorial2Actual](https://user-images.githubusercontent.com/62119614/143375081-09db8266-73f8-476d-a8ed-32f62f715110.PNG)

Now that the user has clicked the apple button 6 times, they will unlock the orange button. Tutorial 2 will also be displayed, and it will explain that this is another type of fruit, which much like apples can be incremented through button clicks. Once the user has obtained 6 oranges they are ready to move on.

Tutorial 3:

![tutorial3ActualActual](https://user-images.githubusercontent.com/62119614/143375171-7e4f4d56-5af3-4d4e-8e6b-343ce1d24391.PNG)
  
At this point, the player likely understands how fruit buttons work, so the store is introduced. In the store, players can buy farmers, which tutorial 3 explains can passively harvest fruit for you. Farmers have a cost, which in the case of this first apple farmer is 6 apples. Every time a farmer is bought, their price increases exponentially, that way the player has to work harder to be able to buy another farmer. Each apple farmer increases apples once every 2 seconds.

Endgame: 

![incrementingApples](https://user-images.githubusercontent.com/62119614/143375572-81195d00-f2e1-4763-9298-dae5dc954985.gif)

The endgame will mostly consist of buying more farmers in order to increase the amount of fruits you own passively per second.

**Future Updates**

Future updates will include image drawings for the upgrades, scrolling between two pages ("Fruits" and "Store" will be in two different pages), upgrades aside from farmers and an overall better, slicker UI. The final version will also implement features to satisfy the requirements for the integration project.
