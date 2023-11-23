# Griffin Bonomo-Clough

## Introduction

> I'm a developer currently studiyng Computer Science at John Abbott College.
 <!!ADD MORE!!>

## Contact

- insert email here
- insert Github link here

## Projects

Below is a list of projects I've worked on over the past few years as well as what I learned from them.

### PrivacyXPresso

> [PrivacyXPresso](https://github.com/tjklint/BellGeekfest2023) is a web app that was developed for the Bell Geekfest 2023 Hackathon, in which it placed top #5. <br/><br/> It was developed over the course of a day and a half alongside [tjklint](https://github.com/tjklint) and [DylanSavelson](https://github.com/DylanSavelson).

PrivacyXPresso is a hub for privacy-conscious individuals to manage the data they share with companies and test the strength of their passwords. 

<img height="300" width="auto" alt="DataEraseX Demo" src="https://github.com/GriffinBonomo/griffinbonomo.github.io/blob/main/images/DataEraseX.gif?raw=true">

The main feature, <ins>DataEraseX</ins> allows a user to demand a company delete their user data via email in accordance with the [CCPA](https://oag.ca.gov/privacy/ccpa) and the [GDPR](https://gdpr.eu/eu-gdpr-personal-data/).<br/>


<img height="300" width="auto" alt="Password Checker Demo" src="https://github.com/GriffinBonomo/griffinbonomo.github.io/blob/main/images/PasswordTester.gif?raw=true">

PrivacyXPresso also includes a basic password strength tester with a dictionary of over <ins>1000</ins> words. It was developed as a bonus feature.

Further information about how this email works [here](https://ico.org.uk/for-the-public/your-right-to-get-your-data-deleted/#no).

#### The Development Process

The first few hours of the hackathon were hectic as I had never actually met my teammates in person before. Nevertheless, we quickly established roles and a document to organize our notes and ideas for how the app should look, feel and work. 

I worked primarily on the <b>JavaScript</b> side of things, helping teammates with merge conflicts along the way as well. At each major step of development, I showed the code to my teammates and asked them to test it out. This strategy proved to be incredibly helpful in the long run as it avoided long debugging sessions.

#### Features to Add

While the hackathon has ended, there are still some features I would like to add to this app.

First is a better password strength tester. In reality, [dictionary attacks](https://www.techtarget.com/searchsecurity/definition/dictionary-attack) often use much more than <ins>1000</ins> words and aren't fooled by simply adding numbers to the end of a commonly used word like "password". A larger dictionary or a more sophisticated method of determining the complexity of a string would be a great improvement.

Second would be using the [Gmail API](https://developers.google.com/gmail/api/guides) to send the generated email to the selected company automatically.

>A link to the code can be found [here](https://github.com/tjklint/BellGeekfest2023).

### JS Canvas Video Game

> This is a game that is still in early stages of development. It uses the [JavaScript Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) for graphical rendering and utilizes many of the techniques learned in my Game Programming course at John Abbott College.

The intention for this game is to fuse the stealth mechanics of games like [DEADBOLT](https://store.steampowered.com/app/394970/DEADBOLT/) with the randomness and replayability of [roguelikes](https://en.wikipedia.org/wiki/Roguelike) like [The Binding of Isaac](https://store.steampowered.com/app/250900/The_Binding_of_Isaac_Rebirth/).

> Below is an example of a primitive level that will be fleshed out and polished in the future.

<img height="300" width="auto" alt="Basic game level" src="https://github.com/GriffinBonomo/griffinbonomo.github.io/blob/main/images/GameLevel.PNG?raw=true"> 

#### Features

- The game currently supports full player movement and a basic collision system (more on that below) as well as character animation.

- A rudimentary projectile shooting system has been added.

- Levels can be loaded into the game from a map-data file using a specified template.

#### Features in Development

- Enemy pathfinding using an implementation of the [A* Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm) is currently in development.

- Transitioning to the [Tiled](https://www.mapeditor.org/) map editor for creating levels.

- Major refactor of movement and physics code for improved performance.

#### What I've Learned

Game development is a difficult process that requires an extraordinary amount of planning and patience. I've realized that spending some time up-front to set up tools, templates and environments is crucial for efficient development. 

> A few notable examples would be:

- Researching common data-structures and optimizations for a problem before jumping straight into code.

- Drawing out state diagrams for complex events or processes.

- Setting up a simple asset pipeline using Photoshop with custom templates, brushes, colour palettes and pixel grids matching the resolution of my sprites. 

# ADD LINK TO REPO HERE

### Pokemon App

> This is mobile app developed in [Kotlin](https://kotlinlang.org/) using [Jetpack Compose](https://developer.android.com/jetpack/compose?gclid=CjwKCAiAjfyqBhAsEiwA-UdzJDvQgolHxVXeCMxZp0L3VlLYY0EX-Ph4dblLUKxLbZUOV83HPQ5JlhoCfLYQAvD_BwE&gclsrc=aw.ds) for my Application Development II course at John Abbott College.

> Note: This app is still in development and the UI is subject to change.

<img height="300" width="auto" alt="Pokemon App info screen" src="https://github.com/GriffinBonomo/griffinbonomo.github.io/blob/main/images/InfoScreen.JPG?raw=true"> 