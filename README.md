# Styleme
Experience of a digital wardrobe

## Introduction
Keeping up with fashion and fashion trends can be a really daunting task sometimes. "I have a blue shirt, which of my trousers should I wear it with". The problems go on and on, but not for long. The world has gone digital, why shouldn't your `wardrobe`. Styleme would assist its users in matching clothes based on current fashion trends and renowned expertise.

## Overview
![project structure](/structure.png)

## Description
1. **User**: An object representing the real world user. This is the channel through which queries and samples are received.
    - Holds authentication data for the real world user.
    - Creates clothe samples and sends to be placed in the wardrobe.
    - Creates queries for particular clothe and color combinations.
    - Holds user specific fashion preferences.
    - Receives the query result.

2. **Sample**: Image of a particular clothe to be analysed and categorised into the wardrobe.
    - Can be received from cloud storage, camera or any storage media.

3. **Wardroble**: A virtual enviroment for the classification of clothes. Each sample placed in the wardrobe would be done according to its properties.
    - It is the storage area for clothes.
    - Can be made available accross devices through cloud storage.

4. **Clothe**: Object representing the characteristics of a particular sample as placed in the wardrobe.
    - Can have varying properties depending on its type.

5. **Query**: A request for a particular clothe combination made by the user.
    - Eg. requesting for what trouser to wear with a blue shirt.

6. **Fashion**: Set of rules guiding colors and clothe combinations.
    - Updated to meet current fashion trends.
    - Takes user preferences into account.

7. **Style**: This is the end point of a users query.
    - Contains suggested combinations that are delivered to the user.

8. **Intelligent systems**: These are sopphisticated neural networks designed to perform specific tasks. There are two main neural networks involved.
    1. **Organiser**: This is responsible for analysing the given sample and arranging/categorising it into the wardrobe.
    2. **Stylist**: This is responsible for receiving user queries and producing the result base on fashion trends, user preferences and available clothes in the wardrobe.

-------------------------------------------------------------------------------------------------
## Targets
This project would be targetting both mobile and web platforms.

### Andrid Platform
For detailed documentation on the android implementation click [here](/Android.md).

## License
This project is licensed under the Apache License Version 2.0, January 2004. Read the [license](/LICENSE) statement for more information.

## Contact
- Support: orsteg.apps@gmail.com
- Developer: goodhopeordu@yahoo.com