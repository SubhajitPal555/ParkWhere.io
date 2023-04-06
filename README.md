# ParkWhere.io

ParkWhere.io is a web application that helps me predict parking availability at my apartment block. 

![image](https://github.com/SubhajitPal555/ParkWhere.io/parkwhere_demo_gif.gif "GIF image")



## The motivation behind ParkWhere.io

Parking spaces are always limited at the apartment block where I live. Very often, I return home at night, only to end up parking a few hundred metres away. 
    
It's especially frustrating when there are things to carry from the car and an active toddler to manage!
    
One day, an idea popped into my head! Why not collect some data , and put data science into action? 

Data collected using API and Web scrapping...!!

## How does it work?

I divided available parking spaces at my apartment block into four zones, 'Zone 1' being the nearest. For eight months, I recorded the dates, times and zones at which I found a parking lot upon returning home.
    
Using the collected data, I trained a binary classification model using Logistic Regression that predicts, given a specific time I return home, how likely I will find a parking lot nearest to my block.

